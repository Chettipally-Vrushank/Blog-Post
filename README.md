# Blog-Post
# Blog Posts REST API

A simple RESTful API built with **Express.js** for managing blog posts. This project demonstrates basic CRUD operations—**create**, **read**, **update**, and **delete**—with all data stored in-memory.

## Features

- **Get all posts**: `GET /posts`  
  Retrieve a list of all blog posts.
- **Get a specific post**: `GET /posts/:id`  
  Retrieve a single post by its unique ID.
- **Create a new post**: `POST /posts`  
  Add a new blog post.
- **Update a post**: `PATCH /posts/:id`  
  Update specific fields (title, content, or author) of an existing post.
- **Delete a post**: `DELETE /posts/:id`  
  Remove a blog post by ID.

## Tech Stack

- [Express.js](https://expressjs.com/)
- [body-parser](https://www.npmjs.com/package/body-parser) (for parsing request bodies)
- In-memory JavaScript array for temporary data storage (no database required)

## Getting Started

1. **Clone the repository**
    ```
    git clone https://github.com/your-username/your-repo-name.git
    cd your-repo-name
    ```

2. **Install dependencies**
    ```
    npm install
    ```

3. **Start the server**
    ```
    node app.js
    ```
    Or, if you have a start script defined:
    ```
    npm start
    ```

4. The API will be running at [http://localhost:4000/posts](http://localhost:3000/posts).
   You need to run server,js first and then the index.js.
   index.js acts as the API to server.js.
   Use tools like [Postman](https://www.postman.com/) or [curl](https://curl.se/) to test the endpoints.


