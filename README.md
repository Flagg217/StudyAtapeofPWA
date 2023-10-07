# StudyAtapeofPWA


## Overview

This is a text editor web application that uses IndexedDB for local storage and a service worker to provide offline functionality. The application is bundled using webpack and can be deployed to Heroku.


## Requirements

-Node.js
-Webpack
-Workbox


## Installation

Clone the repository to your local machine.
Install the required dependencies:
npm install


## Usage

To start the application, run the following command from the root directory:

npm run start

This will start the backend and serve the client. You can then open the application in your web browser.

To bundle the JavaScript files, run the following command:

npm run build

This will generate a bundled JavaScript file in the client/dist directory.

To deploy the application to Heroku, run the following command:

heroku deploy

# Features

Offline functionality
Local storage using IndexedDB
Bundled using webpack
Deployed to Heroku
Usage Examples
The following table provides examples of how to use the text editor web application:

Task	Example
Open the text editor	Open the application in your web browser.
Save content	Enter content in the text editor and click off of the DOM window. The content will be saved using IndexedDB.
Retrieve content	Reopen the text editor and the content will be retrieved from IndexedDB.
Install the application as a Progressive Web App (PWA)	Click on the Install button to download the application icon to your desktop.
Use the application offline	Open the application in your web browser even if you are not connected to the internet. The application will still work.
Next-Gen JavaScript Support
The text editor web application supports next-gen JavaScript features such as async/await and arrow functions. You can use these features in your application without any errors.

Deployment to Heroku
To deploy the application to Heroku, run the following command from the root directory:

heroku deploy
Heroku will build and deploy the application. Once the deployment is complete, you can open the application in your web browser by visiting the Heroku URL.

Build Scripts
The application includes build scripts for a webpack application. These scripts can be used to bundle the JavaScript files and deploy the application to Heroku.

To bundle the JavaScript files, run the following command:

npm run build
This will generate a bundled JavaScript file in the client/dist directory.

To deploy the application to Heroku, run the following command:

heroku deploy
Heroku will build and deploy the application. Once the deployment is complete, you can open the application in your web browser by visiting the Heroku URL.