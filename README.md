# Project Manager

![screenshot](./screenshot.PNG)  

## Description

This is an app I built to practice working with MERN stack technologies- namely graphql for querying a mongoDB database. On the backend, this app makes use of a MongoDB database hosted on MongoDB atlas. To query the database, we are using a node express server to make use of mongoose and graphql. On the front-end we are using React, Bootstrap, and Apollo.

This app has full CRUD functionality!

## Installation and Usage

To run this app locally, clone the repo.

To run the backend server, start in the root folder.
In root:  
```
npm i
npm start
```
You'll need to update the environment variable for the frontend to ensure you're connecting to the local server.  
Open the ```.env ``` file inside the ```./client``` folder. Change the ```APOLLO_URI``` to reflect the address of the graphql endpoint on the node express server. Normally this should be ```http://localhost:5000/graphql```

To run the frontend server, cd into the client folder ```cd client```  
In ./client:  
```
npm i
npm run start
```
The app should now be accessible at ```http://localhost:3000```

## Built With
### Backend
![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white)
![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![GraphQL](https://img.shields.io/badge/-GraphQL-E10098?style=for-the-badge&logo=graphql&logoColor=white)  
[Mongoose] [MongoDB Atlas]

### Frontend
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![Apollo-GraphQL](https://img.shields.io/badge/-ApolloGraphQL-311C87?style=for-the-badge&logo=apollo-graphql)

### Languages
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)

### Dev Tools
![NPM](https://img.shields.io/badge/NPM-%23CB3837.svg?style=for-the-badge&logo=npm&logoColor=white)
![Nodemon](https://img.shields.io/badge/NODEMON-%23323330.svg?style=for-the-badge&logo=nodemon&logoColor=%BBDEAD)
![Vercel](https://img.shields.io/badge/vercel-%23000000.svg?style=for-the-badge&logo=vercel&logoColor=white)
![Render](https://img.shields.io/badge/Render-%46E3B7.svg?style=for-the-badge&logo=render&logoColor=white)