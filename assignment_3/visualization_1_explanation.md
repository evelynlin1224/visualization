# Visualization 1 Explanation: Bike Share Trips by Hour

**Dataset link:** [City of Toronto Open Data — Bike Share Toronto Ridership Data](https://open.toronto.ca/dataset/bike-share-toronto-ridership-data/)  
**Public workbook used:** [bikeshare-ridership-2014-2015.xlsx](https://ckan0.cf.opendata.inter.prod-toronto.ca/dataset/7e876c24-177c-4605-9cef-e50dd74c617f/resource/85326868-508c-497e-b139-b698aaf27bbf/download/bikeshare-ridership-2014-2015.xlsx)  
**Visualization file:** `visualization_1_python_hourly_trips.png`

I made this visualization in Python, using `pandas` to clean the workbook and `matplotlib` to make the line chart. My intended audience is people who want a quick, practical read on Bike Share Toronto usage, like city staff, bike-share operators, transportation students, or classmates looking at commuting patterns.

The main message is that weekday rides look very commute-focused. Trips rise sharply around the morning rush hour, drop a bit during the middle of the day, and then peak again around the evening rush hour. Weekend trips are flatter and build more slowly into the afternoon, which feels more like casual or leisure use.

For design, I used a simple line chart because the x-axis is time across the day. I kept one line for weekdays and one for weekends so the comparison is direct. I used markers, a dashed line for weekends, clear axis labels, a legend, gridlines, and peak labels so the viewer does not have to guess what the important points are. I avoided extra decoration because the story is already in the shape of the lines.

To make it reproducible, the Python file downloads the public workbook, reads the two hourly summary sheets, cleans the header rows, removes the total row, and saves the PNG. Someone else can rerun the same script and rebuild the chart from the public source.

For accessibility, I used a large title, readable axis labels, comma-formatted numbers, and line styles/markers instead of relying only on colour. The chart also has a plain-language title and source note.

The people impacted by this visualization could include riders, station staff, planners, and neighbourhoods where Bike Share resources are placed. I focused only on hour of day and total trips because this chart is about timing. I left out demographic fields and individual trip-level details because they were not needed for this message and could distract from the pattern. The “underwater labour” included finding a public dataset, checking the workbook structure, cleaning messy header rows, choosing the right sheets, testing the code, and adjusting the chart so it was readable.