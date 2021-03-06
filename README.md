# HTTP / AJAX Mini Sprint

## Topics
  * Axios for making HTTP requests
  * JavaScript Promises

In this mini sprint, you'll be eased into the code base for the actual HTTP sprint. Upon cloning this repository, take a moment to look over the different pieces that are already in here. There shouldn't be anything too scary; it's just another React app created using `create-react-app` with some custom styling. The important bits are inside the components folder.

## Running the Application
To run the mini sprint code, first run `npm install` in the root directory. Then run `npm start` to run the server. In _another_ terminal, `cd` into the `client` directory, run `npm install`, then `npm start`. You'll see that we have a non-functioning React app with some compilation errors. 

## Instructions
The `FriendsList` component renders an array of friend objects. Your job for this mini sprint is to add the code necessary inside `FriendsList.js` to fetch this data from the server and populate the list.

Hint: The endpoint to get a list of friends is: `http://localhost:5000/friends`. 

Once you get through the sprint and have the list of friends being rendered by the `FriendsList` component, take some time to read about HTTP, Promises, AJAX, and any of the other topics we touched upon during the lecture. 

## Helpful Links
  * [Promises for Dummies](https://scotch.io/tutorials/javascript-promises-for-dummies) -- A pretty thorough and cohesive writeup on Promises. I would suggest starting here first.
  * [AJAX Documentation on MDN](https://developer.mozilla.org/en-US/docs/AJAX) -- A good place to start reading about and delving into the different parts that make up the AJAX standard.
  * [JavaScript Promises Plain and Simple](https://coligo.io/javascript-promises-plain-simple/) -- This article talks about using Promises in the context of making HTTP requests, which means it's pretty perfect for our use case. Note that in their examples they use the `fetch` API, which is an alternative to Axios.