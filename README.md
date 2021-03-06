# About the Climate Impact Map

For this final essay, the digital geography related project I have decided to analyze and write about is a web map that has been developed by the [Climate Impact Lab](http://www.impactlab.org/). The Climate Impact Lab uses a data-driven and evidence-based approach to quantify the impacts of climate change. They are a team of economists, climate scientists, data engineers, and risk analysts who are essentially creating the world’s most comprehensive research on the impacts of climate change that will help the public and decision makers to understand the risks and create policies that help lessen the impacts of climate change. 


![](map1.png)


> The map that I am focusing this essay on from the Climate Impact Lab, is the [Climate Impact Map](http://www.impactlab.org/map/#usmeas=absolute&usyear=2020-2039&gmeas=absolute&gyear=2080-2099&tab=united-states&usprob=0.95&usrcp=rcp85). The goal of this map is to show a choropleth map of the average temperatures of each state (and within each state – there is more aggregation). Some of the main functions are being able to choose which version of the map the audience wants to see and being able to choose either viewing the United States Map or the Global Map. 

> As for the different versions of the map, the creators give the choice of seeing a **historical (1981-2010) map, Next 20 Years (2020-2039) map, Mid-Century (2040-2059) map, and the End of Century (2080-2099) map.** The last three are all made through experiments that are run by global climate models to give accurate results of what the temperatures (both nationally and globally) will look like in the coming years if climate change continues to occur at the same rate as it is currently. Audience can also change the months to see average temperatures during different months in a year, and for the future projections, they can also see what happens to the average temperatures if we do change our course of action and have low emissions (just to show the positive impact of us taking action on climate change).

> As mentioned previously, the target audience for this are both the general public (who would like to get educated about the impacts of climate change and how it has and it will continue to change if no action is taken) and the authorities in both the public and private sectors (who have the power to create more environment friendly laws and changes in the system).
The Climate Impact Lab has members from University of California Berkeley, the Energy Institute at University of Chicago, among other universities. It also has afflictions with foundations like the national Science Foundation, the International; Growth Center…etc. 

> The site that hosts the map, among other information, is created by constreuctive.co. The client is my browser. The data is taken and analyzed through multiple models that are made by the climate modeling teams the Climate Impact Lab comprises of.  The data is later stored and easily accessible (as an open source form) on the web page, itself, as an excel sheet. The website also does not only comprise of this one map, it has multiple tabs (this map is one of those tabs). The map (both base and layers) is built through Climate Impact Lab, itself.  

> After inspecting the code, I found some really interesting aspects that are being used to make this website. Firstly, **HTML, CSS, and JavaScript** are being used on the front end. And I can see that depending on each average result, certain color coordinates are being given to make the map a choropleth map. They are also using **Amazon AWS** to download something called Mailchimp. On further research, I learned that Mailchimp is a marketing platform for small businesses who are looking to grow. In the code, there a **multiple polygon points** that are made to fill with certain colors. But almost every source URLs are from the Impact Lab, itself. 


![](polygon.png)


> Though I could not access the index.html file for whatever reason, it was there. They were also using bootstrap, specifically for fonts. And this project does support responsive design, meaning the web design does make the web pages render well to different devices, windows, and screen sizes. 

> The map does not have geojson files, but it does have .svg files. SVG stands for Scalable Vector Graphics. It is essentially vector-based graphics in Extensible Markup Language (XML). These are two-dimensional graphics that can support interactivity as well as animation. Apart from that, the map has multiple JavaScript and CSS files. 

> Overall, the UI/UX of this map and the web page/website as whole, is _outstanding_, in my opinion. Everything is set in the right fonts and colors. Easy for the audience to process and play around with the map without much confusing. The map, itself, is well made. With proper colors that help the audience understand the context without much confusion either. The colors are set perfect for the topic of discussion. The bluer the places, the cooler; and the more red the places, the hotter. The map, as per my taste, looks incredibly aesthetic and very educational just by looking at it. Even if someone were to not look through the background or any other information, they would understand this map at a first glance. 

> For the United States Map, the basemap is a map of the United States. For the Global Map, the basemap is a flat map of the entire world. Both basemaps are later sectioned off by a layer of the states or countries (in the global map). There is also another layer that is the actual choropleth layer; that shows the distribution of the average temperature. 

> As for interactive features, there are quite a few. For starters, if the mouse is moves along the map, each state is shown as a pop up with the average temperature of the state. In the Global Map, this is the same, but each country is shown up as a popup with the average temperature, rather than each state. There is a choice to zoom in or out of the maps. There is a choice to either see the temperatures in Fahrenheit or Celsius (making the map more globally accessible and understandable). And as stated above, the viewer can choose which years (4 options) they want to view the map in, they can choose the months, they can choose the amount of emissions they wanted to see projected, and they can choose the probability of that happening. 
As for the web map elements there is a title for the map and a legend that goes from red to blue (red being hotter and blue being cooler).


![](map3.png)



> The strengths of this project are that it is a very informative project, and it is very well and aesthetically displayed. The creators have the methodology under the map, for the audience to click and read how they approached these projections, and they have the data there for anyone to download and use. What I found fascinating about this map is that, it not only shows how the world used to be (in regard to climate change), but it also projects how the world will get towards the end of the century. And I believe these are extremely accurate projections. Another strength is the amount of interactivity this map offers the audience. We can play around with what we see, whether it’s the map of the United States or the Global Map. A weakness I see in this project is that it does not show the projections of the past ten years. There is no map that shows what happened between 2010 and 2020, and this is a little surprising to me because I truly believe these past ten years really worsened the impacts of climate change. Especially with how the government and the regulations have been for the past four years. Another weakness of this map is not having the authors or creators near the map. I could not find who created the map, I guess it was assumed that the Climate Impact Lab created it, rather than specific people. Other than those two weaknesses, I do not see much wrong or things that need to be heavily fixed in this map. 

> It is interesting to see how the average temperatures change depending on what region you live in (in both the United States Map and the Global Map). When we see the United States Map, we can see that a lot of the East Coast has higher average temperatures whereas the West Coast has lower temperatures comparatively. Though some might argue that it is because West Coast is significantly cooler than the East Coast, there are states like California that are shown cooler. This can be probably because of the digital divide as well as the types of government. States like Texas and Florida (which are recently known as republican states) show high temperatures, whereas Democratic States such as Washington, Oregon, California, and New York show cooler average temperatures. Democratic states tend me be more climate conscious, where are Republican states tend to not believe or care in the impacts of climate change. 


![](map2.png)


> Similar trend can also be seen in the Global Map, more developed countries tend to show cooler temperatures, where are third world or developing countries have hotter temperatures. This can show the impacts of industrialization and the digital divide. 

In conclusion, this map I researched and analyzed as a digital geography project, is probably one of the best interactive and educational maps I have seen. The future projects are incredible. **I only hope that people see this, educate themselves, and ask for/create rules and regulations that help reduce the impacts of climate change.** 
