                                                                # Youtube-API-project #
<br>Project Description<br>
This project observed the YouTube ‘s Videos category, counts, likes and comments based per country and its relation to each other. This project answers the question
Our analysis focuses on answering below questions:<br>
•	Is there a significant difference in the average like count of the top 50 videos within each designated region within YouTube?<br>
•	Ha: Average like count will be significantly different between the regions<br>
•	H0: There is no difference between the average like count by region<br>
•	Is there a significant difference in the average like count of the top 50 videos of each designated category within YouTube?<br>
•	Ha: Average like count will be significantly different between the categories<br>
•	H0: There is no difference between the average like count by category<br>
•	Additional Correlations:<br>
What is the average percent of videos liked by the number of views they have received?<br>
Limitation  <br>
Could only pull 50 videos per country. Also the API which could pull the Category of videos was under maintenance  by YouTube so we had to come up with list of 20 category’s (Google search) and use them in project. Also retrieved files per day changes the amount of record. So we have retrieved 5000 records for one and did the analysis.<br>

How this project works : <br>
Project is built to call the YouTube API’s dataset related to Video . Due to large size,  dataset is saved in CSV file for further analysis(5000 records). Python matplotlib, bar graph, pie charts are used to analyzed the data and specify the correlation in between videos, categories, likes, views and counts. Various methods such a correlation, aggregation, t-test, comparison , ANOVA tests are used to do further analysis of data.<br>

Build with :<br>
Python <br>
YouTube API<br>
GitHub<br>
Jupyter Notebook<br>
CSV Files<br>

Some of the challenges we faced <br>
When setting up the pie chart for ‘Percent View Count per category’, we realize that pie chart is colliding 	country names label names and making impossible to read the names. We came up with solution to 	separate the pie chart in two sections , 1st part displays the top 5 countries while 2nd is grouped for other       	countries. Also, we faced issues with Heatmap.

Features we hope to implement in the future <br>
Being able to implement the analysis of  demographic data  such as impact of having internet connectivity impacts the video’s likes, views, comments count.

Data Visualization :<br>
As part of Data Visualization, Bar graphs , Pie Charts, Box Plots are used to display correlation and linear regression of data. P-value and t-test , ANOVA  test, linear regression tests are also calculated to show the relation between data and its hypothesis acceptance. 
 
![image](https://user-images.githubusercontent.com/112952607/219431358-24127e81-9486-4265-9c38-4f2b1519153b.png)

![image](https://user-images.githubusercontent.com/112952607/219431382-5f568234-3086-45e2-a147-8fc08d2c609d.png)

![image](https://user-images.githubusercontent.com/112952607/219431400-4d0146ab-a8ae-43f2-91c7-4d9ce9ada5ef.png)

![image](https://user-images.githubusercontent.com/112952607/219431427-bc0e552e-509a-44be-be3f-3e7aed715da6.png)

![image](https://user-images.githubusercontent.com/112952607/219431444-212bf1de-3e09-41d6-a18b-3a4eab836d8f.png)

![image](https://user-images.githubusercontent.com/112952607/219431462-35ad0eba-a621-4acc-82f3-783f9dd1aea5.png)

![image](https://user-images.githubusercontent.com/112952607/219431478-91f8158d-74b6-4e32-a6fe-13a97e284b30.png)


 

Project Analysis<br>
1.	Accepting the findings as we have done ANOVA, t-test, and correlation coefficient that this Hypothesis testing is acceptable.<br>
2.	P-Value is less than 0.05 so we reject the null hypothesis and conclude that there are differences between regions and in their like counts and view counts.<br>
3.	P-Value is less than 0.05 so we reject the null hypothesis and conclude that there are differences between category and in their like counts and view counts.<br>
4.	Chances of getting more views, likes and comment counts from a video created for Music and Entertainment category is more compared to other categories such as DIY, Sports, News and Politics. <br>
5.	Music and Entertainment industry is in total has 65% more views compared to other categories.<br>
6.	Surprisingly, Cambodia has highest view count (approx. 14 billion) compared to other top country views. This may be due to Cambodian viewership being more highly concentrated in the top 50 most popular videos for that country.<br>
7.	As view count increases the like and comment counts also increases accordingly.<br>
8.	Top 5 countries that have the highest density of viewership are all located in Eastern or Southern Europe. It could indicate either cultural or socio-economic trend of those regions, or combination of both.<br>


https://github.com/PatttyCakess/Youtube-API-project<br>
References :<br>
YouTube API -  https://developers.google.com/youtube/v3<br>
Python - https://pandas.pydata.org/<br>
GitHub - https://github.com/PatttyCakess/Youtube-API-project<br>
