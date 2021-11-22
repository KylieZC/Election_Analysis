# Election_Analysis
## Overview of Election Audit
This project helps a Colorado Board of Elections employee, Tom, to tabulate the result for the U.S. Congressional precinct in Colorado. This analysis uncovered multiple data based on the Python automatic process, including the total number of votes cast, the total number of votes for each candidate, the percentage of votes for each candidate, and the election winner.


## Election-Audit Result
** * How many votes were cast in this congressional election? **

The total number of votes is 369,711. It is equal to the total number of rows in "election_results.csv" based on the for loop method. This loop iterates through each row and increments the "total_votes" variable by 1.

![total_votes1](Resources/total_votes1.png)
![total_votes2](Resources/total_votes2.png)




* Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct. 

Below picture shows that the process retrieves the county's total vote count and uses the equation to calculate the vote percentage of each county. Followed by the f-string in the next step, so the rate is formatted to one decimal place.

_Results of each county_
![c_vote_percentage](Resources/c_vote_percentage.png)




* Which county had the largest number of votes?
The largest number of votes is Denver.
They are applied the if statement to determine the county with the largest vote by comparing the percentage amount. 

**Largest number of votes**
![largest_count](Resources/largest_count.png)


* Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.

**Results of each candidate**
![vote_percentage](Resources/vote_percentage.png)


* Which candidate won the election, what was their vote count, and what was their percentage of the total votes? 

Diana DeGette won the election with 73.8% of the total votes. The code uses the separate f string to identify the winner. 

**Winner of the election**
![winner](Resources/winner.png)


## Election-Audit Summary
The script can be used in other congressional districts and local districts elections with the following steps:
 1. Save all the data in an Excel document. Data contains the candidate names, state governments' names, and the ballot ID.
 2. Retrieve the total number of votes cast.
 3. Figure out the complete list of candidates who received votes.
 4. Find out each candidate's vote percentage.
 5. Identify the total number of each candidate won.
 6. Determine the winner of the state government election based on the vote.
