📜 Quora Post Project
Welcome to the Quora Post Project! 🎉 This is a simple application where users can create, edit, and delete posts, similar to Quora-style posts.

🚀 Features
Create New Posts: 📝 Users can add new posts.
View All Posts: 👀 View a list of all posts made by users.
Edit Posts: ✏️ Users can edit existing posts.
Delete Posts: ❌ Users can delete their posts.
Unique Post ID: 🔑 Each post is assigned a unique ID using uuid.

🔧 Technologies Used
Node.js: 🟢 Server-side JavaScript runtime.
Express.js: 🚄 Web framework to build the server.
EJS: 🖥️ Templating engine to render dynamic HTML pages.
uuid: 🎲 Library to generate unique IDs for each post.
Method-Override: 🔀 Allows using HTTP verbs such as PUT and DELETE.

🌐 Routes
GET /: Returns a "Server working well!" message.
GET /posts: Displays all the posts.
GET /posts/new: Renders a form to create a new post.
POST /posts: Submits a new post.
GET /posts/:id: Displays a specific post by ID.
PATCH /posts/:id: Edits an existing post by ID.
GET /posts/:id/edit: Renders the edit form for a post.
DELETE /posts/:id: Deletes a specific post by ID.

💡 Notes
This project uses EJS to render dynamic HTML pages.
The application uses methodOverride to handle HTTP methods like PATCH and DELETE via form submissions.