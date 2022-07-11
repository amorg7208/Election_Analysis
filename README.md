# Election_Analysis

## Project Overview
The Colorado Board of Elections has requested an election audit for a recent local congressional election. Required tasks are as follows:

1. Calculate the total number of votes cast.
2. Get a complete list of candidates who received votes.
3. Calculate the total number of votes each candidate received. 
4. Calculate the percentage of votes each candidate won.
5. Determine the winner of the election based on popular vote.

## Resources
Data Source: election_resluts.csv <br />
Software: Python 3.9.12, Visual Studio Code, 1.38.1

## Summary
The analysis of the election shows that:
- There were 369,711 total votes cast in the election.

<img width="443" alt="Screen Shot 2022-07-10 at 6 09 06 PM" src="https://user-images.githubusercontent.com/106630710/178178716-1369a975-e673-4590-b58b-4580fdb1b452.png">

- The candidates were:
  - Charles Casper Stockham
  - Diana DeGette
  - Raymon Anthony Doane
  
  <img width="514" alt="Screen Shot 2022-07-10 at 6 10 38 PM" src="https://user-images.githubusercontent.com/106630710/178178649-932522ac-9812-4fa9-91b3-3018a7961863.png">
  
- The individual county results were:
  - Jefferson with 10.5% of the vote and 38,855 number of votes.
  - Denver with 82.8% of the vote and 306,055 number of votes.
  - Arapahoe with 6.7% of the vote and 24,801 number of votes.
  
- The county that received the most votes was:
  - Denver, with 82.8% of the vote and 306,055 number of votes. 

<img width="663" alt="Screen Shot 2022-07-10 at 6 13 31 PM" src="https://user-images.githubusercontent.com/106630710/178178524-02dd534e-46ea-4333-81be-ec53f33b11c8.png">

- The candidate results were:
  - Charles Casper Stockham received 23.0% of the vote and 85,213 number of votes.
  - Diana DeGette received 73.8% of the vote and 272,892 number of votes.
  - Raymon Anthony Doane received 3.1% of the vote and 11,606 number of votes.

- The winner of the election was:
  - Diana DeGette, who received 73.8% of the vote and 272,892 number of votes. 
  
  <img width="539" alt="Screen Shot 2022-07-10 at 6 14 59 PM" src="https://user-images.githubusercontent.com/106630710/178178590-8e948f16-c764-482c-8869-dd3e8b9b59eb.png">

<img width="303" alt="Screen Shot 2022-07-10 at 7 40 09 PM" src="https://user-images.githubusercontent.com/106630710/178178868-b22d8c15-62cb-41b7-80b1-f71fcc36e699.png">
  
## Election Audit Summary
This code can easily be reproduced to provide insight into other analyses. It can be used as a skeleton to pull information from a new data source that could include demographic information about voters, such as, age, gender and political alignment. This type of insight would be helpful for future campaigns. This code structure could also be used for other audits at the local government level such as figuring out how many votes were cast at specific voting locations vs mail in ballots.
