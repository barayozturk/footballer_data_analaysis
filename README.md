# ⚽ Footballers Data Analysis 👨‍💻

This project aims to analyze the statistics of footballers to gather various insights about their performance.

## 📋 Requirements

Make sure to have the following libraries installed before running the code:

- pandas
- numpy
- matplotlib
- seaborn

You can install these libraries using pip:

pip install pandas numpy matplotlib seaborn


## 🚀 Getting Started

1. Clone the repository to your local machine or download the "FootballersData.csv" file.

2. Ensure you have Python and the required libraries installed.

3. Open Jupyter Notebook (or any other Python IDE) and run the code step by step.

## 📁 Data Set

The "FootballersData.csv" dataset contains information about footballers, including name, club, nationality, position, age, matches played, goals scored, assists, yellow and red cards, etc.

## 📝 Code Description

1. Importing libraries: First, we import the necessary libraries, such as pandas, numpy, matplotlib, and seaborn. We also use `%matplotlib inline` to display the graphs directly inline.

2. Loading and inspecting data: We load the dataset using `pd.read_csv()` and then inspect basic information with `df.info()` and summary statistics with `df.describe()`.

3. Checking for missing data: We check if there are any missing values in the dataset using `df.isna().sum()`.

4. Data Transformation: We create two new columns named "MinsPerMatch" and "GoalsPerMatch". These columns are used to calculate the average minutes and goals per match for each player.

5. Data Analysis and Visualization:
   - Total Goals: We calculate and display the total number of goals scored by all players.
   - Total Penalty Goals: We calculate and display the total number of penalty goals scored by all players.
   - Total Penalty Attempts: We calculate and display the total number of penalty attempts made by all players.
   - Penalty Missed vs. Scored: We create a pie chart to visualize the ratio of penalties missed to penalties scored.
   - Different Positions: We display the players' different positions.
   - Forward Players: We filter and display players who play as forwards (position: "FW").
   - Players from Different Nations: We calculate and display the count of players from different nationalities.
   - Nations with Most Players: We create a bar chart to visualize the countries with the most players.
   - Clubs with Most and Least Players: We create bar charts to visualize clubs with the most and least number of players.
   - Players in Different Age Groups: We categorize players into different age groups and create a pie chart to show their distribution.
   - Average Age of Players in Each Club: We create box plots to show the average age of players in each club.
   - Top Players with Most Assists and Goals: We list the top 10 players with the most assists and goals.
   - Goals with and without Assists: We create a pie chart to visualize the ratio of goals with and without assists.
   - Players with Most Yellow Cards: We create a bar chart to show the players with the most yellow cards.

## 🏁 Conclusion

This analysis provides valuable insights into various aspects of players' performances. Visualizations help understand performance in terms of goals, assists, yellow cards, and age distribution. It provides information about the distribution of players across different clubs and nations.

You can continue to explore the code and customize the analysis according to your own requirements.
