## ELECTION_ANALYSIS

### 1) OVERVIEW OF ELECTION AUDIT:
A) The purpose of this audit is to analyse the election results and present them to the election commission. It includes the following additional data:
* The voter turnout for each county
* The percentage of votes from each county out of the total count
* The county with the highest turnout

B) RESOURCES : 
* Data source : election_results.csv
* Software: Python 3.8.8, Visual Studio Code

### 2) ELECTION AUDIT RESULTS:
Following are the election outcomes-

* Total votes were cast in this congressional election = 369,711
* Provide a breakdown of the number of votes and the percentage of total votes for each county

      **County Votes**

      Jefferson: 10.5% (38,855)
      Denver: 82.8% (306,055)
      Arapahoe: 6.7% (24,801)
  
* County with the largest number of votes : DENVER
* Breakdown of the number of votes and the percentage of the total votes each candidate received

      Charles Casper Stockham: 23.0% (85,213)
      Diana DeGette: 73.8% (272,892)
      Raymon Anthony Doane: 3.1% (11,606)
    
* Candidate who won the election, their vote count, and their percentage of the total votes

      Winner: Diana DeGette
      Winning Vote Count: 272,892
      Winning Percentage: 73.8%

### 3) ELECTION AUDIT SUMMARY:
a) This script can be modified to include larger dataset in the csv file representing candidate age, gender and their race . We can perform indexing with for loop variables as a simple addition to the existing code. Details such as vote turnout by political party can be summarized using this code, by adding if-statements, as well.

b) We could represent data from cities and not just counties. We can determine which cities hold a significant position in determining if a candidate would be the winner of the election. This data can be added into our election_results.csv file then basically run the same script as we did for our counties challenge in this module.

