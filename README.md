# UFOs

## Overview of Project
Dana would like a more in-depth analysis of UFO sightings by allowing users to filter for multiple criteria, such as date, city, state, country, and shape. Goal is to add table filters for criteria other than date.
</br>
1. Deliverable 1: Filter UFO sightings using multiple criterias
2. Deliverable 2: complete written report (readme file).

## Resources
- [data file](https://github.com/MuddassirR/UFOs/blob/main/static/js/data.js)
- [data source](https://github.com/MuddassirR/UFOs/blob/main/static/js/app.js)
- [image used in html file](https://github.com/MuddassirR/UFOs/blob/main/static/images/nasa.jpg)
- [html file](https://github.com/MuddassirR/UFOs/blob/main/index.html)
- [css file](https://github.com/MuddassirR/UFOs/blob/main/static/css/style.css)
- tools used: javasScript, Bootstrap, Visual Studio Code

## Results
Our webpage has a navigation bar, page header, article title, article paragraph, filters for the table, and table of sightings data which can be seen [here](https://github.com/MuddassirR/UFOs/blob/main/static/images/html%20file.png). Someone navigating through this webpage may want to filter for UFO sightings based on criteria such as the shape of the UFO, which can be done. As shown in this [picture](https://github.com/MuddassirR/UFOs/blob/main/static/images/circlefiltered.png), you can filter UFO sightings based on the shape of the UFO, in this case 'circle', and you can combine filters as shown in this [picture](https://github.com/MuddassirR/UFOs/blob/main/static/images/circle%26state.png) which combines shape and state filters. To reset filters, you can click "Clear Table" which would erase all the filters you have written and display all the results again. 

## Summary 
One drawback of this page can be that it relies on existing data that is stored in a JS file to find UFO sightings, when there may be newer, more frequent, and important sightings that are not tracked on this webpage. One solution would be to scrape a website for data that lists daily, weekly, or monthly UFO sightings and incorporating that site's data into our webpage. Another recommendation for this project can be to include data that is outside of the US, which would help validate UFO sightings and make the filtering by country criteria usefull. 
