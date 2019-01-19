# Swole
First Project for KU-FullStack Bootcamp - The best group.


With busy lives, it is difficult to make fitness a priority.  Through the use of wearable fitness trackers people have been able to work out "On there time."  With Step2Goal users can achieve their daily step goal, while doing something staying productive with their days tasks.

Our applicaiton is an add-on that provides an extra layer of motivation to obtain fitness goals by giving the user the ability to push themselves to meet a specified goal and stay on top of their fitness goals.  Say someone needs a gallon of milk or needs a few things from CVS or Walgreens, they can pull up the app and see how they can accomplish two things by walking there and getting the items they need. 
As an add-on app, we are providing location for the user to get those final steps in and not the whole step goal in one fell swoop.  (i.e. - our users need to have at least accomplished some steps) or this app isn't for them.

The app currently uses the Google Maps API, Fitbit API, and the FourSquare API, Firebase API, and local javascript.

Functionality that we would like to implement:
-To replace the current map on the results page and populate that map with user location data
-Adding advertisement functionality, selling user data, targeted searches and sponsored results
-Storing fitbit user data, allowing the user to login with fitbit account and have fitbit return up to date data for the user
-Add a percentage to step goal

Team Efforts
Lance created all the backend functionality, to hooking in the various APIs that have hooked in (Fitbit, Foursquare and Google Maps), to adding it to the pages to populate when the user logs in.  I pulled in the geolocation of the user based off the browser location and populated their actual address vs the lat and long of the geolocation.  The challenges that we had were not to monsterous.. we just had to figure out how to use the said APIs and their limitations.  Once figured out it was smooth sailing.  I would say the biggest hurdle was pulling in Googles API which is a very daunting task, and we only used it for directions and nothing else.
