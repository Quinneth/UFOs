# UFOs
## Overview: 
Create a dynamic website for analyzing UFO sightings that incorporates fully functional filters to interact with a table visualization. 
## Purpose:
HTML and JavaScript were are to create a dynamic webpage for users to filter sightings using criteria such as date, city, state, county, or shape. 
The webpage is customized using Bootstrap to provide an appealing frontend framework. <br>

To organize and focus the development of the webpage, the storyboard method was used to determine layout. The data is stored into a table using a Javascript array. A search feature is incorporated to store user input. An event listener detects changes to input elements on the HTML page then calls an update function. The update function selects all the elements that changed, storing the value and id. For each key and value that is stored, the function will filter the table as indicated by the search parameters. The webpage is further customized using Bootstrap.

## Results: 
The resulting webpage is visually appealing and has an eye-catching title. After a description of the webpage content, a table is presented with a search field to the left. The tables columns are:  date, city, state, county, shape, duration, and comments. The user is able to filter the table using the one or more search fields. The user simply enters a date, city, state, county, or shape to display the desired results. <br>
### Example 1:  
Search by ***state only***!
![Single Filter](https://github.com/Quinneth/UFOs/blob/main/Static/images/fliter_by_state.png)
### Example 2:  
Search by ***city & shape***
![Multifilter](https://github.com/Quinneth/UFOs/blob/main/Static/images/filter_by_city:shape.png)
## Summary: 
- Drawback of this webpage: 
The manual process of updating the table's data is one drawback to this webpage.

- Two additional recommendations for further development:
1. Scraping an API would turn the manual data entry process into an automatic one.
2. The user might benefit from using and interactive map in addition to the table. 
