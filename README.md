# Olympic Data Visualization
## Data 

The data I propose to visualize for my project is the Olympic dataset. It is extracted the Olympic Games and medal data on [kaggle](https://www.kaggle.com/the-guardian/olympic-games) from 2000 to 2014. This dataset includes 9679 rows for every Olympic athlete that has won a medal since the year 2000. It contains 12 columns, namely Year, City, Sport, Discipline, Athlete, Gender, Event, Medal, Season, Country, 2015Population, 2015GDP.per.Capita.

The [olympic dataset](https://gist.github.com/RuofanChen/b8ab70bdb93f363cf55e6390ad39805b) used for this project is posted on github gist. 

Features of the data:
* Year (quantitative): The year the medal was awarded
* City (qualitative): The host city of the Olympic Games
* Sports (qualitative): In which sport the medal was awarded
* Discipline (qualitative): In which discipline the medal was awarded
* Athlete (qualitative): The name of the athlete
* Gender (qualitative): The gender of the athlete
* Event (qualitative): In which event the medal was won
* Medals (qualitative): The type (gold, silver, or bronze) of medals awarded
* Season (qualitative): The season of the Olympic Games
* Country (qualitative): The country to which the athlete belongs
* 2015Population (quantitative): The 2015 population of the country where the athlete belongs
* GDP per capita in 2015. (Quantitative): 2015 GDP per capita of the country where the athlete belongs


## Questions & Tasks
The following tasks and questions will drive the visualization and interaction decisions for this project:  


* Q1: Do most countries perform differently in the Winter Olympics and the Summer Olympics? Use a map to display the number of medals won by each country. 
* Q2: How does GDP affect a country's performance? Use GDP and population data from 2015.
* Q3: Wants to see the athlete with the most medals? Use a bar chart to show the total number of medals, type of medals, the year of the medal and the event in which the medal was awarded.
* Q4: Does the number of gold medals in a country change over time? Can we see the trend?
* Q5: What about the country’s medal-winning discipline? Use a pie chart to show the country’s Olympic medals by discipline.

### Note:   
All counts are based on athletes, not events. For example, if a country wins the swimming 4X100M freestyle relay, the number of athletes who have won medals for that event is 4. The goal is to measure how many athletes performed well in the Olympics, participated in various events, and won medals in the events.  
  

## Sketches
### Part 1: Medal Map (Answering Q1). 
![image](https://user-images.githubusercontent.com/57047582/136890997-54e694de-5504-46c2-bde1-086ea42a4891.png)
The bar chart on the map shows the number of medals won by a country from 2000 to the 2014 Olympics. By sliding the bars in the bar chart below, the bar in the map will change with the year. When the mouse hovers over a country on the map, the name of the country and the number of medals won by the country will be displayed.  

### Part 2: Scatter plot: GDP vs Number of Medals (Answering Q2)![image](https://user-images.githubusercontent.com/57047582/136891150-2a1aec91-8325-4a9c-aaed-3354054fc217.png)
When the mouse hovering the points, it displays the country name.  

### Part 3: Bar plot: Best Athletes (Answering Q3)
![image](https://user-images.githubusercontent.com/57047582/136891248-24e2903b-bb31-42fe-ae19-d429bfd883ec.png)
It counts the number of medals won by athletes from 2000 to 2014. When sliding the mouse it will display this medal is awarded in which year, which event.  


### Part 4: Line Chart: Gold Medal by Country (Answering Q4)
![image](https://user-images.githubusercontent.com/57047582/137052860-673e6619-57d2-48c0-adde-239692452220.png)
Create a line chart with a menu bar. It displays the number of gold medals changed over Olympic games of one country.  


### Part 5: Pie Chart: Medal by Discipline in top 10 Countries (Answering Q5) 
![image](https://user-images.githubusercontent.com/57047582/136891351-8401b4dd-f05d-4a47-b7c4-0b2a16c8e077.png)
This is a multi-view that contains bar and pie charts. By selecting the bar chart on the LHS, the RHS pie chart shows the medal disciplines of the selected country.
  
  
## Schedule of Deliverables  
In each of the above sketches, the functions of the plot are described, which are now organized in the table below, and the date of completion of the plan and the places that need to be modified are marked.  

| Task  | Description | Delivery Date| Comment/ Modification |
| ------------- | ------------- | ------------- | ------------- |
| Part 1 Medal Map  | The bar chart on the map shows the number of medals won by a country from 2000 to the 2014 Olympics. By sliding the bars in the bar chart below, the bar in the map will change with the year. When the mouse hovers over a country on the map, the name of the country and the number of medals won by the country will be displayed.  |10/13/2021  | / |
| Part 2 Scatter plot: GDP vs Number of Medals | When the mouse hovering the points, it displays the country name.  | / (Completed)  | /|
| Part 3 Bar plot: Best Athletes |It counts the number of medals won by athletes from 2000 to 2014. When sliding the mouse it will display this medal is awarded in which year, which event. | / (Completed)  | / |
| Part 4 Line Chart: Gold Medal by Country |Create a line chart with a menu bar. It displays the number of gold medals changed over Olympic games of one country. | 10/20/2021  | Two selected menu|
| Part 4 Line Chart: Gold Medal by Country |Create a line chart with a menu bar. It displays the number of gold medals changed over Olympic games of one country. | 10/27/2021  | add animation during the change|
| Part 4 Line Chart: Gold Medal by Country |Create a line chart with a menu bar. It displays the number of gold medals changed over Olympic games of one country. | 11/03/2021  | Add points of on the plot and let the y-axis be int|
| Part 5: Pie Chart: Medal by Discipline in top 10 Countries |This is a multi-view that contains bar and pie charts. By selecting the bar chart on the LHS, the RHS pie chart shows the medal disciplines of the selected country.| 11/10/2021  | /|
| Productizing a Codebase| migrate from vizhub to github and publishing with github pages| 11/17/2021  | /|
| design a dashboard| reorganized the plots and create a dashboard for them | 11/24/2021  | /|
|make any possible changes|modify|12/01/2021|/|




## Prototypes
I’ve created a proof of concept visualization of this data.  
This scatter plot depicts the number of medals in the 2012 Summer Olympics by country/region and country/region GDP (estimated in 2015). The x-axis is GDP and the y-axis is the number of medals. This is a marked scatter plot. When the mouse hovers over the point, the country name will be displayed
There is a linear relationship between GDP and the number of medals. As GDP increases, the country tends to win more medals at the Summer Olympics.

[![image](https://user-images.githubusercontent.com/57047582/136861505-fce7a6a1-f1e4-406d-8e84-72f41540b078.png)](https://vizhub.com/RuofanChen/af53cd1647bd45ebbfd0886ad51f5e48)
    
This bar chart shows the top athletes and their medals. It's designed to emphasize the top athletes in Olympic games which data is collected by Olympic data. Each bar references an athlete. This is an interactive bar chart. When your mouse is pointed at the athlete's bar, it will display the athlete's name, the year of the medal, and the event in which the medal was awarded.  

[![image](https://user-images.githubusercontent.com/57047582/135732009-e0b53c03-3994-442e-b59e-84099494cccd.png)](https://vizhub.com/RuofanChen/80a0c887e536419fb4a98ca16fa856e2) 

This is a multiple views about number of medals by country through years. It shows the number of medals for countries from 2000 to 2014. Besides is a sliding bar. It aims to show the difference among countries in one year in graphical view and the changes in the number of medals among 14 years. 
[![image](https://user-images.githubusercontent.com/57047582/136861653-f4b00e38-1ea3-47f2-b820-073cafed722d.png)](https://vizhub.com/RuofanChen/88b446e7eebe4c82b34e8e05c943dadc)
