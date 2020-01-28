# Sendero Pacifico
My interactive web map from my 2020J-Term internship with World Trails Network in Costa Rica!

If you would like more information on WTN and the Sendero Pacifico project, please visit https://worldtrailsnetwork.org/portfolio-item/el-sendero-pacifico/ 

My larger project over my month in Costa Rica was developing the following web map, but more than that, my colleague Hannah Rigdon and I first had to sort through the mess of data we had been handed. This project is still under development and has been for many years, so many of the data were out of date, corrupt, irrelevant, or only covered the starting region of Monteverde/San Luis. There had yet to exist a full data set for trails, roads, and points of interest that spanned to the coast. 

Using GAIA GPS tracking while we hiked the entire trail network during our first week here, I was able to create my own data for the missing sections. Additionally, Hannah and I worked on created "Master Files" and layers in QGIS that combined our new data with what already existed, making sure to delete replicas and fill in missing data points in the attribute tables. While it is still not perfect, it is a start, and we wanted to leave behind a better starting point than we had been given. Our hope is that the next intern or employee can open our files and simply edit/add to what already exists, instead of recreating everything every year. 

This map represents my stylized version of the Sendero Pácifico, prioritizing the information that would be most relevant for tourists interested in visiting Costa Rica specifically for hiking. As such, it is not necessarily the most objective or accurate, but then again there exists no such thing as an entirely accurate map. While I prioritized the online map in hopes of assisting WTN's future objective of drawing tourists to the trail, Hannah worked on making print maps aimed more towards locals who are interested in the Sendero's many hiking trails. With her permission, I have also included some of her work on this page as well, as I believe it offers a deeper understanding of what we accomplished this month, and it is possible to see how two different objectives/audiences can change a map's design. 

In terms of writing the code that has produced my online map, I received the majority of it using "QGIS2Web", a QGIS plugin which converts Q projects into HTML code, using Leaflet as a platform. From there, I made the following changes: 

1. Reformatting things that did not carry over from my Q file: 
    -Roads layer (color, pattern, and size) 
    -Labels for the Towns layer 
    -colors for the trail networks
   
2. Editing pop-up information to only include relevant information. I also prioritized Spanish over English, as that is not often done and I like to challenge the Lingua Franca whenever possible :)

3. Adding tools like zoom buttons, a scale bar, the legend, and a measuring tool. 

4. Editing the Legend to condense information.

5. Adding in a feature to highlight trail sections on hover, which was largely accomplished with references and guidance from my advisor, [Joseph Holler](https://www.josephholler.com/). 

6. Reformatting the ToolTip features on the Towns layer to provide a readable label

7. Transforming the Points of Interest layer into a scale dependent layer (by far the hardest component!). This was accomplished using a variety of resources, such as Joe Holler and Stack Exchange pages such as [this one](https://gis.stackexchange.com/questions/182628/leaflet-layers-on-different-zoom-levels-how). 

Overall, I'm very proud of this map! It may not be the most complex digital map, but I was able to create a product which will help raise awareness about this incredible, grassroots hiking project, building from skills I already had to teach myself new ones. While it is often frustrating, I really enjoyed this coding experience and would love to continue learning HTML. 


Credits: 
1. [QGIS 3.8 ](https://qgis.org/en/site/)
2. ["QGIS2Web" plugin](https://github.com/tomchadwin/qgis2web)
3. [Joseph Holler](https://www.josephholler.com/)
4. [Monteverde Institute](https://monteverde-institute.org/)
5. Associación de Desarrollo Integral de San Luis 
6. [OpenStreetMaps](https://www.openstreetmap.org/)
7. [GAIA GPS](https://www.gaiagps.com/)
8. World Trails Network, Nat Scrimshaw
9. Hannah Rigdon, Middlebury College

