# Group 1 Capstone Project
Link to Presentation Slides: https://amedeloitte-my.sharepoint.com/personal/jklemm_deloitte_com/Documents/Capstone%20AI%20Academy.pptx?web=1

## Overview

Use exploratory data analysis (EDA) and statistics to derive understanding around what type of creative, original content Computing Vision should produce in their new film studio. Then, provide reasonable, specific recommendations. 

## Business Understanding

Computing Vision is a new media company looking to make their way into creating original video content and wanted insights into the best way to do so. However, given the amount of competition in the space, Computing Vision needs to wisely employ their available resources and wants to identify the optimal entry point for what types of films they should create first.

#### Key Business Questions

- How can we maximize the profit of the films while minimizing the cost of entry?
- What kinds of films are currently performing the best?
- What are the main trends among top performing films?

## Data Understanding and Analysis

### Source of data

Our data is gathered from 3 different sources, each providing us with unique types of data:
1. IMDB - online database of information and details related to films.
2. Box Office Mojo - online serive that tracks international and domestic box office reciepts. 
3. "The Numbers" (provided by The Movie Database, TMDB) - onine movie and television user-created database.

### Description of data

The IMDB database contains a large amount of data about movies from their website. This has many types of tables with important variables such as movie titles, genres, actors, directors, ratings, etc. 

The Box Office Mojo* dataset contains data about how well movies perform in terms of gross domestic income and gross foreign income.

The Numbers* dataset is very similar to the Box Office Mojo dataset and includes data around the production budget of a film and also named the movie stuido. 

*We decided to merge these two datasets based on their similarity, which provided us with more data to utilize when it came to making a more accurate recommendation.

### Three visualizations

Our visualizations include:
1. A bar chart comparing non-original to original movies

![image](https://github.com/myleshansen/deloitte-intensive-capstone/assets/140458440/5a58ca78-0709-45d9-bc25-6639fe604c57)

In descending order of the top 50 domestic gross income movies, over 40 movies were based on non-original ideas (movies based on books or comic books, continuing a movie series, or remaking a classic film) and less than 10 movies were based on original ideas. This implies that movie-goers enjoy films with characters they are already familiar with, and non-original films seem to be big box office hits.

3. A bar chart comparing average gross domestic income based on movie genres

![image](https://github.com/myleshansen/deloitte-intensive-capstone/assets/140458440/6d3d6c45-8515-4da7-868c-7160f0113411)

When comparing different movie genres based on their domestic gross income, the action, adventure, and animation genre generated the most income, at $600 million, with other genre mixes containing action following behind. Therefore, we conclude that action movies seem to be the most popular and profitable. 

5. A bar chart showing the point in which the average gross domestic income for action movies is achieved based on the production budget

![image](https://github.com/myleshansen/deloitte-intensive-capstone/assets/140458440/9c490837-66db-4cf6-8a0a-1d860b7f98a6)

We came up with a scenario challenging Computing Vision to earn the average amount of gross domestic income with their first action movie. Though an awesome and interesting story is most important to movie fans, the production budget seemed to be a good indicator of income success and so we chose to use this variable to help Computing Vision reach their goal of earning the average amount of gross domestic income for action movies, which is about $99.4 million.
   

## Statistical Communication

### Results of data analysis and statistical inference

**Ho: A production budget of $161,500,000 is not enough to make the mean amount of gross income. (mu <= x-bar)**

**Ha: A production budget of $161,500,000 is enough to make the mean amount of gross income. (mu > x-bar)**

With 95% confidence, we can conclude that a production budget of $161.5 million minimum will help Computing Vision earn at least $99.4 million in gross domestic income. If Computing Vision was to earn the average amount of gross domestic income with their first action movie ($99.4 million dollars), they would need to spend at least $161.5 million. This conclusion was drawn from conducting a statistical analysis using a significance level of 5%. 

*We know that the data used to obtain this insight might be skewed because it takes larger, established companies like Disney and Warner Brothers Studios into account. It is possible that one could make a movie for less than this amount and potentially earn the target gross domestic income, but we have high confidence that a higher production budget will allow Computing Vision to be closer to reaching their goals. 


### Interpretation of these results in the context of the business problem

With our recommendations, Computing Vision will be able to have an optimal entry point into the film industry. They can use non-original ideas, and base their movies off of a book, another movie or television series, or remake an existing film. They should plan to use a budget of $161,500,000 to help earn at least $99,478,358.79 in gross domestic income (the average gross domestic income for action movies). Lastly, they should focus on creating movies within the the action genre (specifically action, adventure, and animation), to help optimize their domestic gross income and create movie hits the world will enjoy for years to come.

### Navigating the Repo Notebook

Note: before attempting to run the notebook, please unzip the im.db.zip file in the data folder.

**1. Import Packages: loading in helpful packages for use in the analysis.**
   
**2. Data Exploration and Cleaning: load in data for analysis one by one (im.db, The Numbers, Box Office Mojo), cleaning necessary variables, and exploring the data available.**
   
2.1 IMDB Data: querying to understand interesting and important variables. Visualizing variables like runtime in minutes, top movies by votes, and top genres by rating.

2.2 The Numbers, AKA Budgets data: learning more about how things like production budget and domestic gross income interact with one another and seeing the top earning movie titles.

2.4 Box Office Mojo AKA BOM data: undertsanding the relationships between production budget and studios and seeing top earning movie titles.

2.5 Filter and Join Budgets and BOM data, then Join with IMDB data: because of many similarities in the two datasets, left merge using movie title. Next, combine with the IMDB database to gain a deeper understanding around movie income, budget, and genre.

  2.5.1: Analyzing gross domestic income by genre to see which genre earns the most at the box office.
   
  2.5.2: Understanding the average rating by genre to see what genre is most popular based upon rating.
   
  2.5.3: Learning how much each genre spends in their production budget.
   
  2.5.4: Counting how many of the top 50 movie titles were based on original ideas versus non-original ideas.
   
**3. Statistical analysis: using the mean for gross domestic income for action movies, how much should Computing Vision spend on a production budget in order to reach this income goal?**

3.1: filtering movies based upon earning greater than or equal to the mean gross domestic income for action movies

3.2: Conducting the statistical analysis using a z-score. Assessing three different production budgets ($25 million, $50 million, and $161.5 million) to learn which ones give enough confidence to reject the null hypothesis.

3.3: Visualizing that higher production budgets provide more confidence that the gross domestic income goal will be reached.
   
## Conclusion

We recommend that Computing Vision launch their movie library through the creation of a movie in the action, adventure, and animation genre, based on a non-original idea, and utilize a production budget of $161.5 million dollars.
