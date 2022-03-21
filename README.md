# Election Analysis

## Project Overview
A Colorado Board of Election employee has given us the following tasks to complete the election audit of a recent local congressional election. 

1. Calculate the total number of votes. 
2. Get a complete list of candidates who received votes. 
3. Calculate the total number of votes each candidate received. 
4. Calculate the percentage of votes each candidate won. 
5. Determine the winner of the election based on popular vote.

## Resources
- Data Source: election_results.csv
- Software: Python 3.10.2, Visual Studio Code

## Summary
The analysis of the election saw that: 
- There were x votes cast in the election. 
- There candidates were: 
  - Charles Casper Stockhome
  - Diana DeGette
  - Raymon Anthony Doane
- The candidate results were: 
  - Charles Casper Stockhome received 23.0% of the votes and 85,213 number of votes
  - Diana DeGette received 73.8% of the votes and 272,892 number of votes
  - Raymon Anthony Doane recevied 3.1% of the votes and 11,606 number of votes
- The winner of the election was: 
  - Diana DeGette, who received 73.8% of the votes and 272,892 number of votes

## Challenge Overview

The audit of the Colorado Board of Elections was to determine the winner of the election of the local congressional election, however the major in which the code was created means that this code can be used in other future elections. Within this challenge, we expanded the original code to give us not only the winning candidate, but also provide insights on which counties drove the majority of votes.

## Challenge Summary

Since this code uses CSV files to run it's analysis, it is possible for this code to be updated and reused of future elections. There are a number of ways that the script could be modified to fit future elections, and below are a couple examples and things to keep in mind: 
 - The current CSV file only contained the ballot number, county and candidate name, however, in future elections additional information could be included in the file to gain futher insights into the election results. One example of this would be the way the individual voted, mail-in, in-person, ballot box, etc. If this information is included in the file, additional code can be added to the script to pull that information into the results txt file, in the same manner as we did for counties. 
 - When used for furture elections, we will need to review the header structure of the csv file, as if order of the headers change, then our code will need to adjust to accommodate this change. For example, our could references "row[2]" for the candidate name, but if future elections csv files have this information stored in the 4th row, then we'd need to update our code to ensure we reference "row[3]" for the candidate name variable.

