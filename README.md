# Video Game Sales Analysis

## Data Description

The dataset came from Kaggle.com and can be found [here](https://www.kaggle.com/gregorut/videogamesales)

The set includes a list of games with sales greater than 100k copies (roughly 16,500 rows) and was scraped by Greg Smith from [vgchartz](vgchartz.com)

- Rank - Ranking of overall sales
- Name - The games name
- Platform - Platform of the games release (i.e. PC,PS4, etc.)
- Year - Year of the game's release
- Genre - Genre of the game
- Publisher - Publisher of the game
- NA_Sales - Sales in North America (in millions)
- EU_Sales - Sales in Europe (in millions)
- JP_Sales - Sales in Japan (in millions)
- Other_Sales - Sales in the rest of the world (in millions)
- Global_Sales - Total worldwide sales.

## Project Objective

The objective as always is to have fun and hone my skills as an analyst but I specifically wanted to use some machine learning algorithms to estimate number of copies sold globally based on features like Publisher, Genre, and Console as I have yet to create a model with continuous output.

## Contents

So far I have mostly completed the exploratory phase which can be viewed at `VideoGamesSales EDA.ipynb`

Next up will be a short analysis to answer some questions I didn't cover in the EDA.

Finally I will include our model and make a few predictions like, "How many sales can we expect for a Sports Game released by EA in 2017"
