# Simple Authentication System

This is a basic authentication system built with Node.js and Express, using JSON Web Tokens (JWT) for user authentication.

## Overview

This authentication system provides two main functionalities:

1. **Sign In Endpoint (`POST /signin`):** Allows users to sign in with their username and password. Upon successful authentication, a JWT token is generated and returned to the client.

2. **User List Endpoint (`GET /users`):** Returns a list of users stored in an in-memory database, excluding the user associated with the provided JWT token.

## Features

- User authentication using JWT
- In-memory user database for demonstration purposes

## Usage

1. **Clone the Repository:**
   ```bash
   git clone <repository_url>

