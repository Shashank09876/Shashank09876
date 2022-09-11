
The solution is based on HTML pages, JavaSript & css.

As per requirement, It should able to load the JSON data and provided feasibility to below :

1. As a user I'd like to be able to view the locations of the company plotted onto a map and then be able to tap/click on those points to see more detail about the company.

2. As a user I'd lke to be able to see the companies in a table and be able to filter on the fees and sector.

In current application folder 'TestProject' , it includes :
1. Index.html - Main file to navigate to above two requirements.
2. ShowList.html - It loads the JSON data into a table and provide a filter option.
3. myfilter.js - JavaScript functions for loading filters on column 'Sector' & 'Fees' and implements Table   filter.
4. Map.html - It loads JSON file and create marker on Google Map JavaScript API.
5. jData.json - Sample data to demonstrate the functionality. 

Fetch API is used to load the JSON file in async/await mode.
Google Map JavaScript API is used for showing the Logitude and Latitude. 