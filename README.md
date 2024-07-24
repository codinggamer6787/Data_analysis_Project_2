FIFA EDA Project

This project performs an exploratory data analysis (EDA) on the FIFA dataset, visualizing various aspects of the data to gain insights.


Data Description

The dataset contains comprehensive information about FIFA players, capturing a wide range of attributes that provide insights into their demographics, skills, and professional affiliations. The key columns in the dataset include:

Name: The player's full name.
Age: The age of the player.
Nationality: The country the player represents.
Club: The football club the player is affiliated with.
Overall: The overall rating of the player, which is a measure of their general performance and skills.
Preferred Foot: The player's dominant foot (e.g., left or right).
Skill Moves: A rating that reflects the player's ability to perform skill moves, rated from 1 to 5.
Wage: The weekly wage of the player, which includes values in different formats (e.g., €K for thousands and €M for millions).
Position: The primary position where the player typically plays (e.g., forward, midfielder, defender, goalkeeper).
Height: The player's height.
Weight: The player's weight.
Work Rate: The player's work rate, both offensive and defensive.
Body Type: The physical build of the player (e.g., lean, stocky).
Joined: The date when the player joined their current club.
Contract Valid Until: The year until which the player's contract with their current club is valid.
Nationality: The player's country of origin.
ID: A unique identifier for each player in the dataset.
This dataset offers a rich source of information that can be used to perform various types of analyses, such as understanding the distribution of players' attributes, comparing player performance across different clubs and nationalities, and examining the financial aspects of player wages.

In this project, the dataset is leveraged to perform an exploratory data analysis (EDA) focusing on key areas such as preferred foot distribution, skill moves, age distribution across top countries and clubs, and wage normalization. This analysis helps in uncovering patterns and insights that are not immediately apparent from raw data alone.



Exploratory Data Analysis ,The following analyses were performed:

Preferred Foot Distribution: A count plot showing the distribution of players' preferred foot.
Skill Moves by Preferred Foot: A count plot showing the distribution of skill moves segregated by players' preferred foot.
Top 10 Nationalities: Identification of the top 10 nationalities among the players.
Age Distribution in Top Countries: A box plot showing the age distribution in the top 10 countries.
Age Distribution in Famous Clubs: A box plot showing the age distribution in famous clubs.
Wage Normalization: Conversion of wage values to a uniform format for better analysis.


In this project, I utilized the following tools and techniques:

Data Cleaning and Preparation: I handled missing values, normalized data (such as converting wages to a uniform format), and filtered data based on specific criteria.
Data Visualization: I used visualization libraries like Matplotlib and Seaborn to create insightful and visually appealing plots. This included creating count plots, box plots, and annotating plots with additional information.
Exploratory Data Analysis (EDA): I employed a structured approach to performing EDA, which involved identifying key attributes of the dataset, uncovering patterns, and generating visualizations to better understand the data.
Python Libraries for Data Analysis: I utilized essential data analysis libraries such as Pandas, NumPy, and missingno. These tools were crucial for efficiently manipulating and analyzing the dataset.
Project Documentation: I emphasized the importance of documenting my work for better reproducibility and sharing insights with others. This included writing a comprehensive README file and providing detailed explanations of my findings and methods.
Overall, these tools and techniques were instrumental in successfully completing this project and improving my data analysis and visualization skills.

Link to Dataset : https://www.kaggle.com/code/mohdshahnawazaadil/data-visualization-eda-fifa19-dataset/input


