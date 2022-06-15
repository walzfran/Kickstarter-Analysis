# Kickstarter-Analysis
Module One Challenge
# Kickstarting with Excel
## Overview of Project
### This project is to assist our client, Louise, in understanding fundraising by analyzing data from multiple failed and successful crowd funding campaigns based on launch date and the inital goal amounts.
## Analysis and Challenges
### Analysis of Outcomes Based on Launch Date
#### When looking at the outcomes based on launch date we are taking data and categorizing it in a pivot table to allow us to filter the data by different outputs including the parent category, in this chart it is 'Theater'. When filtering we can select one or multiple categories to allow us to analyze the data that is pertaining to what our client, Louise, is looking for. The way this data has been filtered also has the date launched as a month category and breaks the data into how many kickstarters were successful, failed or canceled and totals the sum of each kickstater launched by month. This information was then turned into a line chart to reflect the data that is in the pivot table in an easier way to read graphic. The x-axis is representing the months and the y-axis represents the amount of campaigns launched. There are three different lines showing successful, failed and canceled. Please see below for the final line chart.

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/106924615/173468381-8c36057d-4cd0-4cff-bd41-97fcd4a1fcb9.png)

### Analysis of Outcomes Based on Goals
#### Looking at the outcomes based on goals we are taking data and categorizing it in a table that shows the inital goal of the kickstarter and breaks it down by monetary values; less than $1,000, $1,000 to $4,999, $5,000 to $9,999 and so on ending with over $50,000 using increments on $5,000. We categorize it using the COUNTIFS function in excel which applies criteria sets to cells across multiple ranges and counts the number of times all criteria are met. We use the function to show how many 'Plays' kickstarters were successful, failed or canceled in each goal range. We then take the information populated by the function to break it down into percentages which requires us to use the SUM function to add all of the kickstarters in each goal range to allow us to fine the percentage successful, failed and cancelled by dividing the amount of successful by the total and so on. Once all of this information has been calculated wecan create a line chart to reflect the data in an easily digestable visual. The chart below uses the y-axis to reflect the percentage and the x-axis to reflect the goal range. 

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/106924615/173468451-3976fa65-4138-457c-a4ef-d5c7e4d2e183.png)

## Challenges and Difficulties Encountered
#### When starting the project I felt confident that I would be able to finish the tasks at hand easily but I did encounter a few challenges when creating the different outcome charts. The Theater Outcomes by Launch Date pivot table was easy enough for me to insert and categorize the data in the correct outputs but I struggled to figure out how to classify the data in the rows by month. I was able to google this and figure out how to filter the data correctly to show each month using this [video](https://trumpexcel.com/group-dates-in-pivot-tables-excel/). Once my pivot table was reflecting the correct data I was able to label the line chart and both items matched what it was supposed to reflect. Moving on, the COUNTIFS function was very challenging for me. I really struggled to format the critera ranges in the correct order, I was able to watch this [video](https://support.microsoft.com/en-us/office/countifs-function-dda3dc6e-f74e-4aee-88bc-aa8c2a866842?ui=en-us&rs=en-us&ad=us) linked to the assignment in the module but I still had a hard time getting my line graph to match the given example. I was able to compare the two to find where mine differend and then alter the critera I had set in the function to match the charts. After working on this function for awhile and feeling a bit down about it I was able to actually understand the function a bit more to truly see how it should be used rather than just copying a function given to me.

## Results
#### What are two conculsions you can draw about the Outcomes Based on Launch Date? 
* A couple conclusions that I have drawn from the Outcomes Based on Launch Date are that the most successful month to launch a kickstarter campaign is May, I say that because there the most total kickstarters launched in May and it also has the highest amount of successful kickstarters and the least amount of failed comparable to the amount of total kickstarters launched. The other being that December is the least successful month to launch a kickstarter campaign as it is almost a 50/50 with failed and successful campaigns started. It seems as though there is a pretty steep decline in the number of successful campaigns and seems to bottom out in December which makes you start to wonder what is so special about the month of May. 
* I then started to research the seasons of broadway and and came across an [article](https://www.nytix.com/articles/broadway-seasons) that outlines the seasons of Broadway. It appears that Fall is the best time to debuet a play. That then sparks the question of how long does it take from receiving funding to curtain call. I used the AVERAGE function to see how long the kickstarters lasted and that showed an average of 30.77 days, so just about a month which would lead the closing date of most of the kickstarters to be one month after they started. Once the kickstarter is closed, that would give 4-6 months to launch the play in the peak fall season. From my search on the internet I found a couple of articles, the [first](https://lionhearttheatre.org/theatre-production-from-the-script-to-the-stage/) gives steps on the production in order and the [second](https://www.musicals101.com/putontime.htm) gives rough timelines. Allowing for about a month to form a production crew and lock in details of scripts and tickets ordered, a month for casting, and 2 months for rehearsals that would lead you right into the perfect time to launch a new play. 
* Using the information I gathered on why May would be the best month to launch you can see why December may be the worst, given the same timeline if you ended your campaign in Janurary you would barely make it in time to be eligible for a [Tony award](https://www.tonyawards.com/about/rules-and-regulations/), as the deadline is typically at the end of April. If that was not the goal of the pay, and you launch in the summer, you are then competing with travel, less buzz in the theater community and summer holidays. All that being said, I may be looking at too broad of information for it to pertain to Louise and the show that she is trying to put on and the data set that we are working with is for lower budget plays that would not necessarily be making it to Broadway. 
#### What can you conclude about the Outcomes based on Goals?
* The conculsion that I took away from the Outcomes Based on Goals is that there 

