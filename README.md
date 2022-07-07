# Tableau Homework - Citi Bike Analytics

### Before You Begin

* This assignment will be saved to your Tableau Public account rather than GitHub.

* If you haven't already, be sure to create a Tableau Public account [here](https://public.tableau.com/s/).

* The free tier of Tableau only lets you save to their public server. This means that each time you save your file it will be uploaded to your Tableau Public profile.

* You are able to load and continue working on the same workbook.

* When you are finished with your assignment, you will turn in the URL to your Tableau Public workbook along with any additional files used for your analysis.

## Background

![Citi-Bikes](Images/citi-bike-station-bikes.jpg)

Congratulations on your new job! As the new lead analyst for the [New York Citi Bike](https://en.wikipedia.org/wiki/Citi_Bike) Program, you are now responsible for overseeing the largest bike sharing program in the United States. In your new role, you will be expected to generate regular reports for city officials looking to publicise and improve the city program.

Since 2013, the Citi Bike Program has implemented a robust infrastructure for collecting data on the program's utilisation. Through the team's efforts, each month bike data is collected, organised, and made public on the [Citi Bike Data](https://www.citibikenyc.com/system-data) webpage.

However, while the data has been regularly updated, the team has yet to implement a dashboard or sophisticated reporting process. City officials have a number of questions on the program, so your first task on the job is to build a set of data reports to provide the answers.

## Task

**Your task in this assignment is to aggregate the data found in the Citi Bike Trip History Logs and find two unexpected phenomena.**

**Design 2-5 visualisations for each discovered phenomena (4-10 total). You may work with a timespan of your choosing. Optionally, you may merge multiple datasets from different periods.**

**The following are some questions you may wish to tackle. Do not limit yourself to these questions; they are suggestions for a starting point. Be creative!**

**I decided to focus on comparing data from the Winter (January, February, December) to the Summer (June, July, August) months from the year 2017. Based primarily on the weather, I hypothesised that the total trips/ usage would be drastically higher during the Summer. Below are some summarised answers to questions relating to my analysis.**

* How many trips have been recorded total during the chosen period?
   - Between the Summer and Winter months of 2017, the total number of trips was 143,955 

<img width="377" alt="Number of trips recorded" src="https://user-images.githubusercontent.com/96853408/177030646-d44665e9-7dc6-4060-9d9a-ece667e29c5e.PNG">


* By what percentage has total ridership grown?
   - From January 2017 (12,926 rides) to August 2017 (35,472 rides) total Ridership grew by 174%.
   - This was followed by a sharp decline from August 2017 (35,472) to December (15,898), illustrating a 55% decrease. 

<img width="270" alt="Number of trips recorded per month" src="https://user-images.githubusercontent.com/96853408/177028902-7e5dd8a4-b34b-4b92-a5ec-d80b2ae9139d.PNG">

* How has the proportion of short-term customers and annual subscribers changed?
   - January illustrated 81 short-term customers to 12,827 subscribers, roughly 1 customers : to every 158 subscribers. 
   - Comparising this to the last month of Summer.
   - August - illustrated 2,470 short-term customers to 33,002 subscribers, roughly 1 customer : to every 13 subscriber, a signicantly closer ratio. 
   - This signicant drop in ratio (1:158 vs. 1:13),  demonstrates the proportion of short-term rider increases dramatically during the Summer months.   

<img width="434" alt="Trips by user type" src="https://user-images.githubusercontent.com/96853408/177030072-618b402e-05c0-469d-b426-257a92f4bef0.PNG">



* What are the peak hours in which bikes are used during summer months?
   -As illustated below the peak hours are between 7am to 9am, and 5pm to 7pm. 
   -8am was the busiest hour of the day recording 11,442 average total trips. 

<img width="540" alt="Peak Summer Hours" src="https://user-images.githubusercontent.com/96853408/177034332-80dd8534-404b-45ef-99b1-e6d2341ac497.PNG">

* What are the peak hours in which bikes are used during winter months?
   -Much like the Summer months, the peak hours were between 7am to 9am, and 5pm to 7pm. 
   - Once again 8am was the busiest hour recording 5,130 average total trips 

<img width="635" alt="Peak Winter Hours" src="https://user-images.githubusercontent.com/96853408/177034409-3dfc786d-b467-4e40-87af-9238b9189f17.PNG">


* Based on your dataset - what are the top 10 stations in the city for starting a journey? (Based on data, why do you hypothesise these are the top locations?)


<img width="387" alt="Top Ten Starting Stations" src="https://user-images.githubusercontent.com/96853408/177035345-8907cb0e-a2b1-4d78-9ef5-d9092bf07cc4.PNG">




* Based on your dataset- what are the top 10 stations in the city for ending a journey? (Based on data, why?)


<img width="356" alt="Top Ten Ending Stations" src="https://user-images.githubusercontent.com/96853408/177035376-766ef3a1-eeb2-4fb8-9099-42e0246b77e2.PNG">


* What are the bottom 10 stations in the city for starting a journey? (Based on data, why?)
     -All of the these 10 stations only demonstrated one count.
      -The bottom 10 stations for starting a journey are either at NYC bus stations or in Brooklyn, and outside of Manhattan, which has the largest concentration of        bike stations   


<img width="381" alt="Bottom Ten Starting Stations" src="https://user-images.githubusercontent.com/96853408/177035968-9e498701-a1d8-47d9-af25-cdc1ada4633a.PNG">


* What are the bottom 10 stations in the city for ending a journey (Based on data, why?)
    -Similar to above - these ten stations listed only one count
     - The bottom 10 stations for ending a journey are also similar to the bottom 10 stations in the city for starting a journey
     

<img width="398" alt="Bottom Ten Ending Stations" src="https://user-images.githubusercontent.com/96853408/177035971-23b835a4-1917-4b7a-9c4a-826ec4b2a6de.PNG">


* Based on your dataset-what is the gender breakdown of active participants (Male v. Female)?
<img width="397" alt="Gender Usge Percentage%" src="https://user-images.githubusercontent.com/96853408/177036005-5942bd29-d5d4-4a3d-ac1d-d8984309fae7.PNG">


* How effective has gender outreach been in increasing female ridership over the timespan?

   -Female ridership has increased year over year but male ridership still far outpaces all genders

* How does the average trip duration change by age?
  - Starting down with the eldest age recorded - 77 years old, the data steadily increases to 32. 
  - Average duration remians stagnant from users aged 31 to 28, then begins to decline sharply from 27 years or younger.  

  Average Trip Duration vs. Age.PNG


**Next, as a chronic over-achiever:**

* Use your visualisations (does not have to be all of them) to design a dashboard for each phenomena.
* The dashboards should be accompanied with an analysis explaining why the phenomena may be occurring.

**City officials would also like to see one of the following visualisations:**

* **Basic:** A static map that plots all bike stations with a visual indication of the most popular locations to start and end a journey with zip code data overlaid on top.

* **Advanced:** A dynamic map that shows how each station's popularity changes over time (by month and year). Again, with zip code data overlaid on the map.

* The map you choose should also be accompanied by a write-up unveiling any trends that were noticed during your analysis.

**Finally, create your final presentation**

* Create a Tableau story that brings together the visualisations, requested maps, and dashboards.
* This is what will be presented to the officials, so be sure to make it professional, logical, and visually appealing.

## Considerations

Remember, the people reading your analysis will **NOT** be data analysts. Your audience will be city officials, public administrators, and heads of New York City departments. Your data and analysis needs to be presented in a way that is focused, concise, easy-to-understand, and visually compelling. Your visualisations should be colourful enough to be included in press releases, and your analysis should be thoughtful enough for dictating programmatic changes.

## Submission

Your final submission should include:

* A link to your Tableau Public workbook that includes:
  * 4-10 Total "Phenomenon" Visualisations
  * 2 Dashboards
  * 1 City Official Map
  * 1 Story
* A text or markdown file with your analysis on the phenomenons you uncovered from the data.

## Sharing Your Work
In order to share your work, we are asking that you will save your workbook as a .twbx file so that your TA's can grade them.

To save your workbook as a .twbx file, you will just need to select "Save As..." from the "File" dropdown. Then, select the .twbx option.

## Assessment

Your final product will be assessed on the following metrics:

* Analytic Rigour

* Readability

* Visual Attraction


## Hints

* You may need to get creative in how you combine each of the CSV files. Don't just assume Tableau is the right tool for the job. At this point, you have a wealth of technical skills and research abilities. Dig for an approach that works and just go with it.

* Don't just assume the CSV format hasn't changed since 2013. Subtle changes to the formats in any of your columns can blockade your analysis. Ensure your data is consistent and clean throughout your analysis. (Hint: Start and End Time change at some point in the history logs).

* Consider building your visualisations with small extracts of the data (i.e. single files) before attempting to import the whole thing. What you will find is that importing all 20+ million records of data will create performance issues quickly. Welcome to "Big Data."

* While utilising all of the data may seem like a nice power play, consider the time-course in making your analysis. Is data from 2013 the most relevant for making bike replacement decisions today? Probably not. Don't let overwhelming data fool you. Ground your analysis in common sense.

* Remember, data alone doesn't "answer" anything. You will need to accompany your data visualisations with clear and directed answers and analysis.

* As is often the case, your clients are asking for a LOT of answers. Be considerate about their need-to-know and the importance of not "cramming in everything". Of course, answer each question, but do so in a way that is organised and presentable.

* Since this is a project for the city, spend the appropriate time thinking through decisions on colour schemes, fonts, and visual story-telling. The Citi Bike program has a clear visual footprint. As a suggestion, look for ways to have your data visualisations match their aesthetic tones.

* Pay attention to labels. What exactly is "time duration"? What's the value of "age of birth"? You will almost certainly need calculated fields to get what you need.

* Keep a close eye for obvious outliers or false data. Not everyone who signs up for the program is answering honestly.

* In answering the question of "why" a phenomenon is occurring, consider adding other pieces of information on socioeconomic or other geographic data. Tableau has a map "layer" feature that you may find handy.

* Don't be afraid to manipulate your data and play with settings in Tableau. Tableau is meant to be explored. We haven't covered all that you need -- so you will need to keep an eye out for new tricks.

* Treat this as a serious endeavour! This is an opportunity to show future employers that you have what it takes to be a top-notch analyst.

* Good luck!

### Copyright

© 2021 Trilogy Education Services, LLC, a 2U, Inc. brand. Confidential and Proprietary. All Rights Reserved.