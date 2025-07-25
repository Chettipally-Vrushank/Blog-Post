# Blog-Post
Blog Posts REST API
Features
Get all posts: GET /posts
Retrieve a list of all blog posts.
Get a specific post: GET /posts/:id
Retrieve a single post by its unique ID.
Create a new post: POST /posts
Add a new blog post.
Update a post: PATCH /posts/:id
Update specific fields (title, content, or author) of an existing post.
Delete a post: DELETE /posts/:id
Remove a blog post by ID.
Tech Stack
Express.js
body-parser (for parsing request bodies)
Temporary in-memory JavaScript array for data storage (no database required)
Getting Started
. Clone the repository.
. Install dependencies with npm install.
. Start the server: node app.js or npm start.
. Access http://localhost:4000/posts in your browser or use tools like Postman to test
endpoints.
