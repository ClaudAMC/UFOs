# UFOs

## Overview of Project

Dana, a data journalist, has chosen to write about UFO sightings. We built a table using data stored in a JavaScript array and created filters so it would be dynamic and respond to user input. The first filter we included was a date filter however Dana would like to provide a more in depth analysis by allowing multiple filters to be used by users. 

### Purpose

The purpose of this analysis is to build a dynamic table from data stored in a JavaScript array and provide filters for the date, city, state, country, and shape that allow analysis of the data through user input.

## Results

The Javascript array storing the data can be found in the file below:

[data.js](https://github.com/ClaudAMC/UFOs/blob/main/static/js/data.js)

The Javascript file housing our analysis; where we built the table and filters can be found below:

[app.js](https://github.com/ClaudAMC/UFOs/blob/main/static/js/app.js)

The HTML and CSS file housing the styling can be found in the files bnelow, respectively:

[index.html](https://github.com/ClaudAMC/UFOs/blob/main/index.html)

[style.css](https://github.com/ClaudAMC/UFOs/blob/main/static/css/style.css)

## Analysis

### Using the Filters:

1. The Date Filter

On the left side of the webpage we can see the list of filters. The first filter is the date filter. The format of the date filter is d/mm/yyyy. Once you enter a date in the filter and press enter the change is detected and the table on the right will update accordingly. In the image below we can see an example of this filtering; the date that was inputed was 1/13/2010 and 3 entries were returned.

![Date Filter.PNG](https://github.com/ClaudAMC/UFOs/blob/main/static/images/Date%20Filter.PNG)

2. The City Filter

Below the date filter we can see the city filter. Here we can enter the city of choice to show if and which sightings have occured in that area. As show in the image below when a city is entered the table will update. In the image we filtered for sightings in the city of benton; we can see that there is one data entry for that city which is then shown on the table.

![City Filter.PNG](https://github.com/ClaudAMC/UFOs/blob/main/static/images/City%20Filter.PNG)

3. The State Filter

Below the city filter is that state filter. Here we can enter the abbreviation of the state to find the data entries for that region. As show in the example we can enter the desired state by its abbreviation and the table will be updated. In the example we entered 'ar' as refering to arkansas. From this we see that 3 sightings are returned all of which occured in the state of arkansas.

![State Filter.PNG](https://github.com/ClaudAMC/UFOs/blob/main/static/images/State%20Filter.PNG)

4. The Country Filter

Below the state filter is the country filter. In the example below we entered 'us' as the filter for country. This will show all the data avaliable as the data only has entriesd for the US.

![Country Filter.PNG](https://github.com/ClaudAMC/UFOs/blob/main/static/images/Country%20Filter.PNG)

5. The Shape Filter

Below the state filter is the shape filter. Here the shape characterizing the sighting could be used to filter the data, for example, in the image below the circle shape is used to filter the data - using this filter results in 4 entires in the updated table.

![Shape Filter.PNG](https://github.com/ClaudAMC/UFOs/blob/main/static/images/Shape%20Filter.PNG)

## Summary

A drawback of this design is that the user has to have some idea of the avaliable data; if the user is not familiar with the data then they may spend a long time playing with the filters to realize there is no information for that location or for that type of sighting characterization. This can be a frustrating way to search for results unless you are sure that your search will have data behind it. This might also just be a drawback of the size of the dataset; a larger dataset may provide more options for users unfamiliar with the avaliable data.

A recommendation for further development and a way to counter the aformentioned drawback would be to use drop down filters that displays the avaliable data filters; this would make it easier to search through the data without needing to know what data is avaliable. 

A second recommendation for this analysis would be to make the filtering live (where the table updates as the information is input into the search bar) and not based on a change in the filter search bars; this along with live dropdowns on those filters would make looking through the data much easier. 
