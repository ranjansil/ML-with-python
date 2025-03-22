Data analysis for Netflix Movies and TV Shows
1.	Data Loading and Inspection:
•	After loading the data in the panda’s data frame, I used the head function to show the first few rows of the data so that I get more insight about the dataset.
•	 I then checked for null values and found quite a few of them. So, I used the drop command to drop all the null values. But this was not a good idea. Let’s discuss it in data exploration. 

2.	Data Exploration:
•	When I dropped all the cells with null values it changed the values in my pie chart. So, I had to revert this command and make the pie chart without dropping the columns with null values. 
•	I noticed the value change as I compared my python pie chart with me excel (.csv file) pie chart and there was a significant number of percentage changes.

3.	Country Analysis:
•	The top 5 countries contributing to Netflix’s content library are Unites states, India, United Kingdom, Japan, and South Korea.
•	This can be used for the company to know what types of content the audience is most interested in. This can help Netflix put out more of the same type of content to attract more audience to their website.

4.	Rating Analysis:
•	The top 5 most rated content are TV-MA, TV-14, TV-PG, R and PG-13.
•	The platform's recommendation algorithms may prioritize content with these top 5 ratings, as they are the most common and likely to appeal to a large portion of the audience.
•	Knowing that TV-MA, TV-14, TV-PG, R, and PG-13 are the most common ratings, the platform can use this information to tailor recommendations to individual users based on their viewing history and preferences. 

5.	Release Year Analysis:
•	During this analysis I made three graphs for the visualization of the release year analysis. The first line plot covers all the years in the data set and the second one covers most of the recent years. The third one is a bar graph with the number of shows counted on top of each bar.
•	All the graphs have the same trend as the number of shows increased in recent years. 
•	The years between 2016 to 2021 have the greatest number of shows released. With year 2016 had 429 shows, 2017 had 1198 shows, 2018 has 1649 shows, 2019 had 2016 shows, 2020 had 1879 shows, and 2021 had 1498 shows. 
•	The increasing number of shows released each year indicates a growing demand for content among viewers. Netflix can use this information to continue investing in a diverse range of content to cater to this demand.
•	By analyzing the types of shows that were popular each year, Netflix can determine the optimal mix of genres, formats, and themes to include in its content section. 

6.	Duration Analysis:
•	During this analysis I came across value error. So, I looked for null values in the duration column.
•	I encountered three null values that were causing a value error. To resolve this issue, I replaced the null values with 0. I chose 0 as the replacement value because using a special character or an alphabet would have resulted in another value error. Therefore, using a numeric value was the most suitable option. 
•	I then again checked for null values to make sure that there were no null values left. 
•	The movie duration histogram reveals that the majority of movies fall within the 90 to 140-minute range. 
