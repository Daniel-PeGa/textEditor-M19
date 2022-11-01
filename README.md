# Module 19 Text Editor

This application is just another text editor made as PWA

## Project Description

This is an installable text editor made as a Progressive Web Application which can work both on- and offline.

## Technologies Used

For this project, I used: 
* Webpack
* Express.js
* Babel
* Nodemon

## Chalenges

There is no challenge in this bootcamp so far that I have had as much of a challenge as on this one. My computer ran out of storage and couldn't run the program at the begining, so I started deleting node modules with what I am almost certain is called npm kill. Among the node modules deleted were this project's, and there were too many changes for a git commit, and from then on I struggled some more than usual. I decided to just put it all in the trash bin and basically start over, and this is the second version... and it works!!

I still have not deployed to Heroku, but at least it works lol.

## Install and run

This project is suuuuuuuper simple to make work now. Just clone it and open on VS Code. Once the project is open on VS Code, open the integrated terminal and type in the following command:
```
npm i
```
This might take some time, so please be patient. Once it's all been installed, you type in:
```
npm start
```
Wait some until you get the "Now listening on port: 3000" on the terminal, and open Google Chrome localhost:3000 and watch the majic at work.

## User Story

AS A developer
I WANT to create notes or code snippets with or without an internet connection
SO THAT I can reliably retrieve them for later use

## Acceptance Criteria

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
