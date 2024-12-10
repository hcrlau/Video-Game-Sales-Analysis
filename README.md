# Video-Game-Sales-Analysis

This project focuses on analyzing Global and Regional Video Games sales from 1977 to 2020, measured by sales of copies in millions. The analysis examines sales trends across genre, console, publishers, regions, and release date to uncover customer behavior patterns. The objective is to extract actionable insights that can inform strategic decisions and drive the growth of video game sales on a global scale.


## The Dataset
This dataset contains a list of video games with sales greater than 100,000 copies.

Features include:
- title:	Game title
- console:	Console the game was released for
- genre:	Genre of the game
- publisher:	Publisher of the game
- critic_score:	Metacritic score (out of 10)
- total_sales:	Global sales of copies in millions
- na_sales:	North American sales of copies in millions
- jp_sales:	Japanese sales of copies in millions
- pal_sales:	European & African sales of copies in millions
- other_sales:	Rest of world sales of copies in millions
- release_date:	Date of the game's initial release


## Tasks Included

Data Import: Seamlessly imported raw sales data into Python

Data Cleaning: Ensured data accuracy and consistency through meticulous cleaning steps

Data Processing: Transformed raw data into actionable insights to uncover key sales trends

Data Analysis: Conducted thorough analysis to identify opportunities and strategic insights

Interactive Dashboard: Developed an intuitive and interactive dashboard using Tableau for real-time data visualization and strategic decision-making


## Visualization of regional and global video game sales
Tableau Interactive Dashboard: [Tableau](https://public.tableau.com/views/VideoG/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

1. Top Performing Games by Sales:
- Which games perform the best by sales?

2. Impact of Publishers on Video Game Sales and Ratings:
- Who are the leading publishers based on sales?
- Do publishers with high sales figures also tend to have higher game ratings, or is their sales success merely a reflection of their brand recognition?

3. Visualizing Genres and Consoles:
- Which consoles and genres are the most successful?
- How many games are released in these top-performing genres and consoles? 

4. Trends Over Time:
- How has the geographic distribution of video game sales changed over time?
- What genres have shown consistent growth or decline over the decades?


## Actionable Insights
**Top Performing Games by Sales**
- Insights: 
  - ***Global Leader***: "Grand Theft Auto V" with 64.29 million units sold.
  - ***Japan's Favorite***: "Hot Shots Golf" with 4.26 million copies.
  - ***Regional Hits***: "Grand Theft Auto V" in North America (26.19 million) and Europe & Africa (28.14 million).
  - ***Franchise Dominance***: The "Grand Theft Auto" and "Call of Duty" series lead global video game sales.

- Actions: 
  - ***Expand Existing Series***: Develop new installments within the existing series. Introduce fresh storylines, characters, and gameplay mechanics to keep fans engaged.
  - ***Spin-Offs and Side Stories***: Create spin-offs or side stories set in the same universe. These can explore different aspects of the game world or focus on specific characters.
  - ***Collaborate with Other Franchises***: Consider crossover events with other successful franchises. This can attract fans from both series.


**Category Insights: Impact of Publishers on Video Game Sales and Ratings**
- Insights:
  - ***Market Leaders***: Activision (722.8 million units) and Electronic Arts (644.1 million units).
  - ***Consistent Quality***: Top 10 publishers have critic scores ranging of 7 to 8.

- Actions:
  - ***Collaborate with Leading Publishers***: Explore partnerships, collaborations, or learn from industry leaders to strengthen market position with successful strategies.
  - ***Maintain Quality Consistency***:  Prioritize high-quality game development to ensure consistent critic scores and market performance.

**Category Insights: Genre sales across different regions**
- Insights:
  - ***Gloabl Dominance***: Sports games with 1.19 billion copies sold.
  - ***Top Region***: North America leads in sales.
  - ***Regional Preferences***:
     - North America (607.4 million units) and other regions favor sports games.
     - Japan prefers role-playing games (130.03 million units).
     - Europe & Africa lead with aciton games (342.5 million units).

- Actions:
  - ***Targeted Regional Marketing***: Tailor marketing strategies and game development to align with regional preferences.
  - ***Expand Genre Variety***: Continue investing in and diversifying game genres, with an emphasis on sports and action games to meet global demand.


**Category Insights: Console sales across different regions**

- Insights: 
  - ***Global Dominance***: PS2 with 1.03 billion copies sold.
  - ***Top Region***: North America leads in sales.
  - ***Regional Preferences***:
      - North America: Prefers X360 (528.4 million units).
      - Japan: Prefers PS (88.28 million units).
      - Europe & Africa: Prefers PS3 (301.8 million units).

- Actions: 
  - ***Leverage Console Preferences***: Develop exclusive content and optimize games for the most popular consoles in each region to increase market penetration.
  - ***Revitalize Classic Consoles***: Consider releasing classic or remastered versions of popular games for the PS2 to tap into its large user base.


**Temporal Trends**

- Insights:
  - ***Sales Trends***: Surge from 2006 to 2008, decline from 2008 to 2013, despite a peak in game launches in 2009.
  - ***Seasonal Sales***: Highest sales in Q4 each year.
  - ***Genre Shifts Over the Decade***:
      - Action games grew from 68.6 million (1990s) to 573.8 million (2000s).
      - Sports games grew from 132.7 million (1990s) to 619.6 million (2000s).
  - ***Popularity Shifts Over the Decade***: Action games remain popular; sports games gained in the 2000s; shooter games dominated in the 2010s.

- Actions: 
  - ***Strategic Release Timing***: Schedule major game releases and marketing campaigns for the fourth quarter to maximize sales during the holiday season.
  - ***Analyze Decline Factors***: Conduct a thorough analysis of the factors that contributed to the decline in video game sales and adjust strategies to mitigate similar risks in the future.
  - ***Optimize for Popular Genres Over Time***: Keep track of genre trends and invest in the development of genres that show growing popularity to stay ahead of market demands.


## Learning Objectives
1. Enhance data cleaning skills through thorough data preprocessing steps in Python.

2. Improve Tableau proficiency by creating interactive and insightful visualizations.


## Statistics

Data available from Maven Analytics: https://mavenanalytics.io/data-playground

Main Language: Python

Visualization: Python and Tableau

## Files Description
- `vgchartz-2024.csv` Original raw dataset
- `vgs.csv` Dataset after data cleaning
- `Video_Game_Sales_Analysis` A notebook detailing data cleaning and analysis

