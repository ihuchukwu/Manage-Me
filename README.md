# Manage Me

A fast interactive personal or event management calendar with fullcalendar libraries being incorporated into Ruby on rails Application and creating events using unobtrusive javascript.

# Getting Started
With a procedural rule of thumb, the calendar process flow was practically arranged to be interactive. These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

# Prerequisites

You need to install the the foolowing software on your machine
* a text editor (e.g. atom)
* an internet browser
* a git bash (for window users) or terminal
* ruby gems

# Arrangements
1. All site-wide scripts and the corresponding pre-defined styling
   app/assets/javascripts & stylesheets folders

2. All external libraries and plugins for javascripts, jQuery, and stylesheets are inside the vendor folder
   * Full calendar libraries
   * Daterangepickers
   * moment.js
   * bootstrap sprockets

3. Framework is on Rails Assets Pipeline which combined them all in one minimized file
   i.e. application.js
   
4. All the scripts are listed in
   app/assets/javascripts/application.js manifest
   
# Deployment
The Manage-Me app is deployed in hosting server heroku
