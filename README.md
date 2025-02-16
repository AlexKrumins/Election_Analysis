# Election_Analysis
This exercise is designed to challenge students' skills to analyze a large set of data using Python, VS Code, and Github.
Specific skills demonstrated include:
- Importing data from external .csv file
- Using for loops to track, store, & analyze information across numerous rows of data.
- Exporting anaylsis to external .txt file

## Overview of Election Audit
An election commission has requested an audit of its data covering:
- The Voter turnout for each county
- The Percentage of votes from each county out of the total count
- The County with the highest turnout

## Election-Audit Results

- Number of votes cast in this congressional election:
  - 369,711

- Number of votes and the percentage of total votes for each county in the precinct:
  - Jefferson: 38,855 (10.5%)
  - Denver: 306,055 (82.8%)
  - Arapahoe: 24,801 (6.7%)

- Which county had the largest number of votes?
  -  Denver


- Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.

  - Charles Casper Stockham:  85,213 (23.0%)
  - Diana DeGette:  272,892 (73.8%)
  - Raymon Anthony Doane:  11,606 (3.1%)


- Which candidate won the election, what was their vote count, and what was their percentage of the total votes?
  - Winner: Diana DeGette
  - Winning Vote Count: 272,892
  - Winning Percentage: 73.8%

## Election-Audit Summary
This script can be used to analyze data from future elections, regardless of the number of candidates or counties. It can easily scale up to cover ballots from millions of voters. As long as your data used for input contains the same ballot parameters ("County", and "Candidate"), the script requires almost no modification. IF you would like to include a breakdown of an additional parameter (e.g., "City") then the code should be updated to reflect & track the new data.
