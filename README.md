# Group 1 Capstone Project
Link to Presentation Slides: https://amedeloitte-my.sharepoint.com/personal/jklemm_deloitte_com/Documents/Capstone%20AI%20Academy.pptx?web=1

## Overview

Use EDA and statistics to generate insights around what type of creative, original content Computing Vision should produce.

## Business Understanding

Computing Vision is a company looking to make their way into creating original video content. We are tasked with providing insights into the best way to do so. However, given the amount of competition in the space, Computing Vision wants to identify the optimal entry point for which films they should create.

#### Key Business Questions

- How can we maximize the profit of the films while minimizing the cost of entry?
- What kinds of films are currently performing the best?
- What are the main trends among top performing films?

## Data Understanding and Analysis

### Source of data

Our data is gathered from 3 different sources:
1. IMDB
2. Box Office Mojo
3. The Numbers

### Description of data

Each of these sources provided us with unqiue types of data. The IMDB database contains a large amount of data about movies from their website. This has all kinds of tables such as movie titles, actors, directors, ratings, etc. 

The Box Office Mojo dataset contains data about how well movies perform in terms of gross domestic and gross foreign.

The Numbers dataset is very similar to the Box Office Mojo dataset but the Numbers dataset included the production budget, while the Box Office Mojo did not. We decided to merge these two datasets based on their similarity, and provided us with more data to utilize when it came to making a more accurate recommendation.

### Three visualizations

Our visualizations include:
1. A histogram comparing Non-Original to Original Movies
2. A scatter plot showing the point in which the Average Gross Income is achieved based on the Production's Budget
3. A histogram comparing Average Gross Domestic income based on movie Genres

## Statistical Communication

### Results of statistical inference

Chart 1:
In descending order of the top 50 domestic gross income movies, over 40 movies were based on Non-Original ideas (movies based on books, movie series, or remake) and less than 10 movies were based on original ideas.

Chart 2:
With 95% confidence, we can conclude that a production budget of $161,500,000 will help Computing Vision earn at least $99,478,358.79 in gross domestic income.

Chart 3:
When comparing different movie genres based on their domestic gross income, the Action, Adventure, and Animation genre generated the most, at $600,000,000

### Interpretation of these results in the context of the problem

With our recommendations, Computing Vision will be able to have and optimal entry point into the film industry. They can use Non-Original ideas, and base their movies off of books, a movie series, or remake an existing film. They can also use a budget of $161,500,000 to help earn at least $99,478,358.79 in gross domestic income, being the average. Lastly, they can focus on creating movies within the the Action, Adventure, and Animation genre, to help optimize their domestic gross income.

## Conclusion

We recommend creating Action, Adventure, and Animation movies based on Non-Original ideas, and utilize a production budget of $161,500,000 to earn at least $99,478,358.79 in gross domestic income.