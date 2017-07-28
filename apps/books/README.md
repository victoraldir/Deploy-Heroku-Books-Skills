# Instructions

1. Clone the repository for alexa-app-server to your PC, located at https://github.com/matt-kruse/alexa-app-server

2. Copy index.js and package.json to the folder "alexa-app-server/examples/apps/books"

3. Edit index.js and set your Goodreads.com API key in the string at the top.
   You can obtain a developer API key at https://www.goodreads.com/api

4. In the console, change directories to the root alexa-app-server folder and run the command "npm install".

5. In the console, change directories to "alexa-app-server/examples" and run the command "node server".

6. Launch your web browser to http://localhost:8080/alexa/books and use the debugger UI to run "LaunchRequest" and "IntentRequest" calls.

## To run chatskills

1. Copy index.js and package.json to a folder on your PC.

2. Edit index.js and set your Goodreads.com API key in the string at the top.
   You can obtain a developer API key at https://www.goodreads.com/api

3. In the console, run the command "npm install" to download dependencies.

4. In the console, run the command "node index" to launch the skill.

5. You can get a book by typing "get book alice in wonderland", or ask for a rating by typing "what is the rating?".
