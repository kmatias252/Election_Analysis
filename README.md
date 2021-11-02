# Election_Analysis

## Overview of Election Audit 
Our objective is to assist a Colorado Board of Elections employee by completing an election audit of a recent local congressional election. Python will be used to complete the following tasks. 

1. Calculate the total number of votes cast.
2. Get a complete list of candidates who received votes. 
3. Calculate the total number of votes each candidate received.
4. Calculate the percentage of votes each candidate won.
5. Determine the winner of the election based on popular vote.
6. Get a complete list of the counties that received votes.
7. Calculate the total number of votes received in each county.
8. Calculate the percentage of votes casted in each candidate.
9. Determine the county with the largest voter turnout.

## Election-Audit Results
The analysis of the election show that: 
- There were 369,711 votes cast in the election.
- The breakdown of the number of votes and the percent of total votes for each county:
 	- Jefferson: 10.5% (38,855) votes 
 	- Denver: 82.8% (306,055) votes
 	- Arapahoe: 6.7% (24,801) votes
- Denver was the county with the largest voter turnout.
- The breakdown of the number of votes and the percent of total votes for each candidate:
 	- Charles Casper Stockham: 23.0% (85,213) votes 
	- Diana DeGette: 73.8% (272,892) votes
 	- Raymon Anthony Doane: 3.1% (11,606) votes
- Diana DeGette was the winner of the election. 
	- Winning Vote Count: 272,892 votes 
	- Winning Percentage: 73.8% of votes
	
![Screen Shot 2021-11-02 at 1 46 50 AM](https://user-images.githubusercontent.com/91925639/139793018-4f60e06d-a710-4229-9b09-de3a73540307.png)

## Election-Audit Summary
The script used to perform our election audit can be used for any election as long as the file path to the csv data is updated to pull the data from the correct source. Below is a screenshot of lines 9 and 11 which would need to be updated to get the results of another election.



## Resources
- Data Source: election_results.csv
- Software: Python 3.8.9, Visual Studio Code 1.61.0
