# Module 3 Challenge

## Overview of Election Audit

The reason for this analysis is to audit whether each candidate's vote numbers match counties and totals. The commission requested the following audited numbers to verify that the data is good.

The following additional data were requested:

- The voter turnout for each county
- The percentage of votes from each county out of the total count
- The county with the highest turnout

The analyzed data file can be downloaded on [election_results.csv](https://github.com/lfhoepers/Election_Analysis/blob/f2ce6cf3ccbc58cc05cbebc5124cceb7d8e09046/Resources/election_results.csv).

The final code was developed in Python the file is [PyPoll_Challenge.py](https://github.com/lfhoepers/Election_Analysis/blob/f2ce6cf3ccbc58cc05cbebc5124cceb7d8e09046/PyPoll_Challenge.py).

The Final Results in TXT can be found on file [Election_Results.txt](https://github.com/lfhoepers/Election_Analysis/blob/f2ce6cf3ccbc58cc05cbebc5124cceb7d8e09046/Analysis/election_results.txt)


## Election-Audit Results

- How many votes were cast in this congressional election?

![image](https://user-images.githubusercontent.com/100812079/159141906-c0a1f602-1ed8-4e48-86f1-4bc5116dc180.png)

![image](https://user-images.githubusercontent.com/100812079/159142044-50f768ba-fde7-4156-9024-90ebd1d78ad6.png)

![image](https://user-images.githubusercontent.com/100812079/159142042-f1999546-795d-4a61-8333-ee4121d91c9d.png)

- Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.

![image](https://user-images.githubusercontent.com/100812079/159141928-372dbfc0-8914-4dcf-b2b9-2cfa5cf23543.png)

![image](https://user-images.githubusercontent.com/100812079/159142065-a9d5e458-90b6-4a10-8d40-1021d0172076.png)

![image](https://user-images.githubusercontent.com/100812079/159142072-fa50d163-4a30-4588-8ac1-56d7d78b94c9.png)

![image](https://user-images.githubusercontent.com/100812079/159142088-03e69624-b64e-421f-adc4-46c971f957a7.png)

- Which county had the largest number of votes?

![image](https://user-images.githubusercontent.com/100812079/159141942-2886006e-4e64-4b69-9f80-92982ec7b0b7.png)

![image](https://user-images.githubusercontent.com/100812079/159142106-964c44ec-0f53-4b7c-be54-24f84a72b3c2.png)

- Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.

![image](https://user-images.githubusercontent.com/100812079/159141952-c98a0537-2e18-4bc4-86fe-c1a6a25d8fc0.png)

![image](https://user-images.githubusercontent.com/100812079/159142125-58c1b112-b43b-41c1-b7d0-12f0eb42ae92.png)

![image](https://user-images.githubusercontent.com/100812079/159142135-41cf3bbe-87c5-4dfe-b1ae-52f36981b352.png)

- Which candidate won the election, what was their vote count, and what was their percentage of the total votes?

![image](https://user-images.githubusercontent.com/100812079/159141960-e2f550cf-eea2-4917-9167-bb5e9da84fbe.png)

![image](https://user-images.githubusercontent.com/100812079/159142146-9d182bd8-d9aa-4a7a-ba80-bab8490f09f9.png)

## Election-Audit Summary:

This script can be used for any other election there are many changes. First you must use a csv file with the information "Ballot ID,County,Candidate". Syntax is simple to count if you have this information.

- If in the file there is another column with the vote of each Ballots computed for Governor, we can add a variable calculating votes per governor taking the fourth column in the case **candidate_Governor_name = row[3]**.
- Another suggestion is if we continue with the CSV file, use an FTP to centralize all the elections in 1 point, and configure the Script for this FTP as soon as the files are uploaded. Of course, for security reasons I prefer to use a database. But this we can discuss in the modules ahead.

I appreciate the opportunity to present this project, I am available for any clarification.
I added my name to the end of the code because it is Audit, in the next ones the developer will comment.

![image](https://user-images.githubusercontent.com/100812079/159142551-b4cdcf13-d5b1-484f-9bfe-61568660c240.png)

**Luiz Fernando Hoepers**  
###### UofT SCS Data Analytics Boot Camp
