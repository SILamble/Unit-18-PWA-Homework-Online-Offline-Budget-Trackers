# Unit-18-PWA-Homework-Online-Offline-Budget-Trackers

Refactoring an existing online only budget app to work offline and online.

## User Story

As a frequent traveller I need to keep on top of my budget, even when in areas with a poor internet connection. Being able to update my budget offline and have it update correctly when I have an internet connection again.

## MVP

User should be able to:
* 1) App can be taken offline
* 2) Deposits and withdrawals can be made offline
* 3) When back online the deposits and withdrawals update the database

## Process

Using provided code refactor to take offline, adding Service Worker, web-manifest & cache API:

* 1) Add Manifest file. Add link in HTML file header
* 2) Add service-worker. Add script link in HTML.
* 3) Add db.js to save to indexedDb, add link to script in HTML (before Index.js link)


### Requirements

Web manifest file
Service worker js
NPM Mongoose
NPm Express

### Screenshots

Directory Structure
![Directory Structure Screen Shot](https://github.com/SILamble/Unit-18-PWA-Homework-Online-Offline-Budget-Trackers/blob/master/public/assets/Capture001.PNG)
Live App View
![Live App View Screen Shot](https://github.com/SILamble/Unit-18-PWA-Homework-Online-Offline-Budget-Trackers/blob/master/public/assets/Capture002.PNG)
WebManifest & Service Worker In Chrome Dev Tools/Applications
![Chrome Dev Tool Screenshot of Manifest and Service-worker](https://github.com/SILamble/Unit-18-PWA-Homework-Online-Offline-Budget-Trackers/blob/master/public/assets/Capture003.PNG)
Service Worker In Chrome Dev Tools
![Chrome Dev Tool Screenshot of Service Worker](https://github.com/SILamble/Unit-18-PWA-Homework-Online-Offline-Budget-Trackers/blob/master/public/assets/Capture004.PNG)


## Deployment

Github Repo: https://github.com/SILamble/Unit-18-PWA-Homework-Online-Offline-Budget-Trackers
Heroku Deployed App: https://budget-tracker-sil2020.herokuapp.com/

## Authors

Stuart Lamble: https://github.com/SILamble
