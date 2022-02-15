## UFO Sightings

### Overview
The purpose of this project is to create a webpage with information about UFO sightings using javascript and html. The page features a news article, as well as a list of UFO sightings that can be filtered based on the user's preferences.

### Results
The page allows to filter the list of UFO sightings by date, city, state, country, and the shape of the UFO, which gives the user the ability to search for UFO sightings on a particular date, or at a specific location. In the example below the filter is set to search for sightings in the US state Arkansas.

![image](https://user-images.githubusercontent.com/93882635/154015387-22a3a53b-ef20-43f9-bf90-e72730ae6333.png)

### Summary
Although the web pages looks good, and the filters work as intended, they are not ideal. The following improvements should be considered:

1 - The date filter currently only allows the user to select one single date. It would be useful to add the ability to search for UFO sightings within a certain timeframe, by turning the single "date" field into seperate "start date" and "ending date" fields.

2 - The current filters only work if the values entered exactly match the values in the page's underlying data. The inputs are case sensitive, and need to be entered in lower case only. A search for sightings in the state "CA" will not yield any results, but a search for "ca" will. This will cause issues when a user's input does not exactly match the format our data uses. Improvements need to be made to make the inputs valid regardless of the use of capitals or lower case letters.
