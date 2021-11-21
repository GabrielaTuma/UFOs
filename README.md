# UFOs
Module 11 - JavaScript 

## Project Overview

Create an interactive webpage using Bootstrap that allows readers to parse the data around UFO sightings. Essentially the projects involves two parts: the webpage that will allow users to view the data (HTML) and a dynamic table that will present it (JavaScript). To allow users to interact with the visualizations the table needs to be equipped with several fully functional filters: 

- City
- State
- Country
- Shape

#### Deliverable 1
- [x] 1. The list element that creates the button is removed, and there are five list elements for filtering in the index.html file
- [x] 2. The event listener is modified to detect changes to each filter in the app.js file
- [x] 3. The updateFilters() function saves the element, value, and the id of the filter that was changed
- [x] 4. The filterTable() function loops through all of the filters and keeps any data that matches the filter values
- [x] 5. The webpage filters the table correctly based on user input


[index.html file](https://github.com/GabrielaTuma/UFOs/blob/e25be8501417a5885fe98ce2d5ea6f21d4a86642/index.html) 

[app.js file](https://github.com/GabrielaTuma/UFOs/blob/e25be8501417a5885fe98ce2d5ea6f21d4a86642/static/js/app.js) 

[data.js file](https://github.com/GabrielaTuma/UFOs/blob/e25be8501417a5885fe98ce2d5ea6f21d4a86642/static/js/data.js) 


#### Deliverable 2
Formating:
- [x] 1. There is a title, and there are multiple paragraphs
- [x] 2. Each paragraph has a heading
- [x] 3. There are subheadings to break up text
- [x] 4. Images are formatted and displayed where appropriate

Analysis:
- [x] 5. The purpose is well defined
- [x] 6. There is a description of how to perform a search, with images
- [x] 7. The summary addresses one drawback of this webpage
- [x] 8. The summary addresses two additional recommendations for further development


### Resources 

- Visual Studio Code 1.58.1, HTML, JavaScript (D3), Bootstrap


## Results 

By following the steps from module 11 a website was created using a dataset with UFO sightings information. The main page of the interactive website looks like this: 

<p align="center">
<kbd>
  <img src="https://github.com/GabrielaTuma/UFOs/blob/ff8c3bfd092ae4788aaf4ffc7c032b5bba6cd965/Resources/Main%20Page.png">
</kbd>  &nbsp;
</p>

Also during module 11, a filter was created to look for sightings from specific dates. During this challenge the filter was improved so that users can also select sightings choosing city, state, country and shape. 

<p align="center">
<kbd>
  <img src="https://github.com/GabrielaTuma/UFOs/blob/ff8c3bfd092ae4788aaf4ffc7c032b5bba6cd965/Resources/Filter%20Search.png">
</kbd>  &nbsp;
</p>

One or multiple filter slots can be filled to generate a result table. The filter is applied as soon as the user clicks anywhere on the screen after filling the slot(s), there's no button to filter the data. As an example we will use date: 1/9/2010, country: US and shape: light to generate a new table. 

<p align="center">
<kbd>
  <img src="https://github.com/GabrielaTuma/UFOs/blob/ff8c3bfd092ae4788aaf4ffc7c032b5bba6cd965/Resources/Example%20Filter.png">
</kbd>  &nbsp;
</p>

After filling the slots for date, country and shape we can see four results that match the chosen filters:

<p align="center">
<kbd>
  <img src="https://github.com/GabrielaTuma/UFOs/blob/ff8c3bfd092ae4788aaf4ffc7c032b5bba6cd965/Resources/Example%20Table.png">
</kbd>  &nbsp;
</p>



## Summary

Results: Describe to Dana how someone might use the new webpage by walking her through the process of using the search criteria. Use images of your webpage during the filtering process to support your explanation.
Summary: In a summary statement, describe one drawback of this new design and two recommendations for further development.

The filters will refresh the table as soon as the user fills one or multiple filter fields and clicks anywhere on the screen.

The webpage serves as a UFO sightings data exploration tool that is simple and easy to use. A drawback of the suggested design is that no data aggregation is available and it is difficult to easily understand for example which US city/state has accumulated the most UFO sightings.

Main drawback The data available in the website is quite putdated 

