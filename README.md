# Written Analysis of the Election Results

## Overview of Election Audit

The purpose of this project was to determine if python could be used to verify election results from tableted data provided by the U.S. Congressional Precinct in Colorado.  

Background
Voters can cast their votes using three main voting methods: Punch Cards, Mail-In Ballots and Direct Recording Electronics. The current process requires each voting method to tally and record the data in tabulated form. The tableted data is then sent to the central office to summarize and validate election results. 

An employee from the Colorado Election Committee supplied the tableted data for us to validate. Our goal was to summaries election results and determine the congressional winner using python.  The ultimate project goal is automating the audit of election results using a modified version of our code in future elections. 

## Election-Audit Results
We were given a cvs file named “election_results” which contained all of the election data by county.  For your reference, this file can be found in the “Resource” folder. Using the cvs file “election_results” and python, we were able to perform calculations on the election data and write summaries back to a text file named “election_analysis”.  The text file “election_analysis” can be found in the folder “analysis”.  

Using the given cvs file and python, we were able to determine the following election results: 
* Total Votes Casted: 369,711
* County breakdown of the percentages of total votes and number of total votes:
	1. Jefferson: 10.5% and 38,855 votes
	2. Denver: 82.8% and 306,055 votes
	3. Arapahoe: 6.7% and 24,801 votes
* County with the largest number of votes: Denver
* Candidate breakdown of the percentages of total votes and number of total votes:
	1. Charles Casper Stockham: 23.0% and 85,213 votes
	2. Diana DeGette: 73.8% and 272,892 votes
	3. Raymon Anthony Doane: 3.1% and 11,606 votes			
* Winning Candidate vote count and percentage of the total votes
	1. Diana DeGette: 73.8% and 272,892 votes

Please find below a snapshot of the election results written to the text file using python: 
![](Resources/###.png)




## Election-Audit Summary
The python code we developed was able to verify the election results from the Colorado Election Committee.  With some modification the Colorado Election Committee can utilize this code for future elections.   

Here are two examples of how the committee can use this script can be modified for other elections:

*
