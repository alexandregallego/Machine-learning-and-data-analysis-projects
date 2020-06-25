# Project to detect misleading cycles within the management of linen in a hotel

Within this project my task was to obtain a Pandas dataframe with a list of possible misleading cycles between two given dates for a hotel of my choice. 
What is a cycle with something strange? A cycle where the difference (in absolute percentage) between the total aggregated tags and the aggregated tags in at least one of the four possible reading states (table ReadingStatus) in a cycle is bigger than 30%.
There are four ReadingStatus in the SOILED cycles (0,1,2,3) and four in the clean cycles (5,6,7,0). The list should contain the suspicious cycles between **2020-03-01** and **2020-03-15**.
