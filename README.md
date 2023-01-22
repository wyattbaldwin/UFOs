# UFOs

## Overview
This project is focused on organizing UFO data and giving users the ability to filter the data for the first 5 columns of the table. A user interface has been implemented on the website, allowing users to see the data as it is being filtered in real-time. The project is built using JavaScript and HTML and includes a table that displays data stored in a JavaScript array. Filters are also implemented to make the table dynamic and responsive to user input. The webpage is further customized using Bootstrap to enhance its overall appearance.

## Results
In the Filter Search section of the website, there are 5 filters that are connected to the table. When the user types into the filters and presses enter, they are able to see the table with the selected filters as shown in Figure 1. Users are also able to select multiple filters at the same time as shown in Figure 2.
<img src="https://github.com/wyattbaldwin/UFOs/blob/main/Buffalo.PNG?raw=true">
Figure 1. Using the website showing only the filters for the city of buffalo and showing the dataset for the filter.

<img src="https://github.com/wyattbaldwin/UFOs/blob/main/2Filters.PNG?raw=true">
Figure 2. Using the website showing 2 filters being used for the state of florida and the shape is fireball.

## Drawbacks and Recommendations
One drawback of this new design is that if there were thousands of data for a value in the table, it would take a while to load the first filter of the table. For example, if the user wanted to filter for the city bonita and the duration of the UFO sighting, but there were a lot of sightings at bonita, it would take a while for the website to load the filter because there would be a lot to filter for.

To improve the website, the following recommendations are made:

Have a button for all of the filters, so that the user can input all the filter requirements before the website starts filtering.
Show a limited amount of data when the users first get on to the website then with the selected filters on show range of data set that the users wanted. For example: show 50 of 150 rows and the user can expand how much they want to see.
