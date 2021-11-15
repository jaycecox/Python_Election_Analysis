# PyPoll_Election_Analysis

# Analysis of Election Audit:

 An audit of the most recent local election, with voting results for each candidate and county.


 # Resources
* Data Source: election_reslults.csv

# Election Results

* Total Votes in the election: 
    - Total_Votes: 369,711
* Each county's percentage and count of votes:
    - Jefferson: 10.5% (38,855)
    -  Denver: 82.8% (306,055)
    - Arapahoe: 6.7% (24,801) 
* The county with the largest voter turnout:
    - Denver
* Each candidate's percentage and counts of votes:
    - Charles Casper Stockham: 23.0% (85,213)
    - Diana DeGette: 73.8% (272,892)
    - Raymon Anthony Doane: 3.1% (11,606)
* The winner of the election with the winning vote count and winning percentage of votes:
    - Winner: Diana DeGette
    - Winning Vote Count: 272,892
    - Winning Percentage: 73.8%

![my analysis](./C:\Users\jayce\Desktop\Class Folder\Python Election Analysis\Python_Election_Analysis\Images\election_analysis.PNG)

# Election Audit Summary:

The code does not use a specific candidate or county name, therefore this code can be applied to audit any election with the following modifications:
1.  A CSV file must be provided for each election. 
    * The code can support any CSV election file no matter the number of candidates or counties. 
2.  Each audit must have its own election_analysis file in order to record the results of each election.
3.  The code can by modified based on the level of the election. For example, if the CSV file provided is for a national election, "county" in the code can be replaced with "state". For a county wide election, "county" in the code can be replace with "precint" as long as the CSV file has the corresponding header.  


