# Cyclistic Bike-Share: Google Data Analytics Capstone Project
![Cyclistic](https://user-images.githubusercontent.com/63750425/224968385-9521ab10-d278-4595-a829-08b4f1c645be.png)

This repository features my Google Data Analytics Capstone - Case Study 1 project, the culmination of my training in the Google Data Analytics course on Coursera. It showcases my proficiency in data cleaning, analysis, and visualization using real-world datasets. Designed to drive data-driven decision-making, this project reflects my ability to extract meaningful insights and solve business problems. I invite you to explore my work, and I appreciate your time in reviewing my portfolio!
## Introduction
The Cyclistic Bike Share case study focuses on a fictional company called Cyclistic, based in Chicago. As a junior data analyst, my role is to analyze data from the first three months of 2019 and 2020 to uncover insights about rider behavior and trends. Although Cyclistic is imaginary, the data used in this study comes from Divvy, a real bike-sharing company operating in Chicago.
## About the company
Cyclistic launched its bike-share program in 2016, expanding to 5,824 GPS-tracked bikes across 692 Chicago stations. Riders can unlock and return bikes at any station.

Initially, Cyclistic focused on broad marketing and flexible pricing, offering single-ride, full-day, and annual memberships. Casual riders (single-ride and full-day users) are less profitable than annual members.

Marketing lead Moreno sees growth in converting casual riders into members, as they are already familiar with Cyclistic. To achieve this, her team will analyze historical bike trip data to understand rider behaviour and optimize digital marketing strategies.
## Business Task
Three questions will guide the future marketing program:
1. How do annual members and casual riders use Cyclistic bikes differently?
2. Why would casual riders buy Cyclistic annual memberships?
3. How can Cyclistic use digital media to influence casual riders to become members?

Moreno has assigned me the first question to answer: 
- How do annual members and casual riders use Cyclistic bikes differently?
## Key Stakeholders
### Lily Moreno: 
  The director of marketing and your manager. Moreno is responsible for the development of campaigns and initiatives to promote the bike-share program. These may include email, social media, and other channels. 
### Cyclistic marketing analytics team: 
  A team of data analysts who are responsible for collecting, analyzing, and reporting data that helps guide Cyclistic marketing strategy. I joined this team six months ago and have been busy learning about Cyclistic’s mission and business goals—as well as how I, as a junior data analyst, can help Cyclistic achieve them. 
### Cyclistic executive team: 
  The notoriously detail-oriented executive team will decide whether to approve the recommended marketing program.
## Data Source
The data used for this case study cover rider information from the first three months of 2019 and 2020. This data has been provided by Motivate International Inc. under [license](https://ride.divvybikes.com/data-license-agreement) and is originally stored in separate CVS files.
## Objective:
The primary objective is to analyze Cyclisitc bike-sharing data to understand user patterns, ride characteristics, and overall system performance. This information can assist Cyclistic in optimizing its services, improving user experience, and making informed business decisions.
## Analysis Steps
### Phase 1 – ASK
Three questions will guide the future marketing program:

1. How do annual members and casual riders use Cyclistic bikes differently?
2. Why would casual riders buy Cyclistic annual memberships?
3. How can Cyclistic use digital media to influence casual riders to become members?
1.1 Business Task
Analyze data to gain insights into how users use Cyclistic's bikes by membership type and to identify trends based on Cyclistic's marketing strategy.
### Phase 2 – PREPARE
#### Guiding Questions

Q1: Where is your data located?

A1: The data can be accessed through the link provided above.

Q2: How is the data organized?

A2: Various tools and programs are available for data editing, but I chose the R programming language for this project. Using R, I merged two different datasets into a single data frame, added relevant columns, and removed those that were not essential for our analysis.

Q3: Are there issues with bias or credibility in this data? Does your data ROCCC?

A3: Yes, the data appears to meet the ROCCC criteria. There are no noticeable issues with bias or credibility, as it comes directly from Cyclistic's own bike riders and is provided under license by Motivate International Inc. Furthermore, the data is reliable, original, comprehensive, current, and properly cited, fulfilling all the necessary requirements for ROCCC.


Q4: How did you verify the data’s integrity?

A4: To ensure the integrity of the data, it is crucial to identify any inconsistencies or errors. This includes checking for missing or incorrect values, spotting outliers, and comparing the data with other sources to confirm its accuracy. I performed this analysis using straightforward and efficient methods in R. As a result, I was able to verify that the data is consistent, identify and correct missing or incorrect data types, and prepare it for analysis.

Q5: How does it help you answer your question?

A5: Cyclistic trip data provides valuable insights into how annual members and casual cyclists use the bike-share program differently. Through analyzing usage patterns, I identified key differences between the two groups and gained a deeper understanding of how each group utilizes the bikes. This analysis has allowed me to develop effective answers to important marketing strategy questions.

Q6: Are there any problems with the data?

A6: I identified some deficiencies and incorrect data types in the data. Using R, I applied appropriate methods to resolve these issues and made the data suitable for analysis.
### Phase 3 – PROCESS
#### Guiding Questions:

Q1: What tools are you choosing and why?

A1: I used the R programming language to process the data and make it ready for analysis. Thanks to its simple syntax and fast usage, I both consolidated my knowledge and analyzed and organized the data. I visualized the data I edited in the R language in the Tableau program. Thus, I developed my skills in both programs.

Q2: Have you ensured your data’s integrity?

A2: Yes, I managed to ensure the integrity of the data. I added 12 months of data to a single data frame, making it ready for a year's analysis.

Q3: Have you documented your cleaning process so you can review and share those results?

A3: Yes, I have documented these operations and analysis process using R markdown.

### Phase 4 – Analyze
Q1: How should you organize your data to perform analysis on it?

A1: First, I grouped the trip data based on user types, hours, time zones, days of the week, months, and seasons, organizing the data accordingly. As shown in the R markdown document I shared during the process phase, I created time columns and classified the user trip data by time type. In addition to analyzing the average and total driving times for each user type, I also extracted important data points, such as start and end times, from the dataset and incorporated them into the analysis. This helped uncover valuable insights.

### Phase 5 - SHARE
Of course, after analyzing this data, visualizing it and sharing it with stakeholders is a very important step. For this reason, you can look at the visualizations we obtained from the Tableau program, where I created explanatory graphics that everyone can understand. You can click this link to check out my [Tableau account](https://public.tableau.com/app/profile/uzair.ahmad6960/vizzes).

### Phase 6 – ACT
Final Conclusion and Recommendation

My answers to the three questions that will guide the future marketing program are as follows, based on my analysis and visualizations:

#### Q1: How do annual members and casual riders use Cyclistic bikes differently?
A1: Key Findings:
1. User Type Comparison:
- On average, customers ride for a longer duration compared to subscribers.

- On average, subscribers tend to take shorter and more consistent rides.

2. Day-of-Week Analysis:
- On Fridays, Saturdays, and Sundays, customers tend to take longer rides on average.

- In general, subscribers tend to take shorter and more consistent rides throughout the week.

3. Ride Lengths:
- The length of the rides taken by customers varies greatly, with some being exceptionally long.

- The distribution of ride lengths among subscribers is more concentrated than among non-subscribers.

### Recommendations

#### 1. Customer Engagement Strategies
The analysis reveals that customers tend to take longer rides compared to subscribers. To boost customer engagement and loyalty, Cyclistic should implement targeted marketing strategies, such as promotional offers or rewards programs. These initiatives can encourage more frequent use and longer rides, increasing overall customer satisfaction.

#### 2. Operational Optimization on High-Traffic Days
Ride lengths vary across different days of the week, with some days showing higher activity. Cyclistic could improve its operational efficiency by optimizing bike distribution and station maintenance on days with higher user demand. This would enhance service efficiency and improve the customer experience during peak periods.

#### 3. Technology Enhancements for Subscriber Experience
With a significant number of subscribers taking shorter rides, Cyclistic can enhance their experience by prioritizing technology upgrades. Improvements to the mobile app or the introduction of additional features could encourage more frequent usage and improve overall satisfaction for subscribers.
