# Social MERN
Since i'm using a DB. Feel free to contact me relating config.js and DB credentials. Otherwise just go to the hosted Heroku page and use this code as reference of what's going on.

https://www.linkedin.com/in/chaseolsen/

## Technologies Used

* NodeJS
* Express (to create node server)
* ReactJS
* Redux
* Webpack (to transpile ES6 and all js files into client.min.js)
* Babel (to handle ES6 code with webpack)

## Project Overview

Qwerky web application build with the ReactJS (With Redux), MongoDB, NodeJS, Express.

Here is basic file structure of project

    ├── client                  # All client related files, including a client Node_Modules
    ├── node_modules            # Will be generated when running 'npm install'
    ├── models                  # Contains Mongoose Schemas for Post/Profile/User
    ├── routes                  # All API Routes
    ├── validation              # All Validation files for advanced error checking with API handles.
    ├── server.js               # Server related code, like express, route handling, connecting to db etc.
    └── README.md


## How to Run Everything (since i've yet to finish and host to heroku yet)
(be sure node is installed)

1. Clone Project
```
git clone https://github.com/chaseolsen/SocialMERN.git
```
2. Enter Project
```
cd trialproject
```

3. Install Dependencies (Do this inside root directory as well as Client directory, I've two sperate Node_Modules for client/server)
```
npm install
```

4. Run Node Server (I used 'concurrently' to run both backend server and front end, see package.json(root) for all scripts)
```
npm run dev
```
Done! Your browser should open and run localhost:3000

## Extra Details About Development And Future Plans
I plan to implement react-stock-charts and turn the entire application to a social trading web app once I finish setting everything up.

