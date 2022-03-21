# UFOs

## Overview

We were tasked with building a webpage and dynamic table with UFO data for Dana. She’d like to provide a more in-depth analysis of UFO sightings by allowing users to filter for multiple criteria at the same time. In addition to the date, we added table filters for the city, state, country, and shape.

## Resources

Created a Flask app on UFO data.

- Python 3.9.7
- VS Code 1.65.2
- Jupyter Notebook 6.4.8
- Mongo DB 5.0.6
- Javascript
- Bootstrap
- D3

## Results

### How to use the webpage:

This webpage can be used to filter UFO data based on Data, City, State, Country, and Shape. The fields contain an example of what you can search for, and as long as they enter the criteria the correct way a table will display all UFO events that happen in the specified field. The table updates without the need to use a button so it is very easy to use. 

- The webpage introduction can be seen below:

![image](https://user-images.githubusercontent.com/96445453/159201891-ee0ec83a-1390-4418-a13e-e24447d73acb.png)

- The search table follows the intro:

![image](https://user-images.githubusercontent.com/96445453/159201950-dc198904-538a-4324-958f-b876b95f771e.png)

## Summary

The data can be searched with individual search critera or the results can be further narrowed down by inputing mutliple search fields. Another feature of the search is it shows which previous inputs have been used upon user click in the search fields.

### Improvements

There are a few improvements that can help to make the webpage more user friendly.

- Users may like a "search" button and perhaps a "reset table" function. This would minimize confusion on wether or not they think the table was updated.
- With the shapes filter there are a lot of results on the page. A filter to sort by alphabetical by city or state would be helpful.
- A duration filter with a few bins with incrimental minutes. If people want to look at how different UFO encounters are affected by time.
