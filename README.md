# Pandas-Dataframe-Analysis


## Leaderboard for Statements and Reasons
This project includes two scripts to create leaderboards based on the total number of statements and reasons for a given set of data. The scripts were created using Python and the Pandas library.

**Requirements**

Python 3.7 or higher

Pandas 1.3.3 or higher

A CSV file containing the data to be analyzed

__Script 1: Leaderboard for Statements and Reasons__

This script reads a CSV file containing data for each participant, including their name, UID, number of statements, and number of reasons. It then calculates the rank of each participant based on their number of statements and reasons, and prints a leaderboard with the following information:

Rank

Name

UID

Number of Statements

Number of Reasons

The leaderboard is sorted in descending order based on the number of statements and reasons.

__Script 2: Team Wise Leaderboard__

This script reads a CSV file containing data for each participant, including their team name, number of statements, and number of reasons. It then calculates the average number of statements and reasons for each team, calculates the sum of the average number of statements and reasons, and prints a team-wise leaderboard with the following information:

_Rank

_Average Statements_

_Average Reasons_

_Sum of Average Statements and Reasons_

The leaderboard is sorted in descending order based on the sum of the average number of statements and reasons.

Usage
To use these scripts, follow these steps:

Install the required dependencies by running the following command: pip install pandas

Save the CSV file containing the data to be analyzed in the same directory as the scripts.

Open the terminal or command prompt and navigate to the directory containing the scripts.

To run Script 1, run the following command: python script1.py

To run Script 2, run the following command: python script2.py
The leaderboard will be printed to the console.

**License**

This project is licensed under the MIT License. Feel free to use and modify these scripts as needed.
