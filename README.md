# Election_Analysis1 By Kieran Persaud

## Overview of Election Audit
A Colorado Board of Elections employee has given me the following tasks to complete the election audit of a recent local congressional election.

1. Calculate the total number of votes cast.
2. Get a complete list of candidates who received votes.
3. Calculate the total number of votes each candidate received.
4. Calculate the percentage of votes each candidate won.
5. Determine the winner of the election based on popular vote.

Furthermore, as part of the Challenge, the election commission requested some additional data to complete the audit.
1. The voter turnout for each county
2. The percentage of votes from each county out of the total count
3. The county with the highest turnout

## Resources
- Data Source: election_results.csv
- Software: Python 3.7.6, Visual Studio Code

## Election Audit Results
The analysis of the election shows that:
- There were 369,711 votes cast in the election.
- The candidates were:
  - Charles Casper Stockham
  - Diana DeGette
  - Raymon Anthony Doane
- The candidate results were as follows;
  - Charles Casper Stockham received 23.0% of the vote and 85,213 votes.
  - Diana DeGette received 73.8% of the vote and 272,892 votes.
  - Raymond Anthony Doane received 3.1% of the vote and 11,606 votes.
- The winner of the election wasL
  - Diana DeGette, who received 73.8% of the vote and 272,892 votes.

For the challenge, the analysis shows that:
- Jefferson County had 38,885 votes, 10.5% of the total votes cast.
- Denver County had 306,055 votes, 82.8% of the total votes cast.
- Arapahoe County had 24,801 votes, 6.7% of the total votes cast.
- The county with the highest turnout was Denver County.

## Challenge Summary 
This script is robust and flexible enough to be used for any election, be it congressional or local. One instance in which the code can be modified is if there is data for several races (mayoral, city council, etc). Dictionaries of candidates can be added to the code to identify what candidates belong to which race, and cast that information to the csv file. If already present in the csv file, an empty list and dictionary method similar to the ones used can be implemented to automatically create dictionaries of the candidates for each race. Another way this code can be modified is to identify races that lead to run-off elections. Depending on the state/county law, if no candidate reaches a majority (greater than 50%), there will be a runoff elections. A variable can be added to the code called *cut_off_percent*, which can be referenced when modifying the code's if section and print out an f' string if the condition is met.
