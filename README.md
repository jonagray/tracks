# React Native Application
Small learning app that runs on expo - allows you to create "tracks" on a map of where you have traveled. However, you must replace the incoming location data with real-time data - it currently comes from mock numbers located in _mockLocation.js.

## Starting Instructions

* Run `npm start` in the main directory to get the react server going
* cd into track-server and run `npm run dev`
* In main directory, run command `ngrok http 3000`
* Replace baseURL string from line 5 of tracker.js with the new ngrok forwarding link (http, NOT https)
* Ensure your IP address is whitelisted on MongoDB cloud atlas website