# Progressive-Web-Applications-PWA-Text-Editor

## Table of Contents 
 * [Description](#Description)
 * [Criteria](#Criteria)
 * [Website](#Website)
 * [Installation](#Installation)
 * [Usage](#Usage)
 * [License](#License)

## Description
Built a text editor that runs in the browser. The app will be a single-page application that meets the PWA criteria. Additionally, it will feature a number of data persistence techniques that serve as redundancy in case one of the options is not supported by the browser. The application will also function offline.

<img src="./assets/TextEditorScreenShot.png" alt="Text Editor Scrren Shoot"/>

## Criteria 
```md
GIVEN a text editor web application
WHEN I open my application in my editor
THEN I should see a client server folder structure
WHEN I run `npm run start` from the root directory
THEN I find that my application should start up the backend and serve the client
WHEN I run the text editor application from my terminal
THEN I find that my JavaScript files have been bundled using webpack
WHEN I run my webpack plugins
THEN I find that I have a generated HTML file, service worker, and a manifest file
WHEN I use next-gen JavaScript in my application
THEN I find that the text editor still functions in the browser without errors
WHEN I open the text editor
THEN I find that IndexedDB has immediately created a database storage
WHEN I enter content and subsequently click off of the DOM window
THEN I find that the content in the text editor has been saved with IndexedDB
WHEN I reopen the text editor after closing it
THEN I find that the content in the text editor has been retrieved from our IndexedDB
WHEN I click on the Install button
THEN I download my web application as an icon on my desktop
WHEN I load my web application
THEN I should have a registered service worker using workbox
WHEN I register a service worker
THEN I should have my static assets pre cached upon loading along with subsequent pages and static assets
WHEN I deploy to Render
THEN I should have proper build scripts for a webpack application
```
## Website
[Click the link to the wesbsite](https://pwa-text-editor-awkt.onrender.com)

## Installation

run `npm run install` in the command line and have all of the client's dependencies installed.

run `npm run build` in the command line and have our client run the webpack build script.

## Usage 

 run `npm run start` in the command line to run our build script and start our server.

 ## License
 This project uses MIT license