# Game Sales Optimization Analysis

## Table of Contents
- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Recommendations](#recommendations)

### Project Overview
The project aims to identify the optimal year for game sales by analyzing both the quantity of games sold and user satisfaction. Additionally, it seeks to determine the most successful game released during that year. Furthermore, the project intends to explore the correlation between the number of games developed by a particular developer and the corresponding sales figures of those games.

### Data Sources
Kaggle: https://www.kaggle.com/datasets/holmjason2/videogamedata

### Tools
Python - Data preprocessing, exploratory data analysis, data analysis, and data visualization

### Data preprocessing
Remove duplicate entries based on the game name.

### Exploratory Data Analysis
Some question about EDA:
1. Checking if there are any pieces of information missing
2. Calculating the mean user score.
3. Determining the average total shipments.

### Data Analysis

1. Which years have more than 3 games?
2. Which years belong to the top 25% based on ratings?
3. Which years are in the top 25% based on sales?

### Data Analysis
I'd like use Python to know:
1. Find the years with over 3 games.
2. Determine the top 25% of years based on ratings.
3. Identify the top 25% of years based on sales.
4. Investigate if there's a correlation between the number of games produced by a developer and the units sold.

### Data Visualization
![developer_game_sales](https://github.com/fernandasubekti/Game_Sales/assets/116712020/b5b78711-1e6a-4b58-875c-7d1f2e943d7a)

### Results
1. Games typically get an average score of 7.15 out of 10.
2. On average, games sell around 0.62 million copies units.
3. Looking at the visualized data, it seems that the number of games a developer creates doesn't have a clear connection with the revenue they generate.
4. The highest game sales occurred in 2008, reaching a total of 516 million units.
5. The year 2010 was a standout for games because a lot of games did really well in terms of both sales and ratings. Minecraft, which was released that year, was a big part of this success.

### Recommendations
- To be considered very good, your game should have a minimum rating of 7.15.
- Achieving a minimum of 620k copies in sales is necessary for a game to be classified as very good.
- The number of games a developer creates doesn't show any correlation with revenue. Therefore, focusing on creating really good games, marketing them well, and considering other important aspects, rather than just making a lot of games to make more money.
