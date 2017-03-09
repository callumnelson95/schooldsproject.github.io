## Welcome to Our Data Science Project

You can use the this site to explore our week and find status updates for our project.

### Blog Post 1

#### Vision

Our overarching goal is to create a means for visualizing public schools across the country and allowing the user to 	filter along a number of parameters. We’re also hoping to include a temporal component, whereby the user can select any of the years from 2000-2016 and see how schools have changed over time, which schools closed and/or underperformed. This feature could interface with information about the passage of important education legislation throughout the years. We hope to help users understand what attributes are correlated with school success. 

#### Data

Our project uses data on public schools from the National Center for Education Statistics (NCES) to create a data pipeline for analyzing and comparing schools across the country. We have school-level enrollment, staffing and retention, school performance, and demographic data. To organize this data, we have developed a star schema with a SCHOOL FACT TABLE that combines School name and primary key with State Name and primary key. 

#### Challenges so Far

So far we haven't had too many issues. One source of frustration has been the relative difficulty we've had with the NCES data repository. You aren't allowed to pull more than 75 columns at a time, which means that we have to pull our data in batches and then append the CSV files. We were able to get some help from a professor in the Ed Studies department who pointed us in the right direction for more accessible data sources.

#### Next Steps	

We hope to work on two things in the coming weeks. First, we'd like to find a way to incorporate major policy changes into our schema such that we can analyze any potential correlation between policy change and school characteristics/performance. We also need to determine what trends to analyze (e.g. performance by state, comparison between public and public charter) to start to get a sense of what the data are telling us and how to disaggregate the data. 

- Group Members
  - Callum Nelson
  - Emma Friesner
  - Meryl Charleston
  - Marianne Le Quere
