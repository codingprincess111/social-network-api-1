# Heather's NoSQL Social Network API

This is a Node.js API built for a social network web application that enables users to perform CRUD operations on social networking data models using a NoSQL database. The API supports various data models, including friends, users, thoughts, and reactions. Users can interact with these models by retrieving data by ID or querying all available data.

The API leverages the power of Node.js and Mongoose, providing a flexible and scalable solution for handling social networking data. By utilizing a NoSQL database, this API eliminates the constraints often associated with traditional relational databases, allowing for a more streamlined and efficient data management process.

## Table of Contents:

- [Overview](#Overview)
- [The Challenge](#The-Challenge) 
- [Usage Instructions](#Usage-Instructions)
- [Built With](#Built-With)
- [What I Learned](#What-I-Learned)
- [Continued Development](#Continued-Development)
- [Acknowledgements](#Acknowledgements) 

# Overview

## The Challenge:

The goal of this project was to develop a RESTful API for a social media startup that enables CRUD operations on users, thoughts, and reactions data models using a NoSQL database. The API is implemented using Node.js and Mongoose, providing a robust and efficient solution for handling large amounts of unstructured data.

API Features:

- User: Create and delete user accounts
- Thoughts: Create, read, update, and delete thoughts
- Reactions: Add and remove reaction to thoughts
- Friend management: Add and remove friends to user's friend list

 ## Usage Instructions
 Repository: open the documentation run 'npm i'. To use the application you will need a MongoDB database. Once installed on your machine or server create an `.env` file in the root directory. Once the server is running, use a tool like Postman to test the API endpoints.

### Available Endpoints

1. GET /api/user - get all users
2. GET /api/user/:userId - get a single user by ID
3. POST /api/user - create a new user
4. PUT /api/user/:userId - update a user by ID
5. DELETE /api/user/:userId - delete a user by ID
6. GET /api/thought - get all thought
7. GET /api/thought/:thoughtId - get a single thought by ID
8. POST /api/thought - create a new thought
9. PUT /api/thought/:thoughtId - update a thought by ID
10. DELETE /api/thought/:thoughtId - delete a thought by ID
11. POST /api/thought/:thoughtId/reactions - add a reaction to a thought
12. DELETE /api/thought/:thoughtId/reactions/:reactionId - remove a reaction from a thought
13. POST /api/user/:userId/friends/:friendId - add a friend to a user's friend list
14. DELETE /api/user/:userId/friends/:friendId - remove a friend from a user's friend list

