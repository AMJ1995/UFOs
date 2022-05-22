# Project Overview

The purpose of this analysis is to help a data journalist named Dana build a website that allows the user to filter information about UFO sightings. The user is able to enter a date, city, state, country and UFO shape to narrow down specific info on UFO sightings throughout the world. Dana was provided a javascript file with all of the data on sightings (data.js), and my task was to write a javascript code (app.js) and a HTML file (index.html) that work with each other to create the desired website. Using various functions and arrow functions I was able to succeed in the creation of this website.

I began with creating a list of elements in the HTML file that will serve as the titles for the filters the user will input. These elements were embedded in list (<li>) tags and were titled date, city, state and country. All of these elements match keys in the data.js file. I then created an empty array titled "filters" to keep track of all of the elements that are changed when the user enters data. Next, I created a function that updates that filters, saves the changed element as a variable, and saves the id of the filter that was changed as a variable. The code looks like this:
  <img width="534" alt="Screen Shot 2022-05-22 at 11 43 10 AM" src="https://user-images.githubusercontent.com/100390727/169706250-cee147e0-85d5-45c0-a800-682111e6ece7.png">

  I then coded an if/else statement that analyzes whether or not a filter value was added. If so, it adds this value to the filters list. If no value was entered, it will clear the filter ffrom the filters object. A function is then called, applying the filters and rebuilding the table. This function is coded next, and is named "filterTable." I then set the filtered data to the table data, wrote a loop to go through each filter and keep any data that matches the filter values, and wrote a code to rebuild the table using the filtered data.
  An event was that attached to observe changes to each filter. The last linen of code in the app.js file builds the table when the page loads.
  
  I also created a style.css file which gives the web page a bit of style. This file adds the color of the page as well as the background image of the page. The color I chose was f7f7f7, which is the color white. This style.css file is referenced in the index.html file.
  
  Dana also wanted us to include a few paragraphs on the webpage, which are also embedded in paragraph tags in our html file.
  
# Results
  
The result was that I was able to successfully create this webpage for Dana. Upon visiting the site titled "UFO Finder," the user is greeted with the heading "The Truth is Out There." A few paragraphs describing the webpage are seen toward the top, and on the left of the page is the input field where the user is able to enter their own information to retrieve the UFO sightings that they desire. The website looks like this:
  <img width="1430" alt="Screen Shot 2022-05-22 at 11 54 15 AM" src="https://user-images.githubusercontent.com/100390727/169706603-37d97fa3-f57d-4d92-8c8c-56e350699dae.png">

Notice the filter search on the left hand side. The user of this website can click each of these input fields and type whatever they want. The result is the information on UFO sightings based on the inputs. Remember, all of this data on UFO sightings is coming from the data.js file that we were provided initially.
  
# Summary
  
All in all, this website is looking pretty stellar! One thing that should be noted is that our data only provides info from 2010. It would be nice to look at UFO sightings from the past as well, which would mean we would need a much larger data file. Here are 2 things I would add to this website if I could:
  
1. visual representations of these UFOs. It would be incredible to work with an artist who would be able to create images based on these sightings and display them accordingly.

2. information on how many people witnessed the same sighting. With many UFO sightings across the globe, there are often times more than 1 witness to a certain sighting. I wonder how many of these sightings were witnessed by more than just one person.
  
I'm glad I was able to help Dana build this webpage using Javascript and HTML. With the knowledge I gained from this project, I'm eager to put myself to th test and build many more incredible websites like this one.
