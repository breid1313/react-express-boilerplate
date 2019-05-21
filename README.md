# Overview
This repository consists of a frontend built using `create-react-app` served by an Express application. This boilerplate is a great starting point for building more complex applications. In this simple example, the React application makes a call back to the react app using the `fetch` library, and the response is displayed as a `<p>` element on the splash page. You'll find the frontend files under the client directory and the Express files under the api directory.

## Getting Started
With a few commands, you'll be able to get your boilerplate application up and running in no time. Simply do the following:
* Clone this repository `git clone git@github.com:breid1313/react-express-boilerplate.git`
    * or if you want to clone using HTTPS `https://github.com/breid1313/react-express-boilerplate.git`
* Head into your newly created directory `cd react-express-boilerplate-master`
* Install the necessary dependencies with by running `npm install` from both the client and api directories
* Finally, start the application and the server. Do do this you will need to have two terminals open, and run `npm start` from both the client and the api directories.

## Ensuring the Application is Working Properly
Once you've started both your React application and Express server, go ahead and navigate your browser to localhost:3000. This is what you should see:
The second middle line of text, "API is working properly" is actually being fetched from out Express server. If you are interested, head over to localhost:9000 on your browser, and you can see the simple UI that has comes with our Express app. The message seen on our React app is coming from localhost:9000/testAPI. Navigating there should take you to an otherwise blank page with the text "API is working properly" in the top left corner.
