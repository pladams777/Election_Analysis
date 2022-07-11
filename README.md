# Election Analysis - Audit of Colorado US Congresional Race Results

![Vote](https://user-images.githubusercontent.com/107540080/178165824-e130eff7-1c73-4002-95b4-f006fe980c45.jpg)

## Project Overview
A Colorado Board of Elections employee has requested the following tasks to complete the election audit of a recent local congressional election:
  * Calculate the total number of votes cast.
  * Determine the county with the highest voter turnout  
  * Retrieve a complete list of candidates who received votes.
  * Calculate the total number of votes each candidate received.
  * Calculate the percentage of votes each candidate received.
  * Determine the winner of the election based on popular vote.
  
### Resources
 - Data Source: [Election Results](https://github.com/pladams777/Election_Analysis/blob/main/Resources/election_results.csv) (csv file provided by the election board)
 - Software: Python 3.9.12, Visual Studio Code 1.69.0

### Election Audit Results
**The Audit determined the following:**
    
 * There were 369,711 votes cast in the election. 
 * Total votes cast and percentage by county:
    - Arapahoe: 6.7% (24,801)
    - Denver: 82.8% (306,055)
    - Jefferson: 10.5% (38,855)
 * *Denver County* had the highest voter turnout.
 * Candidate Results:
    * Charles Casper Stockham received 23.0% of the total votes with 85,213.
    * Raymon Anthony Doane received 3.1% of the total votes with 11,606.
    * Diana DeGette received 73.8% of the total votes with 272,892.
 * The winner by popular vote:
    * **Diana DeGette** with 272,891 votes giving her 73.8% of the total votes.
    
### Election Audit Summary
Using a Python script, we were able to take a large amount of data and extract detailed and pertinent information. With some additional data points and slight script modifications we would be able to extract other important data, such as preferred voting methods (mail-in vs in-person) and, preferred voting days (early voting vs Election Day). This information can assist campaign strategy and election procedures. The script is scalable for elections of any size including Senatorial elections and local or statewide elections.
