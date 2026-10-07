# Random Quotes OOP with API

Welcome to the Random Quotes app!
This project consists of a client-side Vanilla JavaScript app and a server-side Express Node.js app.

## Running the APP in Development Mode

### Run server

1. Navigate to the root directory of the project.
2. Open a new terminal window.
3. Change directory to the server subfolder:
   'cd server'
4. Install server dependencies by running the following command:
   npm install
5. Run server in the development mode with hot reload:
   npm run dev
6. Server will be running at the `http://localhost:3000`

### Run client

1. Open client/index.html in Visual Studio Code.
2. Right-click index.html and select Open with Live Server.
3. The client application will open in the browser.

## Running the APP in Production Mode

### Run server

1. Navigate to the root directory of the project.
2. Open a new terminal window.
3. Change directory to the server subfolder:
   'cd server'.
4. Install server dependencies by running the following command:
   'npm install'.
5. Run server in production mode:
   'npm start'.
6. Configure hosting server where you run application to forward all requests to the
   http://localhost:3000
7. Get the URL assigned to your backend API server by the hosting provider.
   For example `https://random-quotes-api.com`

### Run client

1. There is no need to build the client because it already contains HTML, CSS, and JavaScript files.
2. In client/src/config.js, replace http://localhost:3000 with the URL assigned to the server API in step 7 of the previous section.
3. Host all client files from the 'client' subfolder on the public web server.
   4.Get the URL assigned to your client frontend application by the hosting provider.
   For example `https://random-quotes-frontend.com`.
4. Open `https://random-quotes-frontend.com` in the web browser.
