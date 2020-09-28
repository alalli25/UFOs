# UFOs
## Overview of the Project
### Purpose
The purpose of this analysis was to use HTML, JavaScript and CSS to build a webpage and dynamic table to provide a more in-depth analysis of UFO sightings for our client, Dana. Users are able to filter multiple parameters at the same time to fine-tune their research of UFO sightings. The data can be filtered using the following criteria:
- Date of sighting
- City of sighting
- State of sighting
- Country of sighting
- Shape of UFO

## Results
The goal of this analysis was to build a visually appealing dynamic webpage that would allow users to research  documented UFO sightings by certain search criteria. Each user is first greeted with a well organized, easy to read webpage that outlines why and how UFOs may exist. Towards the bottom of the webpage, users are able to search for specific UFO sightings using the pre-determined filtered categories. The table displays Date, City, State, Country, Shape, Duration, and Comments. When the user first accesses the webpage, there are no search parameters defined, and all data is displayed. Each filter is independent, meaning you are able to filter for one parameter, multiple, or no parameters. Once the users parameters are selected, and you select the "Filter Table" button, the table will only show data that matches you're selected criteria.

***Full Webpage:***
![](Screenshots/full_webpage.png)

### Filtering Examples
***Filter by Date:***
![](Screenshots/date_filter.png)
- Filtering by date is a helpful way to view events that happened on the same day!
- We can see above that there are three documented sightings on 1/13/2020...coincidence?!

***Filter by Multiple Parameters***
![](Screenshots/filter_multiple.png)
- By filtering for multiple parameters, we are able to address more complex questions
- It looks like California had multiple light sightings between 1/1/2020 through 1/6/2020

## Summary
This webpage is very helpful and useful for individuals looking for UFO data that can fit certain parameters. That being said there are a few drawbacks and recommendations for improvement.
### Drawbacks
The dataset used is very limited and has inconsistent formatting. The date range for this dataset is from 1/1/2010 to 1/13/2010. Ideally we would like to have a much more complete list of all global sightings. Additionally, the formatting is inconsistent. I would like to see the first letter of each city capitalized, country codes capitalized, the duration in a consistent format, and the comments cleaned of any incorrect verbiage.

***Drawbacks***
![](Screenshots/drawbacks.png)

### Enhancements
There are multiple enhancements I would like to implement in this webpage. First and foremost, I would like to gather more data and make formatting consistent. Regarding more technical enhancements, I believe we should implement he ability to search by date ranges, multiple cities, states, countries and shapes. I would also like to implement a technical enhancement using a maps API to allow users to visualize where sightings that match their search parameters are in distance to each-other. This would allow the user to gather more evidence to substantiate certain objectives.