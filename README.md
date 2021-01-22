# NYT Cooking: Predicting the Number of Recipe Ratings


## Description
#### The goal of the project is to used data scraped from individual NYT recipes to accurately predict the number of ratings a recipe will receive



## Features and Target Variables
#### Features Include Number of Preparation Steps, Aggregate Rating Value, Preparation Time (minutes), Number of Ingredients, Estimated Publish Date, Keyword Tags, and Author.

#### The target variable is Number of Ratings



## Data Used
#### NYT Cooking https://cooking.nytimes.com/
#### Wayback Machine https://archive.org/ - I wasn't able to get publish date from NYT Cooking, so I used the earliest Wayback Machine snapshot as the estimate



## Tools Used
#### Web Scraping: BeautifulSoup, Selenium, Extruct
#### Linear Regression: statsmodels, sklearn



## Possible Impact
#### This project could help recipe authors and NYT Cooking staff better understand the factors of a recipe that encourage people to rate recipes. Recipe ratings provide useful feedback, and help signal when subscribers are particularly interested in a recipe
