A fully-featured RESTful Blog API built using Django REST Framework and MySQL. This project allows users to create, read, update, and delete blog posts. Designed with scalability and best practices in mind, it's ideal for use as a backend service for blogging platforms or CMS integrations.

🚀 Features
User registration and login (Token-based authentication)

Create, Read, Update, Delete (CRUD) operations on blog posts

Post filtering by author or title

Permissions and role-based access (e.g., only authors can edit their posts)

MySQL as a production-ready relational database

Admin panel for content management

⚙️ Tech Stack
Backend Framework: Django, Django REST Framework

Database: MySQL

Authentication: Token Authentication (DRF's TokenAuth)

Tools: Postman, Git
🛠️ API Endpoints
Method	Endpoint	Description	Auth Required
POST	/api/register/	Register a new user	❌
POST	/api/login/	Get auth token	❌
GET	/api/posts/	List all blog posts	✅
POST	/api/posts/	Create a new post	✅
GET	/api/posts/{id}/	Retrieve single post	✅
PUT	/api/posts/{id}/	Update post (if owner)	✅
DELETE	/api/posts/{id}/	Delete post (if owner)	✅

📚 Future Improvements
JWT Authentication using djangorestframework-simplejwt

Comments and tags for posts

Like/Bookmark system

Rate limiting and throttling

Docker + CI/CD integration




