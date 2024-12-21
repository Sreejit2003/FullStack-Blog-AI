Full-Stack Blog Application
Table of Contents
Project Overview
Key Features
Technologies Used
Installation Instructions
Usage
API Endpoints
Contributing
License
Project Overview
The Full-Stack Blog Application is a modern web application that allows users to create, read, update, and delete blog posts. It features user authentication, an admin dashboard, and a responsive design. The application is built using the MERN stack (MongoDB, Express.js, React.js, Node.js) and provides a seamless user experience.

Key Features
User Authentication: Users can sign up and log in using Google social login with JWT for secure authentication.
Blog Management: Admins can create, update, and delete blog posts, categories, and tags.
Search Functionality: Users can search for blogs based on titles and descriptions.
SEO-Friendly: The application is optimized for search engines with SEO-friendly pages.
Filtering Options: Blogs can be filtered based on categories and tags.
Pagination: Supports pagination for better navigation through blog posts.
Comments: Users can leave comments on blog posts using Disqus integration.
Related Blogs: Displays related blog posts to enhance user engagement.
Technologies Used
Frontend:
React.js
Next.js
Backend:
Node.js
Express.js
Database:
MongoDB
Authentication:
JWT (JSON Web Tokens)
Styling:
CSS
Comments:
Disqus
Installation Instructions
To set up the Full-Stack Blog Application locally, follow these steps:

Prerequisites
Node.js (v14 or higher)
MongoDB (local or cloud instance)
Git
Clone the Repository
bash

Verify

Open In Editor
Run
Copy code
git clone https://github.com/aditya28sarin/Full-Stack-Blog-Application.git
cd Full-Stack-Blog-Application
Backend Setup
Navigate to the backend directory:
bash

Verify

Open In Editor
Run
Copy code
cd backend
Install dependencies:
bash

Verify

Open In Editor
Run
Copy code
npm install
Create a .env file in the backend directory and add your MongoDB connection string and JWT secret:
plaintext

Verify

Open In Editor
Run
Copy code
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
Start the backend server:
bash

Verify

Open In Editor
Run
Copy code
npm start
Frontend Setup
Navigate to the frontend directory:
bash

Verify

Open In Editor
Run
Copy code
cd ../frontend
Install dependencies:
bash

Verify

Open In Editor
Run
Copy code
npm install
Start the frontend application:
bash

Verify

Open In Editor
Run
Copy code
npm start
Usage
Open your browser and navigate to http://localhost:3000 to access the application.
Users can sign up or log in using Google.
Admins can manage blog posts, categories, and tags from the admin dashboard.
Users can search for blogs, filter them, and leave comments.
API Endpoints
Authentication
POST /api/auth/login: Log in a user.
POST /api/auth/signup: Register a new user.
Blog Management
GET /api/posts: Retrieve all blog posts.
GET /api/posts/:id: Retrieve a specific blog post by ID.
POST /api/posts: Create a new blog post (admin only).
PUT /api/posts/:id: Update a blog post by ID (admin only).
DELETE /api/posts/:id: Delete a blog post by ID (admin only).
Category Management
GET /api/categories: Retrieve all categories.
POST /api/categories: Create a new category (admin only).
PUT /api/categories/:id: Update a category by ID (admin only).
DELETE /api/categories/:id: Delete a category by ID (admin only).
Contributing
Contributions are welcome! If you would like to contribute to this project, please fork the repository and submit a pull request.

License
This project is licensed under the MIT License. See the LICENSE file for details.

This documentation provides a comprehensive overview of the Full-Stack Blog Application, including setup instructions and key
