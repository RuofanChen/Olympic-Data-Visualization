# Olympic Data Visualization
## Data 

The data I propose to visualize for my project is the Olympic dataset. It is extracted the Olympic Games and medal data on [kaggle](https://www.kaggle.com/the-guardian/olympic-games) from 2000 to 2014. This dataset includes a row for every Olympic athlete that has won a medal since the year 2000. It contains 12 columns, namely Year, City, Sport, Discipline, Athlete, Gender, Event, Medal, Season, Country, 2015Population, 2015GDP.per.Capita.

The [olympic dataset](https://gist.github.com/RuofanChen/b8ab70bdb93f363cf55e6390ad39805b) used for this project is posted on github gist. 

Features of the data:
* Year (quantitative): The year the medal was awarded
* City (qualitative): The host city of the Olympic Games
* Sports (qualitative): In which sport was the medals awarded
* Subject (qualitative): In which discipline the medal was awarded
* Athlete (qualitative): The name of the athlete
* Gender (qualitative): The gender of the athlete
* Event (qualitative): In which event the medal was won
* Medals (qualitative): The type (gold, silver or bronze) of medals awarded
* Season (qualitative): The season of the Olympic Games
* Country (qualitative): The country to which the athlete belongs
* 2015Population (quantitative): The 2015 population of the country where the athlete belongs
* GDP per capita in 2015. (Quantitative): 2015 GDP per capita of the country where the athlete belongs


## Questions & Tasks
The following tasks and questions will drive the visualization and interaction decisions for this project:  


* Do most countries perform differently in the Winter Olympics and the Summer Olympics? Use a map to display the number of medals won by each country. According to the year and the type of Olympic Games (optional in winter and summer).
* How does GDP affect a country's performance? Use GDP and population data from 2015.
* Wants to see the athlete with the most medals? Use a bar chart to show the total number of medals, type of medals, the year of the medal and the event in which the medal was awarded.
* Does the number of gold medals in a country changes over time? Can we see the trend?
* What about the country’s medal-winning project? Use a pie chart to show the country’s recent two Olympic medals.

## Note: All counts are based on athletes, not events. For example, if a country wins the swimming 4X100M freestyle relay, the number of athletes who have won medals for that event is 4. The goal is to measure how many athletes performed well in the Olympics, participated in various events, and won medals in the events.  
  

## Sketches
![image](https://user-images.githubusercontent.com/57047582/134278848-6efd0612-9cad-4d9f-86be-19c21ebfd8ae.png)
![image](https://user-images.githubusercontent.com/57047582/134278407-43866c07-5215-45ed-b64e-9c8d10fbb1a0.png)



## Prototypes
I’ve created a proof of concept visualization of this data.  
This scatter plot describes 2012 summer olympic games medal count by country and the country's GDP(2015 estimated). x-axis is gdp y-axis is the number of medals. This is a marked scatter plot. When the mouse is hovering over the point, the country name will be displayed
There is a linear relationship between GDP and the number of medals. As GDP increases, the country tends to win more medals at the summer Olympics.  

[![image](https://user-images.githubusercontent.com/57047582/134273629-f4adb498-2362-47d5-a815-6ff1549d15b2.png)](https://vizhub.com/RuofanChen/af53cd1647bd45ebbfd0886ad51f5e48)
    
 
This bar chart shows the top athletes and their medals. This is an interactive bar chart. When your mouse is pointed at the athlete's bar, it will display the athlete's name, the year of the medal and the event in which the medal was awarded.  

[![image](https://user-images.githubusercontent.com/57047582/135732009-e0b53c03-3994-442e-b59e-84099494cccd.png)](https://vizhub.com/RuofanChen/80a0c887e536419fb4a98ca16fa856e2)
  
We can select country to see the number of gold medals changes by year. 
[![image](https://user-images.githubusercontent.com/57047582/134279155-c0ad0bdf-b212-4f86-a703-160fce094ad9.png)](https://vizhub.com/RuofanChen/870734f4b8764c58a70833aed27a857d) 
  
It's an interactive piechart with bar chart. It displays medals by discipline of the country.
[![image](https://user-images.githubusercontent.com/57047582/135737129-f06d2819-f9c4-4cd0-a032-e15273606553.png)](https://vizhub.com/RuofanChen/256b09a931664cb5bf9c6eb1f317a357?edit=files)
