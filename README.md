# Pewlett-Hackard-Analysis

Overview of the analysis: The purpose of this analysis was to understand how to use postgres to perfrom various analysis on employee data from Pewlett-Hackard. I used a variety of methods like the DISTINCT ON, WHERE, and JOIN in order to identify the number employees per employee titile for those born between 1952-1955 and left by 01-01-1999. Additionally, I used similar methods to create a table of those eligible for mentorship based on age by joining two datasets.


Results: Provide a bulleted list with four major points from the two analysis deliverables. Use images as support where needed.

1. First major result was the creation of a table that filtered employee data by date of birth and date of resignation. In the screenshot below you see that there are duplicates in the data because many employees may have changed titles in the company but retained the same employee number. This is a good raw dataset but needs to be cleaned. 




2. The second major result was the creation of another table that removed the duplicates in the table above by using the DISTINCT ON method to pull employee numbers and ordered by number and date of resignation. 



3. The third major result was the final table that organized the unique dataset that removed the duplicate to show the number of employees by recent title. As shown in the screenshot below, there are over 25,000 Senior Engineers but only 2 Managers. 

4. Lastly, the table below shows employees born in the year 1965 who are eligible for mentorship. 


