# UFOs

## Project Overview
In this module, we're using JavaScript to build a dynamic webpage to display UFO sightings.  We will create a HTML form to let users filter UFO data based on their search criteria.

### Resources
- Source Files: [data.js](/static/js/data.js), [nasa.jpg](/static/images/nasa.jpg)
- Result Files: [app.js](/static/js/ap.js), [index.html](index.html),[style.css](/static/css/style.css),[search_results.png](/static/images/search_results.png)
- Software: HTML, JavaScript, Bootstrap, CSS

## Results
Users can filter on our UFO data based on sighting date, city, state, country and shape. Once the user enter a criteria, our table to the right of the form will automatically update based on the filter criteria(s). Please refer to [search_results.png](/static/images/search_results.png) to see this in action.

## Summary
One shortfall of our current design is case sensitivity. User must enter the data exactly in the same case as we stored the data. In the future, we should consider either removing case sensitivity in our form or adding drop-downs instead of text boxes for our search criteria. That way, users won't have to worry about spelling certain criterias exactly as we have stored them in our data file.