# Data Analytics Project: Navigating Numbers

## Table Contents

- [Project Overview](#Project-Overview)
- [Objective](#Objective)
- [About Dataset](#About-Dataset)
- [Tools Used](#Tools-Used)
- [Process](#Process)
- [Data Analysis](#Data-Analysis)
- [Suggestions, Actions and Solutions](#Suggestions,-Actions-and-Solutions)

## Project Overview

In collaboration with Social Buzz, our data analytics team addresses challenges in resource allocation, unstructured data, and technology, preparing the platform for a successful IPO.

## Objective

They are expecting the following:
- An audit of their big data practice.
- Recommendations for a successful IPO.
- An analysis of their content categories that highlights:
  1. the top 5 categories with the largest aggregate popularity.
  2. number of unique categories.
  3. Number of reactions for top category.
  4. Month with Highest Post.

## About Dataset

This .csv dataset comprises three tables - Content, Reaction, and ReactionTypes. It contains unique IDs, user information, content and reaction details, sentiment analysis, and popularity scores for Social Buzz's content and user interactions.


![Screenshot 2024-02-11 215258](https://github.com/TripathiAmbrish/Data-Analysis-Project-at-Accenture/assets/139352292/1cfb6a9a-9a18-4cf2-aaa6-589464e24654)

## Tools Used

- Excel: Data Cleaning and Manipulating
- Power BI: Data Modeling and Data Visualization
- MS Powerpoint: Creating presentation
- Loom: Recording Presentation

## Process

### Business Understanding

- Collaborated with the team and stakeholders.
- Gone through the company's history.
- Gathered information on Social Buzz's Problems and the cause of the problem.
- Collected the info on requirements.

### Data Collection, Cleaning/Preparation

- Used the dataset to understand and collect the data tables to be used as per requiremnts.
- Used the csv file and imported to excel for:
  1. Data cleaning and inspection
  2. Removed unecessary values, empty values and unwanted columns
  3. Formating and manipulating incorrect values

### Data Modeling

- Imported the cleaned data into Power BI.
- Before modeling:
  1. Added required columns
  2. inserted some columns from dimension tables into factable (Reactions Table)
     in Power Query
- Created Data Model using keys in Model tab.

  ![Screenshot 2024-02-11 232350](https://github.com/TripathiAmbrish/Data-Analysis-Project-at-Accenture/assets/139352292/8f309676-3b4a-46ef-9faf-1ac634f21ca6)

### EDA and Data Visualzation

- Created Visuals using KPIs, Charts and Filters.
- EDA involved exlporing the Content and reactions data to answer the questions.
- Also performed sentiment analysis.

## Data Anlaysis

- Bar Chart: Top 5 Categories
Utilized to spotlight the platform's content powerhouses—Animals, Science, Healthy Eating, Technology, and Food. Allocating resources to these top-performing categories enhances user engagement and platform vitality.

- KPIs: Number of Reactions and Unique Categories
Key Performance Indicators tracking overall user engagement and content diversity. Guides and community feedback platforms amplify user understanding, fostering a vibrant and varied user experience.

- Line Chart: Total Posts By Month
Illustrates posting trends, essential for strategic planning. Collaboration with influencers and targeted campaigns during slower months maintains consistent user interaction and platform visibility.

- Pie Chart: Sentiment Analysis – Reactions By Sentiment Type
Provides a snapshot of user sentiment. Investing in advanced sentiment analysis and content moderation systems improves sentiment accuracy, ensuring a positive user experience.

- Horizontal Bar Chart: Content Type Distribution – Posts By Content Type
Empowers content creators with insights into their content's performance. The development of an analytics dashboard guides creators, enhancing content quality and engagement.

- Line Chart: Total Reactions By Month
Reveals monthly engagement patterns. Utilizing push notifications strategically during specific months promotes increased user participation and community activity.

## Insights

- Top 5 Categories:
Animals
ScienceHealthy Eating
Technology
Food

- There are total 16 Unique categories

- There 1895 reactions for Animal which is the most popular category.

- January was the month with most posts. 781 posts were posted.

- Sentiment analysis:
56.19% Positive Reactions on Posts.
31.31% and 12.5% were Negative and Neutral.

- January, August and December were the months with highest engament.


## Suggestions, Actions and Solutions

#### Suggestions:

- Conduct audience surveys to identify subtopics in top categories.
- Develop guides to educate users on content categories.
- Collaborate with influencers for platform visibility.
- Invest in advanced sentiment analysis algorithms.
- Implement an analytics dashboard for content creators.

#### Actions:

- Push subtopics in top categories for increased engagement.
- Establish community feedback platforms for category suggestions.
- Run targeted marketing campaigns for visibility.
- Collaborate with data scientists to improve sentiment analysis.
- Provide insights to content creators through an analytics dashboard.

### Solutions:

- Create in-app notifications for lesser-known categories.
- Implement user-generated category suggestions with a voting mechanism.
- Design campaigns inspiring users to create content with specific themes.
- Collaborate with data scientists for sentiment accuracy.
- Flag or review content with consistently negative sentiments.

## Limitations

I have removed empty rows, user Id column and url column as they would have affected the esults from analysis and some are removed as they weren't required.
