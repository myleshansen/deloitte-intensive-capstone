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
2. A bar chart comparing average gross domestic income based on movie genres
3. A bar chart showing the point in which the average gross domestic income for action movies is achieved based on the production budget 

## Statistical Communication

### Results of statistical inference

Chart 1:
In descending order of the top 50 domestic gross income movies, over 40 movies were based on non-original ideas (movies based on books or comic books, continuing a movie series, or remaking a classic film) and less than 10 movies were based on original ideas. This implies that movie-goers enjoy films with characters they are already familiar with, and non-original films seem to be big box office hits.

Chart 2:
When comparing different movie genres based on their domestic gross income, the action, adventure, and animation genre generated the most income, at $600,000,000, with other genre mixes containing action following behind. Therefore, we conclude that action movies seem to be the most popular and profitable. 

Chart 3:
With 95% confidence, we can conclude that a production budget of $161.5 million minimum will help Computing Vision earn at least $99.4 million in gross domestic income. If Computing Vision was to earn the average amount of gross domestic income with their first action movie ($99.4 million dollars), they would need to spend at least $161.5 million. This conclusion was drawn from conducting a statistical analysis using a significance level of 5%. We know that the data used to obtain this insight might be skewed because it takes deep-pocket companies like Disney into account. It is possible that one could make a movie for less than this amount and potentially earn the target gross domestic income, but we have high confidence that a higher production budget will allow Computing Vision to be closer to reaching their goals. 


### Interpretation of these results in the context of the business problem

With our recommendations, Computing Vision will be able to have an optimal entry point into the film industry. They can use non-original ideas, and base their movies off of a book, another movie or television series, or remake an existing film. They should plan to use a budget of $161,500,000 to help earn at least $99,478,358.79 in gross domestic income (the average gross domestic income for action movies). Lastly, they should focus on creating movies within the the action genre (specifically action, adventure, and animation), to help optimize their domestic gross income and create movie hits the world will enjoy for years to come.

## Conclusion

We recommend that Computing Vision launch their movie library through the creation of a movie in the action, adventure, and animation genre, based on a non-original idea, and utilize a production budget of $161.5 million dollars.
