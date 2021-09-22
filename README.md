# Olympic Data Visualization
## Data 
The data I propose to visualize for my project is the Olympic data from 2000 to 2014. It is extracted from kaggle [link](https://www.kaggle.com/the-guardian/olympic-games).  
The [oylmpic dataset](https://gist.github.com/RuofanChen/b8ab70bdb93f363cf55e6390ad39805b) used for this project is posted on github gist. 

This dataset describes the performance of different countries in every Olympic Games (Summer and Winter).

Data key features:
* Year (quantitative): Year
* Medal (categorical): Which medal (gold, silver or bronze) did this athlete obtain
* Country (categorical): Which country of political groups does this athlete belong to


## Questions & Tasks
The following tasks and questions will drive the visualization and interaction decisions for this project:  


* Do most countries perform differently in the Winter Olympics and the Summer Olympics? Use a map to display the number of medals won by each country. According to the year and the type of Olympic Games (optional in winter and summer).
* How does GDP affect a country's performance? Use GDP and population data from 2015.
* Wants to see the athlete with the most medals? Use a bar chart to show the total number of medals, type of medals, the year of the medal and the event in which the medal was awarded.
* Does the number of gold medals in a country changes over time? Can we see the trend?
* What about the country’s medal-winning project? Use a pie chart to show the country’s recent two Olympic medals.


## Sketches
(insert one or more hand-drawn sketches of interactive visualizations that you imagine) (describe each sketch - how is the data visualized, what are the interactions, and how do these relate to the questions/tasks). 



## Prototypes
I’ve created a proof of concept visualization of this data.  
This scatter plot describes 2012 summer olympic games medal count by country and the country's GDP(2015 estimated). x-axis is gdp y-axis is the number of medals. This is a marked scatter plot. When the mouse is hovering over the point, the country name will be displayed
There is a linear relationship between GDP and the number of medals. As GDP increases, the country tends to win more medals at the summer Olympics.  

[![image](https://user-images.githubusercontent.com/57047582/134273629-f4adb498-2362-47d5-a815-6ff1549d15b2.png)](https://vizhub.com/RuofanChen/af53cd1647bd45ebbfd0886ad51f5e48)
    
 
This bar chart shows the top athletes and their medals. This is an interactive bar chart. When your mouse is pointed at the athlete's bar, it will display the athlete's name, the year of the medal and the event in which the medal was awarded.  

[![image](https://user-images.githubusercontent.com/57047582/134274019-9ac4e988-0215-4f3c-a5de-f81dd8bda8eb.png)](https://vizhub.com/RuofanChen/f1c54c3e6630474bb37f77bebd48f42f)
