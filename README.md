# Movie Budget Data Analysis
*Nashville Software School Capstone Project*

### **Contents**
- [Motivation](#Motivation)
- [Data Analysis](#Data-Analysis)
- [Data Sources and Tools](#Data-Sources-and-Tools)
- [Challenges](#Challenges)
- [Thank You](#Thank-You)



### **Motivation**
With an interest in movies and always spending weekends with my family to go to the movies. I had always wondered what it took for a movie to be considered successful. This led me to collecting data of movies from 2006 to 2018 so that I could analyze it to see if there is any correlation with movie budgets with their success. I decided a good way for me to gauge success in movies was by how profitable they were. If there weren’t was I able to find something that successful movies have in common.




### **Data Analysis**
In my analysis, I found 3 different websites to help collect my data. With [IMDb](https://www.imdb.com/) I used their datasets. I had to unzip these datasets, connect them together, and pull the information I needed. I then had to find information on movie's production budgets and was able to use a small dataset of movies from [The Numbers](https://www.the-numbers.com/) website. I  then web scrapped [Box Office Mojo](https://www.boxofficemojo.com/?ref_=bo_nb_yl_mojologo) to get information on opening weekend earnings and number of theaters to movie was shown in. I needed to attach these datasets together and was able to merge them by movie title names and release year. After doing this I was still left with a few duplicate entries that I was able to filter out in Excel due to them having a low vote count for their reviews. From their I used Excel to create pivot tables to add to my PowerPoint presentation. I also used Power BI to create a dashboard so that I would have the ability to filter through the rest of the data and be able to see the different movies' information.








### **Data Sources and Tools**
**Data Sources**
- [Box Office Mojo](https://www.boxofficemojo.com/?ref_=bo_nb_yl_mojologo)
- [The Numbers](https://www.the-numbers.com/)
- [IMDb](https://www.imdb.com/)

**Tools**
- Jupyter/Python Notebooks used for gathering and cleaning data.
- Excel us for further cleaning Data and creating charts.
- PowerPoint used for presenting charts about data.
- Power BI for dashboard of data.






### **Challenges**
Some challenges that I faced where being able to locate the data needed for my capstone and also being able to link the different datasets together. With the data coming from three different websites I needed to find a way to link the datasets together, which I was able to do with the title and year of the movies. I also needed to create a loop that allowed me to scrap multiple pages from BoxOfficeMojo website. After getting the data pull together and into Excel I did notice a problem of duplicate entries. The duplicate data had a low count of votes compared to the original and did not match the ratings from IMDb so these entries where taken out. While creating my charts I needed to be able to separate the movies by budget so I had to create a new column in Excel that categorized the budgets by size. I used this to create my charts for my PowerPoint and also for my Power BI dashboard.









### **Thank You**

*Back to [Contents](#Contents)
