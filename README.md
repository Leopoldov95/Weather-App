# Weather App
## Table of Contents
* [General Info](#general-info)
* [Features](#features)
* [Screenshot](#screenshot)
* [Technologies](#technologies)
* [What I Learned](#what-i-learned)


## General Info
This was a fun and challenging weather app I created using HTML, CSS, javaScript, and as well as a weather api and a map api. This app is fully responsive for desktop, tablet, and mobile viewing. The app displays the current weather of the selected city as well as a one week forecast. The app also features an autocomplete searchbar to make searching for a city a much better user experience.

## Features
I tried my best to make this into a useful and user friendly weather app. As a result the weather app has the following features:
* An autocomplete searchbar that allows you to search for any city in the world
* Current forecast data
* A one week forecast 
* A unit selector bewteen celcius and fahrenheit
* responsive for a comforatble experience on desktop, tablet, and mobile phone

## Technologies
The app was created with the following technologies
* HTML
* CSS
* javaScript
* Axios

## What I Learned
This was my larget project to date and as a result I was able to learn a lot about javaScript, handling HTTP requests, async code, and most importantly not being afraid to go into unkown and new territories of programming. I am aware that at the moment the source code is quite messy and definitely has room for refactoring.

When I first started to create this app, I had little understanding of handling requests, handling API data, and as well about asynchronous javaScript. You can view my first attempt at creating a weather app at https://weather-app-old.netlify.app/. I wasn't too happy about it, the weather API allows only for one city search at a time. Also the older weather app doesn't scale down well for mobile and tablet view.

As a result I decided to create a more ambitious weather app, one that looks nicer and that contains a autocomplete searchbar. I ended up using a seperate location API that returns multiple city results based on name and then using that data for the weather API to allow me to search for the selected city. I also added a feature that allows the user to switch between imperial and metric units without having to make a new request.
