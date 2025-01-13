# Social Network API

## Description
A robust API for a social network web application where users can share their thoughts, react to friends' thoughts, and create a friend list. This application uses Express.js for routing, MongoDB as the database, and Mongoose ODM. The API is designed to handle large amounts of unstructured data efficiently.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Credits](#credits)
- [License](#license)

## Installation
1. Clone the repository
2. Install MongoDB on your machine (if not already installed)
3. Run `npm install` to install dependencies
4. Run `npm start` to start the server

## Usage
The API provides the following endpoints:

### Users
- GET `/api/users` - Get all users
- GET `/api/users/:userId` - Get single user by ID
- POST `/api/users` - Create new user
- PUT `/api/users/:userId` - Update user by ID
- DELETE `/api/users/:userId` - Delete user by ID
- POST `/api/users/:userId/friends/:friendId` - Add friend
- DELETE `/api/users/:userId/friends/:friendId` - Remove friend

### Thoughts
- GET `/api/thoughts` - Get all thoughts
- GET `/api/thoughts/:thoughtId` - Get single thought by ID
- POST `/api/thoughts` - Create new thought
- PUT `/api/thoughts/:thoughtId` - Update thought by ID
- DELETE `/api/thoughts/:thoughtId` - Delete thought by ID
- POST `/api/thoughts/:thoughtId/reactions` - Add reaction
- DELETE `/api/thoughts/:thoughtId/reactions/:reactionId` - Remove reaction

## Features
- User Management
  - Create, Read, Update, and Delete users
  - Add and remove friends
- Thought Management
  - Create, Read, Update, and Delete thoughts
  - Add and remove reactions to thoughts
- Data Validation
  - Email validation
  - Required field validation
  - Length restrictions on text fields

## Technologies Used
- Node.js
- Express.js
- MongoDB
- Mongoose ODM
- JavaScript Date object
- RESTful API principles

## Credits
Developed by Marcello Romero

## License
This project is licensed under the MIT License.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Questions
For any questions or concerns, please open an issue in the GitHub repository or contact the developer directly at mra24@me.com

GitHub: [marcelloro24](https://github.com/marcelloro24)