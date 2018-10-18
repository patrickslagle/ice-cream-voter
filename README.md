# Ice Cream Voter

Run ```npm install```  in the root project dir and run another ```npm install``` at the  ./client folder. Notice that root folder and /client both have package.json files.

Run with ```npm run dev``` on the root folder. This simultaneously runs the express server with nodemon, and the create-react-app client.

Routing on the client is handled with [react-router-dom](https://reacttraining.com/react-router/core/guides/philosophy). API calls to the back end can be done without having to prefix the server hostname by proxying (in the client package.json) the API calls to the express server.

The react app on the client is equipped with a redux store. One may handle async actions using [redux-thunk](https://www.npmjs.com/package/redux-thunk) middleware.
