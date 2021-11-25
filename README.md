# budget-tracker

Link to deployed website: https://dq-budget-tracker.herokuapp.com/

The Budget Tracker project is a app that has been refactored to be a Progressive Web App (PWA) allowing for offline functionality. The app uses a number of technologies including Express, IndexedDB, Mongoose, and a service worker. The app was reconfigured to use IndexedDB to allow users to input data while offline that gets collected by IndexedDB in the browser. Once the app is back online, the database is updated with data that was input while offline. The PWA also has a service worker to allow for the app to continue to display information even while the internet connection is disrupted since the app files are cached allowing the app to continue to run. To run the app, you can use the commands npm install and npm start.

Screenshot of Budget Tracker app:

![image](https://user-images.githubusercontent.com/82297346/143393277-1d5b1856-13ca-4730-9a95-84ae926c7064.png)
