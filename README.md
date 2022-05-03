# Election_Analysis

## Overview of Election Audit: 
### This Election Analysis Python file will analyze a CSV file with Ballot ID, County, and Candidate and print out a report which consisits of "County Votes" with how many percentage and total vote came from each county and determines which county had the largest vote turn out, how many percentage and votes each candidate received, and declare the Name/Vote Count/Percentage of the winner in this election.  
##
## Election-Audit Results: 
### •How many votes were cast in this congressional election?
#### Total Votes: 369,711
### •Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.
#### County Votes:
#### Jefferson: 10.5% (38,855)
#### Denver: 82.8% (306,055)
#### Arapahoe: 6.7% (24,801)
### •Which county had the largest number of votes?
#### Largest County Turnout: Denver
### •Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.
#### Charles Casper Stockham: 23.0% (85,213)
#### Diana DeGette: 73.8% (272,892)
#### Raymon Anthony Doane: 3.1% (11,606)
### •Which candidate won the election, what was their vote count, and what was their percentage of the total votes?
#### Winner: Diana DeGette
#### Winning Vote Count: 272,892
#### Winning Percentage: 73.8%
##
## Election-Audit Summary: In a summary statement, provide a business proposal to the election commission on how this script can be used—with some modifications—for any election. Give at least two examples of how this script can be modified to be used for other elections.
### This script can be used to tally the vote result by analyzing a source CSV files with 3 fields, "Ballot ID", "County", and "Candidate".  
#### Modification 1: The PyPoll Challenge background says there are 3 possilbe sources Mail-in Ballots, Punch Cards, ad DRE.  Three source CSV files can be used by For loop, as long as the CSV format with 3 specific fields is intact.  
#### Modification 2: More fields in CSV can be added for analysis, for example, voter age range, voter gender, etc.  Anotehr set of list and dictionary will need to created then loops neeeded be added to add the counts, in a similar fashion to the existing voter counts in this script.
