# Election_Analysis_
Module 3 Challenge
# Election Audit 

## Overview of Election Audit
### An election audit was completed to review the voter turnout by county, the percentage of votes by county, and the county with the highest turnout. The audit was built off an initial review, which identified election votes by candidate, percentage of votes by candidate, and the candidate with the highest total votes. 

## Election Audit Results
Below is a summary of the election results followed by a visual of results:
- A total of 369,711 votes were cast in the congressional election. 
- The breakdown of votes by county was as follows: Denver County with 306,055 votes for 82.8% of the total vote, Jefferson County with 38,855 votes for 10.5% of the total vote, and Arapahoe County with 24,801 votes for 6.7% of the total vote.   
- Denver County had the highest total votes with 306,055 votes.
- The breakdown of votes by candidate was as follows: Charles Casper Stockham with 85,213 votes for 23.0% of the total vote, Diana DeGette with 272,892 votes for 73.8% of the total vote, and Raymon Anthony Doanne with 11,606 votes for 3.1% of the total vote.
- Diana DeGette won the election with 272,892 votes for 73.8% of the total vote. 

![Election Audit Results](https://github.com/codfjenn/Election_Analysis_/blob/main/Election%20Analysis%20Results.png)

## Election Audit Summary
The script created can be modified to review results of other elections. Below are two examples for how the script could be used for additional analysis. 
- The script could review other elections with csv data provided in a similar format. The script would need the file_to_Load and the file_to_save updated in order to pull in the new dataset and create a new output. See below snip of the location of these items. 
![Script to Update](https://github.com/codfjenn/Election_Analysis_/blob/main/File%20to%20Load%20and%20file%20to%20save%20visual.png)

- The script could be modified to review election percentages by candidate by county. Additional code would need to be added to allow us to see which candidate won each county. Currently, the code does not have this data, but we could create an additional if statement to total votes by candidate to identify the specific county. 
