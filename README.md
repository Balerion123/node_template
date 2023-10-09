# Node JS Project Template

## Table of Contents

- [Introduction](#introduction)
- [Prerequisites](#prerequisites)
- [Start](#start)
- [Features](#features)

## Introduction

This is a basic template with proper error handling and separation of development and production environments which you can use to jump into the coding part and not have to worry about the setting up work you have to do every time you make a new Node.js project.

## Prerequisites

### Prerequisites

Before you can activate the project, ensure you have the following prerequisites installed:

- Node.js: You can download it from [nodejs.org](https://nodejs.org/).

### Setting up the `config.env` File

```bash
# Navigate to the backend folder
cd backend

# Create the config.env file
touch config.env

# Open the config.env file in a text editor
# Add the following properties and save the file
PORT=8000
DATABASE="Your Database Connection String"
DATABASE_PASSWORD="Your Database Password"
NODE_ENV=development
JWT_SECRET="Your Secret Key"
JWT_EXPIRES_IN=30d
JWT_COOKIE_EXPIRES_IN=0.5


# Replace "Your Database Connection String" and "Your Database Password" with the actual database connection string and password you intend to use. Also, set your preferred values for JWT_SECRET, JWT_EXPIRES_IN, and JWT_COOKIE_EXPIRES_IN.

```

````

## Start

```bash
# Navigate to the backend folder if not already there
cd backend

# Install project dependencies
npm i

# Start the project
npm start

```

## Features

- **Error Handling:** Proper error handling middlewares and utility function have already been set up.
- **Basic MVC Setup:** A model, route and controller have already been set up for reference.
- **Separation of Development and Production Environment:** Environment can be changed through config file which manages error responses.
````
