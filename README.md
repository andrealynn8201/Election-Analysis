# Election-Analysis

## Project Overview
A Colorado Board of Elections employee has given the following tasks to complete the election audit of a recent local congressional election.

1. Calculate the total number of votes cast.
2. Get a complete list of candidtates who received votes.
3. Calculate the total number of votes each candidate received.
4. Calculate the percentage of votes each candidate won.
5. Determine the winner of the election bashe on popular vote.

## Resources
-Data Source: election_results.csv
-Software: Python 3.7.6, Visual Studio Code, 1.63.0

## Summary
The analysis of the election show that:
-There were 369,711 votes cast in the election.
-The Candidates were:
  -Charles Casper Stockham
  -Diana DeGette
  -Raymon Anthony Doane
- The Candidate results were:
  -Charles Casper Stockham recieved 23.0% of the vote and 85,213 number of votes.
  -Diana DeGette recieved 73.8% of the vote and 272,892 number of votes.
  -Raymon Anthony Doane recieved 3.1% of the vote and 11,606 number of votes.
-The winner of the election was:
  -Diana DeGette, who received 73.8% of the vote and 272,892 number of votes
  
## Challenge Overview
The Elections Commistion requested additional data:
-Voter turnout for each county
-Percentage of votes from each county out of the total count
-The county with the highest turnout

There were a total of 369,711 votes casted within the 3 counties represented: Arapahoe, Denver and Jefferson. By using similar code I used to find the  Candidates data, and using nested for loops, I was able to find out the outcome within the counties at the same time I was finding out the outcome of the candidates. 

Here is the .txt file of the code that was ran in VS Code. 

![Screen Shot 2021-12-12 at 9 17 11 PM (2)](https://user-images.githubusercontent.com/93801125/145747304-dfbc1ed8-0b59-4883-a4c2-899186c44ae6.png)

As you can see, Arapahoe had the least votes of 24,801 and a percentage of 6.7 of the votes casted. Jefferson came in second, with 38,855 votes and 10.5% of the votes casted.  Denver cast the most votes with 306,055 votes and a whopping 82.8% of the vote tally.  That made Denver the county wit the largest turnout.

When it comes to candidtates, there were three condtenders. Raymon Anthony Doane came last with 11,606 votes and only 3.1% of the total votes. Charles Casper Stockham had 85,213 votes, which gave him 23.0% of the votes and brought him second place.  Diana DeGette received the most votes of 272,892 and 73.8% of the total votes and the clear winner.

## Challenge Summary

With this script, the Elections commision can use this with any election. Modifications would need to be made to which file is being accessed. Also, if more variables besides 'Ballot ID', 'County', and 'Candidate' were used, further script would need to be made, and/or adjusted depending on the layout of the table provided (ie: which row does county and candidates land on).
