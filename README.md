# Mars News Analysis

##Deliverable 1: Scrape Titles and Preview Text from Mars News

###Step 1: Visit the Website
I used automated browsing to visit the Mars news site and inspected the page to identify which elements to scrape.

###Step 2: Scrape the Website
I created a Beautiful Soup object and used it to extract text elements from the website. I then created an empty list so I can use it to loop throught the Mars news articles to retrieve the titles and the previews from the html.



##Deliverable 2: Scrape and Analyze Mars Weather Data

###Step 1: Visit the Website
I used automated browsing to visit the Mars Temperature Data Site and inspected the page to identify which elements to scrape.

###Step 2: Scrape the Table
I create a Beautiful Soup object and use it to scrape the data in the HTML table and extracted all the rows from the table from the website.

###Step 3: Store the Data
I assembled the scraped data into a Pandas DataFrame. The columns  have the same headings as the table on the website. I first created an empty list in order to loop through the scraped data to retrieve all the rows. I did this seperatley for the headers. I then created a pandas dataframe by using the list of rows and a list of column names. 

###Step 4: Prepare Data for Analysis
I examine the data types that are currently associated with each column. I casted/converted the data to the appropriate datetime, int, or float data types.

###Step 5: Analyze the Data
I analyzed my dataset by using Pandas functions to answer the following questions:

1.How many months exist on Mars?
2.How many Martian (and not Earth) days worth of data exist in the scraped dataset?
3.What are the coldest and the warmest months on Mars (at the location of Curiosity)? To answer this question:
    -Find the average the minimum daily temperature for all of the months.
    -Plot the results as a bar chart.
4.Which months have the lowest and the highest atmospheric pressure on Mars? To answer this question:
    -Find the average the daily atmospheric pressure of all the months.
    -Plot the results as a bar chart.
5.About how many terrestrial (Earth) days exist in a Martian year? To answer this question:
    -Consider how many days elapse on Earth in the time that Mars circles the Sun once.
    -Visually estimate the result by plotting the daily minimum temperature.





---

© 2022 edX Boot Camps LLC. Confidential and Proprietary. All Rights Reserved.
