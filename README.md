# Election-Analysis
Python Analysis

## Overview of Election Audit

In this Election audit we are helping Tom who is a Colorado Board of election employee. We have initially calculated the total number of votes cast, the total number of votes for each candidate, the percentage of votes for each candidate and the winner of the elections based on the popular vote. Also as per election comission's request we have calculated the voter turnout for each county,the percentage of votes from each county out of the total count, and the county with the highest turnout. We also have automated the process of calculations and displayed the results using python. This code can also be use to audit data for other congrestional districts, senotorial districts and local elections.

## Election-Audit Results
We have calculate the below election results by importing the data from the election_results csv file, making connections to the os by refering a path of the saved file,initilizing variables,lists and dictionaries as required for the calculations, using loops for iterating through the rows of data and collecting data with conditional statements, display data to the command line and store results in a txt file. 

- How many votes were cast in this congressional election? 
  369,711 votes
  
- Number of votes and the percentage of total votes for each county in the precinct.
  Jefferson: 10.5% (38,855)
  Denver: 82.8% (306,055)
  Arapahoe: 6.7% (24,801)
  
- Which county had the largest number of votes? 
  Denver
  
- Breakdown of the number of votes and the percentage of the total votes each candidate received.
  Charles Casper Stockham: 23.0% (85,213)
  Diana DeGette: 73.8% (272,892)
  Raymon Anthony Doane: 3.1% (11,606)
  
- Which candidate won the election, what was their vote count, and what was their percentage of the total votes?
  Diana DeGette: 73.8% (272,892)
  
## Election-Audit Summary
The script has been written with a lot of variabes and this makes its easy to work with any kind of data .With this code we can analyze any data' provided we have the same fields in the files.The csv file provied has three fields that are id,county and candidate name, with similar information we can calculate results for any county or district.

### Example of modifying the script
We can change the import depending on the type of file. Since the data can be available in any format, while importing the file the command will change depending on the file type we are importing. and we can do graphs to make the presentation more attractive.


