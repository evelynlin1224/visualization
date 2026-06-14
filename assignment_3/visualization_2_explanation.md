# Visualization 2 Explanation: Top Bike Share Start Stations

**Dataset link:** [City of Toronto Open Data — Bike Share Toronto Ridership Data](https://open.toronto.ca/dataset/bike-share-toronto-ridership-data/)  
**Public workbook used:** [bikeshare-ridership-2014-2015.xlsx](https://ckan0.cf.opendata.inter.prod-toronto.ca/dataset/7e876c24-177c-4605-9cef-e50dd74c617f/resource/85326868-508c-497e-b139-b698aaf27bbf/download/bikeshare-ridership-2014-2015.xlsx)  
**Visualization file:** `visualization_2_tableau_top_stations.png`

I made this second visualization with Plotnine, which is a free ggplot-style visualization tool. The file name keeps the requested “tableau” label, but I used Plotnine as the second tool so the work stays fully reproducible from code and does not depend on a private Tableau Public account.

The intended audience is Bike Share Toronto operations staff, city transportation planners, and people interested in how the bike-share network is used. The message is that trip starts are not spread evenly across all stations. A small group of stations, especially downtown stations like Bay St / College St, account for a large number of trip starts. That matters because busy stations may need more docks, more bikes, or more frequent rebalancing.

For design, I chose a horizontal bar chart because station names are long and would be hard to read on a vertical chart. I sorted the bars from highest to lowest, added the trip totals beside the bars, and used a simple layout so the ranking is easy to scan. I did not use a map here because the point is ranking and comparison, not exact geography.

This visualization is reproducible because the Python script reads every monthly route sheet from the public workbook, sums total trips by `Start Terminal`, joins those station IDs to the `Station Key` sheet, and saves the top 10 chart. If someone reruns the script, they should get the same output from the same public data.

For accessibility, I used a clear title, labelled axes, printed values, large text, and a chart type that works well even without colour. The labels are horizontal, so they are easier to read than rotated labels.

The communities impacted by this chart include riders near busy stations, people in neighbourhoods with fewer stations, city planners, and workers who rebalance bikes. One risk is that focusing only on the busiest stations can make lower-ridership or underserved areas look less important, so I would not use this chart alone for equity decisions. I included start station, station name, and total trip count because those features directly answer the question. I excluded end stations, user type, and demographics because they belong to different questions. The underwater labour was combining many sheets, fixing headers, checking station ID joins, handling missing values, and testing the final PNG export.
