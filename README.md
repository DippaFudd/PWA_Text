## PWA Text Editor
Welcome to the Text Editor PWA! This is a Progressive Web Application designed to help you create, edit, and store notes or code snippets, whether you're online or offline. With robust data persistence, automatic saving, and offline functionality, this app ensures you can always access and work with your content no matter where you are or what your connection is like.

## Description
This project is a text editor web application built as a Progressive Web Application (PWA). The app allows users to create and store notes or code snippets that can be accessed offline and function even without an internet connection. It uses IndexedDB for data persistence and incorporates service workers, allowing for caching and offline functionality.

## User Story
- AS A developer
- I WANT to create notes or code snippets with or without an internet connection
- SO THAT I can reliably retrieve them for later use

## Acceptance Criteria
- GIVEN a text editor web application
- WHEN I open my application in my editor
- THEN I should see a client server folder structure
- WHEN I run `npm run start` from the root directory
- THEN I find that my application should start up the backend and serve the client
- WHEN I run the text editor application from my terminal
- THEN I find that my JavaScript files have been bundled using webpack
- WHEN I run my webpack plugins
- THEN I find that I have a generated HTML file, service worker, and a manifest file
- WHEN I use next-gen JavaScript in my application
- THEN I find that the text editor still functions in the browser without errors
- WHEN I open the text editor
- THEN I find that IndexedDB has immediately created a database storage
- WHEN I enter content and subsequently click off of the DOM window
- THEN I find that the content in the text editor has been saved with IndexedDB
- WHEN I reopen the text editor after closing it
- THEN I find that the content in the text editor has been retrieved from our IndexedDB
- WHEN I click on the Install button
- THEN I download my web application as an icon on my desktop
- WHEN I load my web application
- THEN I should have a registered service worker using workbox
- WHEN I register a service worker
- THEN I should have my static assets pre cached upon loading along with subsequent pages and static assets
- WHEN I deploy to Render
- THEN I should have proper build scripts for a webpack application

## Installation
Clone the repository:


Clone repo
- 1.git clone (Repo)

- 2.cd (Repo)

- 3 .bash
npm install

- 4.bash
npm run start
The app will now be available at http://localhost:3000 (or the port specified by your development environment).


## Screenshots
![Image Alt](https://github.com/DippaFudd/PWA_Text/blob/733508714011aa97e6e9fbee1a4612681a022a00/2025-03-27%20(4).png)
![Image Alt](https://github.com/DippaFudd/PWA_Text/blob/733508714011aa97e6e9fbee1a4612681a022a00/2025-03-27%20(5).png)

