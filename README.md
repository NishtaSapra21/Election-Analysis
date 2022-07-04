# Election-Analysis

## Purpose of Election Audit 

Assisting Colorado Election Commission Board employee by developing  Python script to audit election data to read CSV file and  calculate the votes turnout for each county,
the percentage of votes from each county, county with highest turnout;  in addition to total number of votes cast,  the number of votes that each candidate received, 
the percentage of votes for each candidate, winner of the election with number of votes and percentage of votes. 

## Election Audit Results

**-Total Votes**

The total number of votes cast in this congressional election were 369,711.

![Total Votes](/Election-Analysis/Resources/ElectionResults_TotalVotes.png?raw=true "Total Votes")

**-County View**

![County View](/Election-Analysis/Resources/ElectionResults_CountyView.png?raw=true "County View")

Jefferson county have cast 38,855 votes, 10.5% of total votes.
Denver county have cast 306,055 votes, 82.8% of total votes.
Arapahoe county have cast 24,801 votes, 6.7% of total votes.

**-Largest County Turnout**

![Largest County](/Election-Analysis/Resources/ElectionResults_LargestCounty.png?raw=true "Largest County")

Denver county have cast the largest number of votes, 306,055.

**-Candidate View**

![Candidate View](/Election-Analysis/Resources/ElectionResults_CandidateView.png?raw=true "Candidate View")

There are three candidates: Charles Casper Stockham, Diana DeGette, Raymon Anthony Doane.  
Charles Casper Stockham got 85,213 votes which is 23.0% of total votes
Diana DeGette got 272,892 votes which is 73.8% of total votes.
Raymon Anthony Doane got 11,606 votes which is 3.1% of total votes.

**-Winner**

![Winner](/Election-Analysis/Resources/ElectionResults_Winner.png?raw=true "Winner")

From the result analysis, it is clear that the winner is Diana DeGette with highest number of votes 272,892. She won the election by getting 73.8% of total votes cast. 

## Election-Audit Summary

Pyhton script “PyPoll” is easy to use, powerful and versatile. This script calculates and saves report in text file of total number of votes; candidates, their total votes
and percentage of votes; counties, their total number of votes and percentage of votes; winning candidate and his/her vote statistics.  This script is particularly has been developed 
for Colorado Election Commission to audit election data; but it is useful for any election with its powerful loops and decision making code, flawless reading of data files  (.csv files) , 
simple writing operations to any file, versatile data types like dictionary, list, tuples and rich library of mathematical and other functions. 

This file can be used for any local election like District School Board Election. In election dataset, “County” can be easily replaced by “Zones”. Same calculations can be applied
to make report of total votes, candidates, candidate's votes and winner of the election. Instead of text file, election analysis can be stored in PDF files for easy Internet upload to view 
election analysis. 
 
Also, updated script with new code lines can be used with large election data like “National  Election”. With little more or definitely more coding we can get simple analysis of election like total 
states and their candidates, candidates and their votes, their parties; parties , their reprentatives, votes etc. Here nested dictionary concept of Python can be useful to get desire outputs. 

This script is also useful for election audits of non government bodies like HOAs, local organizations etc. with few additions and modifications to code. 