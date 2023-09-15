# PowerBi
# PowerBi Experience
I created this repository to showcase my work with PowerBi.
Despite not having a job title aligned with PowerBi, I have significant experience with PowerBi.
I have created a number of dashboards over my career, however, many of them have confidential information so I am unable to showcase them.
I have remade some dashboards with dummy data to highlight the functionality of them.
I am not going to directly place them on my github, instead, I am going to provide screenshots and detail their actions on this repository.

# Power Query

Power Query is a bi tool which allows you to import data from many different sources and then clean, transform and reshape your data as needed. Here is an example of what I have used Power Query for:

![image](https://github.com/Taharqua/PowerBi/assets/56850203/124d941d-b7d6-4afd-98e6-d46eb14d64e0)

In this case, I have got a lot of data in the incorrect form.
We want to record most of the fields separately instead of as one so it is easier to group them when we get to the Power Visuals aspect.
In doing so, we split the entry into multiple entries by choosing to split by a denominator.
When this occurs, it adds spaces infront of many entries, we can room this by using the trim transformation.
Once we have done the above, we are able to remove any unneccessary entries by filtering them data and removing any null data.
These steps have been repeated multiple times as there were multiple columns that this issue occurred.

# Power Pivot (DAX)
![image](https://github.com/Taharqua/PowerBi/assets/56850203/0d9530ce-20da-4183-9da7-3fc683696d80)
![image](https://github.com/Taharqua/PowerBi/assets/56850203/435565fb-dec2-49c9-a855-56be84bababf)
![image](https://github.com/Taharqua/PowerBi/assets/56850203/377275f6-c964-4fb7-bb12-65aa5abc49f7)

# PowerBi Visuals

## Global Warming Dashboard

This dashboard was made to display global data.

The below image is a screenshots of the front cover of a dashboard.
![unnamed](https://github.com/Taharqua/PowerBi/assets/56850203/d8bf5ad5-4e98-40a1-b815-d9539cc44d43)
![unnamed](https://github.com/Taharqua/PowerBi/assets/56850203/8affba70-10e4-4642-9b37-0177e79c26b8)
![unnamed](https://github.com/Taharqua/PowerBi/assets/56850203/330fd355-8a60-48ee-af97-fb041c7361c4)

## Functionality:
## Globe
The globe moves, and is responsive. If you click on a country, it will focus on that country or if you select a continent using the menu on the left it will

## Text
The text below the menu on the left hand side of the dashboard changes as you select different countries, continents or years.

The amount of methane is 995,760.25 in the first image. In the second image you can see the change to 49,209.00 as Europe is selected.

## The Year Slider and Year Bar Chart
The slider and the bar shart allow us to filter out depending on the year. If you want it a year you place to the slider to left or the right. If there are more data points, you are able to sift through them using it.
If you do not want to use the slider, you can use the bar chart by clicking directly on a year.

## The Emissions Per Country Tab
The tab on the right shows the amount of methane per country per year on individual area charts. These charts change when selecting different regions and you are also able to scroll down and find each individual country in that region.

## Page Navigator
The tab on the top of the page which details what page we are on is called the page navigator tab. I allows easy changing when showcasing the dashboards.

# African Inflation Dashboard

This dashboard was made with data from Kaggle to show the changes of inflation over the years in certain African countries.

![image](https://github.com/Taharqua/PowerBi/assets/56850203/3dff2e7f-32d7-4578-8e98-15905341624b)
![image](https://github.com/Taharqua/PowerBi/assets/56850203/3747cf66-4578-4f58-aa59-3c018443fb7d)
![image](https://github.com/Taharqua/PowerBi/assets/56850203/e5db6f5c-6cfa-4562-9e3c-bbcc253e94e5)

## Functionality:
## Scatter Chart
The scatter chart a playable scatterchart.
In this case, that means that I can showcase each year by just pressing on the play button on the bottom left of the scatter chart. This is illustrated by the first image as you can see the play button is playing, unlike the rest of the images.
You are able to select a particular year by selecting a specific year on the timeline located below the scatter chart.

## Multiple Line Chart 
This is an overview of the annual inflation of each country over the years.

The other functions on this page are similar to the first dashboard and I will not be covering them. If you want to understand them, you can read the details on the "Global Warming Dashboard" segment.

## References:
[Global Emissions Data](https://www.kaggle.com/datasets/ashishraut64/global-methane-emissions)

[African Inflation Data](https://www.kaggle.com/datasets/chirin/africa-economic-banking-and-systemic-crisis-data)
