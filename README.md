# PWA-Text-Editor

Deployed App: https://jate-ms.herokuapp.com/

## Description
The goal of this assignment is to create a text editor that runs within a web browser. The application can be downloaded & installed to work offline. This app meets PWA (progressive web application) criteria. 
### Installed App
![Demo of the Installed Application](./Assets/JATE_Installed_App.png)

### Service Worker
![Chrome DevTools Service Worker](./Assets/Service_Worker_Chrome-Dev.png)
### Manifest JSON
![Chrome DevTools Manifest JSON](./Assets/Manifest_JSON_Chrome-Dev.png)

## Usage
```
npm i
npm run start:dev
```
Note: this app is running on Localhost:3002

## User Store
```md
AS A developer
I WANT to create notes or code snippets with or without an internet connection
SO THAT I can reliably retrieve them for later use
```

## Acceptance Criteria
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
WHEN I deploy to Heroku
THEN I should have proper build scripts for a webpack application
``` 

## Technology Used
* JavaScript
* IndexedDB
* manifest.json

## Credit
* Starter Code provided by UofM BootCamp
* UofM Learning Assistants 
