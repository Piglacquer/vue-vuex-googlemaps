# Vue-google-maps
This project is a basic setup to get Google maps running in a Vue project using VueX. The mutations and actions are all occurring in the store!

The goal is to show ```A:``` a way to get the google maps api running with vue and vuex, and ```B:``` to show a pattern to pass around actions, mutations, and data using vuex.

## Project setup
- You'll need to acquire an api key for the google maps API, you can do that by logging into google, and going to the developer section.
  - For this project to work, you need to enable the google maps api, the geolocation api, and the places api. (I might have forgotten one)
- Once you've done this, make a ```.env``` file and make a variable in there called ```VUE_APP_GOOGLE_MAPS_KEY```, set it equal to your api key, no quotes.
- That should enable your app to make the calls it needs to!
- Go ahead and ```npm install``` to get your dependencies installed.
- Then you should be able to hit ```npm run serve``` to run it!
