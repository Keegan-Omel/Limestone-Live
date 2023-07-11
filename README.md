# Limestone-Live

## Description

Limestone-Live is a platform for users to connect and share their thoughts with friends. It serves as the backend for a social networking web application, allowing users to perform actions such as creating posts, reacting to posts, and managing their friend list.

The API is built using Express.js, a fast and minimalist web application framework for Node.js. It leverages MongoDB as the database to store user information, posts, reactions, and friend connections. The Mongoose ODM (Object Data Modeling) library is used to provide a more convenient and structured way of interacting with the MongoDB database.

## Table of Contents

Project Description
Getting Started
Installation
Configuration
Running the Application
Usage
API Endpoints
Contributing
License

## Getting Started

Follow these steps to get the project up and running on your local machine.

## Installation

Clone the repository to your local machine.
Navigate to the project directory.
Run npm install to install the required dependencies.

## Configuration

Create a MongoDB database and obtain the connection URL.
Create a .env file in the project root directory.
Set the following environment variables in the .env file:
MONGODB_URI: Connection URL for your MongoDB database.

## Running the Application

Run npm start to start the server. The API will be accessible at http://localhost:3001.

## Usage

Once the server is up and running, you can start making requests to the API endpoints.

Refer to the API Endpoints section for details on the available endpoints and their usage.

Here are the main endpoints provided by the API:

user(folder):
GET find all users
GET find users by I.D.
POST create user
POST create second user
POST create thrid user
PUT update user
DEL delete user

friends(folder):
POST add friend
DEL delete friend

thoughts(folder):
GET thoughts 
GET thoughts by I.D.
POST create thougths
DEL delete thoughts

reactions(folder):
POST create reaction
DEL delete reaction

## Contributing

Contributions to this project are welcome! If you have any ideas, suggestions, or bug reports, please open an issue or submit a pull request.

When contributing, please ensure that your code adheres to the existing code style and conventions. Provide clear and descriptive commit messages to facilitate the review process.

##License

This project is licensed under the MIT License. You are free to modify, distribute, and use the code for personal and commercial purposes. See the LICENSE file for more details.

## GitHub Link: 

https://github.com/Keegan-Omel/Limestone-Live

## Demonstration Video Link:



