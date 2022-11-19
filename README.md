# UFO

## Overview

A webpage was created to contain a database of UFO sightings. The table is fitted with multiple filters that facilitate retrieval of specific events and allow Citizen-scientists to analyze the data and further the field of UFO research.

## Results

When you first encounter the page you see the title UFO Sightings at the top left corner of the page followed by a banner and an overview paragraph describing the purpose of the page. Then you can see side by side the full data content highlighted by the arrow and the filter options highlighted with the curly bracket and arrow. 

[Main View](01_main-view.PNG)

![Main View]( https://github.com/coralrofa/UFO/blob/main/Resources/01_main_view.png)

### Filtering Data

The data table contains 7 types of data: the date of sighting, the city, state and country the sighting took place, the shape and duration of sighting and any additional details provided under the comment’s column. The page is fitted with 5 filter options: Date, City, State, Country and Shape. These filters allow to select the desired subset of data. 

[Filter Options](02_filter_oprions.PNG)

![Filter Options]( https://github.com/coralrofa/UFO/blob/main/Resources/02_filter_options.PNG)

The filter fields display an example of the format for the data contained under that column. If we wanted to see only the sightings that occurred on 11/13/2010 we would go to the “Enter date” filter field highlighted, enter ‘1/13/2010” and hit enter. The table wil display data collected on 1/13/2010 only. 

[Filter by Date]( 03_date_filter.PNG)

![Filter by Date]( https://github.com/coralrofa/UFO/blob/main/Resources/03_date_filter.PNG)

If we wanted to change the filter parameter, the page is set up to clear the previous filter setting once a new search criteria is entered. For example, if we now wanted to see the sightings recorded for the state of Oregon,  we can type OR in the “Enter State” filter field and it will automatically remove the date filter and return the sightings data for the state of Oregon. 

[Filter by State](04_state_filter.PNG)

![Filter by State]( https://github.com/coralrofa/UFO/blob/main/Resources/04_state_filter.png)

## Summary

This set up presents a few drawbacks that can be addressed with further development: 

1) The filter set up only allows filter for a single category at a time. This does not represent a major issue because of the relatively small size of this database but would limit the search resolution for larger data sets.  

2) The comment column cannot be searched/filtered for specific content. Allowing search of the comment’s column could facilitate capturing details of the sightings.

3) The data is limited to what is contained in the in the data.js file therefore sightings must be manually logged to that file for the data to be available for use.  The code should be updated to allow real time update of the recorded sightings.  
