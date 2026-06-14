# Data Visualization

## Assignment 2: Good and Bad Data Visualization

### Requirements:

- Data visualizations are important tools for communication and convincing; we need to be able to evaluate the ways that data are presented in visual form to be critical consumers of information 
- To test your evaluation skills, locate two public data visualizations online, one good and one bad  
    - You can find data visualizations at https://public.tableau.com/app/discover or https://datavizproject.com/, or anywhere else you like! 
- For each visualization (good and bad):  
    - Explain (with reference to material covered up to date, along with readings and other scholarly sources, as needed) why you classified that visualization the way you did.
      ```

      For my bad visualization example, I selected the Tableau visualization “Formula 1 Constructors (2006–2025) https://public.tableau.com/views/Formula1ConstructorsRadialBumpChart/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link ”. The chart uses a radial bump chart to show Formula 1 constructor rankings across the years, with each constructor represented by a different colored line. The visualization looks impressive at first because the circular layout, dark background, and bright team colors make it visually attractive. However, after looking at it more carefully, I think the design makes the information harder to understand than it needs to be. 
      The first problem is that the purpose of the chart is not immediately clear. The chart title does not clearly tell me what question I am supposed to answer. Am I supposed to compare constructor rankings by year? Track one team’s movement over time? Compare championship points? Or understand which teams dominated Formula 1 during this period? A good visualization should be designed around a clear task, as Munzner (2009) argued, and that visualization design should begin by understanding the user’s task and the data before choosing the visual form. In this case, the chart seems to include ranking, time, teams, and possibly points, but the design does not make any one of those tasks easy. 
      The second problem is the radial layout. Time usually works best when it is shown in a simple left-to-right direction because viewers can follow change naturally. In this chart, the years are placed around a circle, so I have to move my eyes around the whole shape and trace curved lines. That makes it harder to quickly follow one team’s rise or fall. It is also not clear whether the outside of the circle means a better rank or a worse rank. The viewer has to guess the meaning of the inner and outer positions instead of reading it from a clear axis. Cleveland and McGill (1984) explain that people read quantitative information more accurately when it is shown through position on a common scale. This chart weakens that advantage because the rank scale is curved and not clearly labeled. 
      The third problem is visual clutter. There are many constructors, many colors, and many lines crossing or overlapping. Because of that, the chart demands a lot of effort from the viewer. I have to keep checking the legend, match colors to lines, and follow a line around the circle without losing it. That may be possible for a Formula 1 fan who already knows the teams, but it is not friendly for a general audience. Goldberg and Helfman (2011) found that reading values on radial graphs can take longer than on linear graphs because viewers spend more time mapping visual positions to values. Waldner et al. (2020) also found that linear charts were more accurate and efficient than radial charts in their comparison of radial and linear layouts. 
      The time period also needs more explanation. The title says 2006–2025, and the caption describes it as the last 20 seasons, but the chart does not explain why this period matters. If the main idea is “the last 20 seasons,” that should be stated more clearly in the title or subtitle. If the main idea is to show a major change in Formula 1 constructors, then the chart should highlight that story more directly.
      

      ```
    - How could this data visualization have been improved?  
      ```
     For the bad example, to improve this visualization, I would redesign it based on the main purpose. If the goal is to show how constructor rankings changed over time, I would use a standard bump chart with years on the x-axis and rank on the y-axis, with rank 1 clearly placed at the top. I would directly label the lines at the end instead of making viewers rely mainly on the legend. If the goal is to compare championship points, I would use a line chart or small multiples, with one panel for each major constructor. Javed et al. (2010) found that separated views such as small multiples can help people compare multiple time series more efficiently, especially when there are many lines. If the goal is simply to show the champion or top teams each year, a bar chart or ranked table would be clearer.

     References
     Cleveland, W. S., & McGill, R. (1984). Graphical perception: Theory, experimentation, and application to the development of graphical methods. Journal of the American Statistical Association, 79(387), 531–554. doi:10.1080/01621459.1984.10478080. 
     Goldberg, J. H., & Helfman, J. I. (2011). Eye tracking for visualization evaluation: Reading values on linear versus radial graphs. Information Visualization, 10(3), 182–195. doi:10.1177/1473871611406623. 
     Javed, W., McDonnel, B., & Elmqvist, N. (2010). Graphical perception of multiple time series. IEEE Transactions on Visualization and Computer Graphics, 16(6), 927–934. doi:10.1109/TVCG.2010.162. 
     Munzner, T. (2009). A nested model for visualization design and validation. IEEE Transactions on Visualization and Computer Graphics, 15(6), 921–928. doi:10.1109/TVCG.2009.111. 
     Waldner, M., Diehl, A., Gracanin, D., Splechtna, R., Delrieux, C., & Matković, K. (2020). A comparison of radial and linear charts for visualizing daily patterns. IEEE Transactions on Visualization and Computer Graphics, 26(1), 1033–1042. doi:10.1109/TVCG.2019.2934784. 
     '''
     
     
    - Explain (with reference to material covered up to date, along with readings and other scholarly sources, as needed) why you classified that visualization the way you did.
      ```
      For my good visualization example, I selected “Annual Degrees and Certificates - #VOTD” by MiraCosta College https://public.tableau.com/app/profile/mcc.rpie/viz/AnnualDegreesandCertificates_16487718324400/Awards . I chose this example because the topic connects directly to my area of study in education. The dashboard is not only visually clear, but also useful for understanding institutional trends in higher education. 
      This dashboard works well because the purpose is easy to understand. The title says “Degrees, Certificates and Diplomas,” and the subtitle says “Annual Count of Awards.” That tells the viewer what the data is about before they even start reading the chart. The main stacked bar chart shows yearly totals from 2014–2015 to 2023–2024, and the labels above the bars make the annual totals easy to read. The table below the chart gives exact numbers for each award type, such as Associate of Arts, Associate of Science, Certificate of Achievement, and Certificate of Proficiency. This is helpful because the viewer can first get the general trend from the chart and then check exact values in the table. This follows Shneiderman’s (1996) information-seeking idea: give users an overview first, then allow details when needed. 
      The chart type also fits the purpose. Since the dashboard is comparing counts across academic years, a bar chart is a reasonable choice. The viewer can quickly see which years had higher or lower award counts. Cleveland and McGill (1984) argue that position and length along a common scale are among the clearest ways to communicate quantitative values, and this dashboard uses that principle better than the radial Formula 1 chart. 
      Another strength is that the dashboard shows both the total and the categories. I can quickly see that some categories, such as Associate of Arts and Certificate of Achievement, make up a large portion of the awards, while smaller categories take up much less space. I would not say the chart shows exact percentages, because it is not a 100% stacked bar chart. A better way to describe it is that the chart shows the relative share of each award type within each year, while the table provides the exact counts. This makes the visualization useful for both quick reading and closer analysis.
      The dashboard also makes a good accessibility effort. It gives viewers two color options: “MiraCosta Blues” and “High Contrast.” This matters because viewers do not all see color in the same way. High contrast can make text, bars, and chart elements easier to read, especially for people with low vision or color-vision differences. The World Wide Web Consortium explains that enough contrast helps users read text and distinguish visual information, and meaningful non-text elements should also be visually distinguishable. The dashboard also includes a data table, so the viewer does not have to rely only on color to understand the information. Harrower and Brewer (2003) also explain that color schemes should be chosen carefully based on the type of data, the audience, and the display environment. 
      I also like that the dashboard separates different questions into different pages or views. The Annual Count of Awards page answers the broad question of how many awards were given each year. Other pages, such as award detail, individual graduate counts, and overview information, help users look at the data from different angles. This is important because “number of awards” and “number of graduates” are not exactly the same thing. One student may earn more than one award, so separating those ideas makes the dashboard more responsible and less misleading. 
      '''

- How could this data visualization have been improved?  
    '''
    First, the visible chart should include a clearer data source or reference note. The screenshot does not clearly explain where the numbers come from or how they were counted. Since this is education data, viewers may want to know whether the numbers come from internal college records, state reporting, IPEDS, or another official source. 
    Second, each page should have a short title or explanation near the chart itself. The main page title is clear, but a viewer should not have to go to the Overview page to understand what every dashboard page is doing. A short sentence under each page title would help, such as “This view shows total awards by academic year and award type” or “This view counts unique graduates, not total awards.”
    Third, the stacked bar chart is good for showing totals and major categories, but it is not perfect for comparing every category across time. The bottom segment is easy to compare because it has a shared baseline, but the middle segments are harder to compare because they float on top of other categories. 

    References:
    Cleveland, W. S., & McGill, R. (1984). Graphical perception: Theory, experimentation, and application to the development of graphical methods. Journal of the American Statistical Association, 79(387), 531–554. doi:10.1080/01621459.1984.10478080. 
    Harrower, M., & Brewer, C. A. (2003). ColorBrewer.org: An online tool for selecting colour schemes for maps. The Cartographic Journal, 40(1), 27–37. doi:10.1179/000870403235002042. 
    Munzner, T. (2009). A nested model for visualization design and validation. IEEE Transactions on Visualization and Computer Graphics, 15(6), 921–928. doi:10.1109/TVCG.2009.111. 
    Shneiderman, B. (1996). The eyes have it: A task by data type taxonomy for information visualizations. Proceedings of the IEEE Symposium on Visual Languages, 336–343. 
      
      ```
- Word count should not exceed (as a maximum) 500 words for each visualization (i.e. 
300 words for your good example and 500 for your bad example)

### Why am I doing this assignment?:

- This assignment ensures active participation in the course, and assesses the learning outcomes
* Apply general design principles to create accessible and equitable data visualizations
* Use data visualization to tell a story

### Rubric:

| Component               | Scoring   | Requirement                                                 |
|-------------------------|-----------|-------------------------------------------------------------|
| Data viz classification and justification | Complete/Incomplete | - Data viz are clearly classified as good or bad<br />- At least three reasons for each classification are provided<br />- Reasoning is supported by course content or scholarly sources |
| Suggested improvements  | Complete/Incomplete | - At least two suggestions for improvement<br />- Suggestions are supported by course content or scholarly sources |

## Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:
* Submission Due Date: `23:59 -  2026-06-09`
* The branch name for your repo should be: `assignment-2`
* What to submit for this assignment:
    * This markdown file (assignment_2.md) should be populated and should be the only change in your pull request.
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/visualization/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-2`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
