# Pewlett-Hackard-Analysis

Overview of the analysis: The purpose of this analysis was to understand how to use postgres to perfrom various analysis on employee data from Pewlett-Hackard. I used a variety of methods like the DISTINCT ON, WHERE, and JOIN in order to identify the number employees per employee titile for those born between 1952-1955 and left by 01-01-1999. Additionally, I used similar methods to create a table of those eligible for mentorship based on age by joining two datasets.


Results: Provide a bulleted list with four major points from the two analysis deliverables. Use images as support where needed.

1. First major result was the creation of a table that filtered employee data by date of birth and date of resignation. By adding the filter WHERE and using the date 01-01-1999 I was able to figure out a way to clean the data of duplicates without another set of code. 
2. 
![image](https://user-images.githubusercontent.com/96396696/155832365-7171bb4e-82b7-4e32-b30f-da1f3c14a54d.png)

However, if I was to remove the WHERE clause, then it would provide a data set in which there are duplicates, as shown in the screenshot below.
![image](https://user-images.githubusercontent.com/96396696/155832745-f74bd1c9-72c5-4141-b6f3-c1663741f67a.png)

2. The second major result was the creation of another table that removed the duplicates in the table above by using the DISTINCT ON method to pull employee numbers and ordered by number and date of resignation. 

![image](https://user-images.githubusercontent.com/96396696/155832378-9109bb5e-741e-4bb4-899f-090c030f1cfc.png)

3. The third major result was the final table that organized the unique dataset that removed the duplicate to show the number of employees by recent title. As shown in the screenshot below, there are over 25,000 Senior Engineers but only 2 Managers. 

![image](https://user-images.githubusercontent.com/96396696/155832388-062538db-d183-4e94-9d3d-c362b56fb0e3.png)

4. Lastly, the screenshot  below shows the code used to identify employees born in the year 1965 who are eligible for mentorship. 

![image](https://user-images.githubusercontent.com/96396696/155832566-3963228f-b1e0-43e7-9645-f4e32f74e3a4.png)
