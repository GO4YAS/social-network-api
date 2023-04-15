# social-network-api

## Table of Contents
  * [Description](#description)
  * [User Story](#user-story)
  * [Acceptance Criteria](#user-story)
  * [Installation](#installation)
  * [Setup](#setup)
  * [Usage](#usage)
  * [Screenshots of Application in Use](#screenshots-of-application-in-use)
  * [Technologies](#technologies)
  * [Tests](#tests)
  * [Questions?](#questions)



## Description
An API for a social network web application where users can share their thoughts, react to friends’ thoughts, and create a friend list.


## User Story
```
    AS A social media startup
    I WANT an API for my social network that uses a NoSQL database
    SO THAT my website can handle large amounts of unstructured data
```


## Acceptance Criteria 
```
    GIVEN a social network API
    WHEN I enter the command to invoke the application
    THEN my server is started and the Mongoose models are synced to the MongoDB database
    WHEN I open API GET routes in Insomnia for users and thoughts
    THEN the data for each of these routes is displayed in a formatted JSON
    WHEN I test API POST, PUT, and DELETE routes in Insomnia
    THEN I am able to successfully create, update, and delete users and thoughts in my database
    WHEN I test API POST and DELETE routes in Insomnia
    THEN I am able to successfully create and delete reactions to thoughts and add and remove friends to a user’s friend list
```
    

## Installation
- Step 1: Clone this repository. you can do this by running ``` git clone https://github.com/Brooksteven/Social-Network-NoSQL.git``` in your terminal
- Step 2: Install dependencies by running the ``` npm install ``` command in the command line
- Step 3: Open your code editor by running the command ``` code . ```
- step 4: Start the server by running ``` npm start ``` in the terminal
- step 5: - Open any application that simplifies the interaction and design of HTTP-based APIs like [insomnia](https://insomnia.rest/download)
- step 6: Create, read, update, and delete Users, thoughts, and reactions using endpoints in usage


## Setup
Integrated Terminal: 	
* mongod
* npm i
* npm start
        
        
## Usage
After following the instructions in installation: 
1. Open the "index.js" file in your integrated terminal.
2. Run command "npm run seed" to seed users into your database.
3. Run command "npm run start" (or "node server.js"). Alternatively, if you have Nodemon installed, run "npm run watch" (or "nodemon server.js"). 
4. Open insomnia and type in "localhost:3001/api/_" in the address bar. Check out the following routes: <br><br>
User + Friends <br>
- `/api/users` to get all users or create user
- `/api/users/:userId` to get one user, update and delete user
- `/api/users/:userId/friends/:friendId` to add or delete a friend <br><br>
Thought + Reactions <br>
- `/api/thoughts` to get all thoughts or create thought
- `/api/thoughts/:thoughtId` to get one thought, update or delete. 
- `/api/thoughts/:thoughtId/reactions` to create reaction 
- `/api/thoughts/:thoughtId/reactions?reactionId=` to delete reaction 
5. When finished, run CONTROL-C in terminal to end and trash the session. 

Please check out this [video] to view a demonstration of how to use this program. 


## Screenshots of Application in Use



## Technologies
* [Node.js](https://nodejs.org/en/)
* [Express.js](https://expressjs.com)
* [MongoDB](https://www.mongodb.com)
* [Mongoose](https://mongoosejs.com/docs/)
* [Javascript](https://developer.mozilla.org/en-US/docs/Web/JavaScript)


  ## Questions?
  ### Reach me here: 
  [Yasmein Yang](https://github.com/GO4YAS)  
  yasmein.yang@gmail.com
