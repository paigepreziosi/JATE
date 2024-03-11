# JATE

## Table of Contents
1. Project Description
2. User Story
3. Acceptance Critera
4. Programs Used
5. Installation
6. Credits
7. License
8. Contact

## 1. Project Description
This is a text editor that runs in the browser. It is capable of storing text in a database and retrieving it from the database. It is also capable of storing text in a local file system. 

## 2. User Story
- AS A developer
- I WANT to create notes or code snippets with or without an internet connection
- SO THAT I can reliably retrieve them for later use

## 3. Acceptance Criteria
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
-THEN I should have my static assets pre cached upon loading along with subsequent pages and static assets
- WHEN I deploy to Render
- THEN I should have proper build scripts for a webpack application



## 4. Programs Used
1. Node.js
2. Inquirer
3. mySQL

## 5. Installation
1. Clone the repository: "git@github.com:paigepreziosi/JATE.git"
2. Open the terminal
3. Run the following command "npm install"
4. Run the following command "npm run start"
5. Open the browser and go to "localhost:3000"

## Credits

N/A

## License

N/A

## Contact

Name: Paige Preziosi
E-mail: PVPreziosi@hotmail.com
GitHub: https://github.com/paigepreziosi
