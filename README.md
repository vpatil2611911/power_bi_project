# Movies Analysis Top Rated
Top rated movie analysis using power BI 

where I've analyses the fascinating movies from box office hits of genre trends, this interactive dashboard dives deep into the cinematic universe, explores the numbers behind film's finest, and lets the data tell you the story behind the silver screen magic.
The dashboard includes key performance indicators such as Total shows, Total Gross, Top 10 shows, and Top 10 shows gross, as well as most viewed genre by gross, box office collection by gross, and box office collection by Runtime.

![movies](https://github.com/vpatil2611911/power_bi_project/assets/111626187/f1f37e7d-2d87-4342-ab53-711f73ec14cd)

DAX for caluculation 
Measures: 
1.Overview = SELECTEDVALUE(imdb_top_1000[Poster_Link],0)
2.Top Shows Gross = SUM(Top10[Gross])
3.Top Shows = COUNT(Top10[Series_Title])
4.Total Box Collection = SUM(imdb_top_1000[Gross])
5.Total Shows = COUNT(imdb_top_1000[Series_Title])

New Table:
Power Query
1.Top10 = TOPN(10,imdb_top_1000)

Power BI report Link: https://app.powerbi.com/groups/me/reports/3915c53e-c33f-4b7c-909c-3713920e20df/ReportSection?experience=power-bi

Project Overview: "Conducted in-depth analysis of box office hits to uncover fascinating insights within the world of cinema."

Interactive Dashboard Creation: "Designed and developed an interactive dashboard that serves as a comprehensive tool for exploring the cinematic universe."

Exploring Genre Trends: "Analyzed and visualized genre trends within the movie industry, providing valuable insights into the types of films that resonate with audiences."

Key Performance Indicators (KPIs): "Incorporated essential KPIs in the dashboard, including Total shows, Total Gross, Top 10 shows, and Top 10 shows gross, to provide a holistic view of movie performance."

Genre Analysis: "Identified the most viewed genre by gross, offering a data-driven perspective on the popularity of different film genres."

Box Office Collection Insights: "Unveiled critical findings related to box office collections, enabling a deeper understanding of the financial aspects of the film industry."

Runtime Analysis: "Examined the relationship between runtime and box office collections, revealing the impact of film duration on audience engagement and financial success."

Storytelling Through Data: "Used data visualization techniques to craft a narrative that brings the data behind the silver screen magic to life."

Data-Driven Decision-Making: "Empowered stakeholders with actionable insights, facilitating informed decision-making within the film industry."

Data-Backed Recommendations: "Leveraged project findings to propose recommendations for filmmakers and studios, guiding them in creating successful films."
