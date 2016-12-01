# Ride
Ride is a ride share application to help college students communiting between campus and home. This applicaiton is developed using HTML, Bootstrap CSS, JQuery for front-end, and Node.js, Mongo Database for backend. The prototype version is hosted using Heroku App Service

# Getting Started
To use Ride, simply go to http://rideordrive.herokuapp.com/
Login with your Google account.
That's it!

# Technical/Development Summary
HTML(ejs) - Template for each page of the application.

Bootstrap CSS - Adopting a Twitter styled layout for front end display.

JQuery - Dynamically allocate user data and ride group data from Mongo back-end to client-side HTML(ejs) template. Check validity of user input while creating a ride group. Display feedback message after user performs an action for better UX.

Node.js - Connecting client-side data to server-side and database. Route files  used to direct user's GET request to corresponding page. Controllers used to pass information from server-side to client side HTML(ejs) template. Npm session used to store current, logged-in client information to be used throughout the app.

Mongoose - Create schema for user and ride group information to be stored into MongoDB back-end.

MongoDB - JSON database used to store user and ride group information.

Google Map API - Creating a group by allowing user to specify a pickup and drop off location using Google Map's GeoSearch function. Displaying ride group's pickup and dropoff location to better user experience.

Firebase Google Authentication - Verification and retrieval of user identity upon log in. 
