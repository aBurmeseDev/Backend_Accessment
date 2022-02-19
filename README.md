# Hatchway-Backend-Challenge:

Backend Challenge at Hatchways.

### Summary:

- This application contains the results of a backend-challenge at Hatchways.
- The challenge is entirely focused on the backend and uses an external API, as a result I have not used my own database.
- tests are found in test/test-page.js

### Requirements:

```
Node 16.14.0
Nodemon 2.0.15
```

### Steps to Operate

- In the terminal and within the project directory run `npm install`
- This server will run on `PORT=3000`
- Run `npm start` to start the server, which will be at `localhost:3000`
- Step-1 result will be found at localhost:3000/api/ping
- Step-2 result will be found at localhost:3000/api/posts/:tags/:sortBy?/:direction?
- For example you main insert http://localhost:3000/api/posts/history,tech/likes/desc to get a result.
  Or simply http://localhost:3000/api/posts/history,tech
- Run `npm test` to see the passing tests in the terminal
- I used `Thunder Client` (Visual Studio extention) to verify all of my solutions.
