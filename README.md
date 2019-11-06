# Code301 Lab07 - APIs

**Author**: Holly Davis and Natalie Alway
**Version**: 1.2.0
<!-- (increment the patch/fix version number if you make more commits past your first submission) -->

## Overview
Create a node.js server that connects to APIs that provide weather, events, restaurants, and movie showing information to the City Explorer site. 

<!-- Provide a high level overview of what this application is and why you are building it, beyond the fact that it's an assignment for this class. (i.e. What's your problem domain?) -->

## Getting Started
<!-- What are the steps that a user must take in order to build this app on their own machine and get it running? -->
1. Fork this repository
2. Clone it to your computer
3. In your command line: $ touch .env
4. Add the following to your .env file and save
PORT = 3000
GEOCODE_API_KEY = "[your api goes here]"
WEATHER_API_KEY = "[your api goes here]"
EVENT_API_KEY = "[your api goes here]"
5. Confirm that node is installed: $ node -v (if not installed, do so)
6. To start your server: $ nodemon
7. Go to city-explorer-code301.netlify.com and enter "http://localhost:3000" in the field. Search for a city and you should see the location and weather information. 

## Architecture
<!-- Provide a detailed description of the application design. What technologies (languages, libraries, etc) you're using, and any other relevant design information. -->

This is a Node.js server that uses express, dotenv, and cors packages. The server currently references two json data files in order to provide information to the client. 

## Change Log

11-06-2019 09:05 AM - application provides properly formatted data

11-06-2019 09:45 AM - location name entry working

11-06-2019 09:55 AM - weather information for location showing

11-06-2019 10:50 AM - events JavaScript in place


<!-- Use this area to document the iterative changes made to your application as each feature is successfully implemented. Use time stamps. Here's an examples:

01-01-2001 4:59pm - Application now has a fully-functional express server, with a GET route for the location resource.-->

## Credits and Collaborations
<!-- Give credit (and a link) to other people or resources that helped you build this application. -->
Felipe Delatorre for date part of the Event constructor function 
https://github.com/felipedelatorre/lab-07-back-end/blob/master/server.js

Number and name of feature: Feature #1 Data formatting
Estimate of time needed to complete: 15 minutes
Start time: 09:00 AM
Finish time: 09:05 AM
Actual time needed to complete: 5 minutes

Number and name of feature: Feature #2 Locations
Estimate of time needed to complete: 15 minutes
Start time: 09:15 AM
Finish time: 09:45 AM
Actual time needed to complete: 30 minutes (in order to troubleshoot heroku key issue)


Number and name of feature: Feature #3 Weather
Estimate of time needed to complete: 10 minutes
Start time: 09:50 AM
Finish time: 09:55 AM
Actual time needed to complete: 5 minutes


Number and name of feature: Feature #4 Eventbrite
Estimate of time needed to complete: 30 minutes
Start time: 10:00 AM
Finish time: 10:50 AM
Actual time needed to complete: Not complete (having url issues)