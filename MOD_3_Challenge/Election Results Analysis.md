Election Results Analysis

Overview of Election Audit

The purpose of this election audit was to help the election commission uncover data about the counties and candidates for the election. The commission wanted to uncover the voter turnout for the counties of Arapahoe, Denver and Jefferson, the percentage of the total vote each county contributed, and the county with the highest voter turnout. While working through this challenge I was able to uncover that the county Denver had the largest voter turnout, contributing to 82.8% of the total vote across all three counties. 

Election-Audit Results

- How many votes were cast in this congressional election? 
    369,711 total votes cast
- Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct
    County Votes:
        Arapahoe:  6.7% of total vote | 24,801 total votes for Arapahoe County
        Denver:  82.8% of total vote | 306,055 total votes for Denver County 
        Jefferson:  10.5% of total vote | 38,855 total votes for Jefferson County
- Which county had the largest number of votes?
    Denver County had the largest number of total votes with 306,055 of the total 369,711 votes.
- Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.
    Candidates:
        Charles Casper Stockham: 23.0% of total vote | 85,213 total votes
        Diana DeGette: 73.8% of total vote | 272,892 total votes
        Raymon Anthony Doane: 3.1% of total vote | 11,606 total votes
- Which candidate won the election, what was their vote count, and what was their percentage of the total votes?
    -------------------------
    Winner: Diana DeGette
    Winning Vote Count: 272,892
    Winning Percentage: 73.8%
    -------------------------

- Election-Audit Summary: In a summary statement, provide a business proposal to the election commission on how this script can be used—with some modifications—for any election. Give at least two examples of how this script can be modified to be used for other elections.

Though the script written is designed to help with the counties and candidates provided, it can be modified and used as a template to help with other elections. One way this code can be modified to use in other elections is by looking for data on other candidates or other counties. This can be done by changing the counties/candidates within the code to retrieve the correct data for the counties/candidates in question. This would most likely be stored in another .csv file than the one used for this analysis, so the name of the file where the data is retrieved will need to be updated as well. 

Another way this data can be modified and used for other elections is by inquiring about more information then just the counties. By this I mean the data can be used to pull information such as age of voters from each county to get more specific on the demographics of voter turnout. This can be used to determine which age group may have more voters compared to others and can even be sorted by county as well. Though this would require more modification within the code than than just changing the county or candidate. Age would need to not only be defined within the code but it would need to be located within the new .csv file so that our code does not break and is able to sort based on age as well.