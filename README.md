# blog-api

Environment Variables
-
- MONGODB_URI
- SECRET_KEY

Installing and Running Locally
-
### Clone the respository
In the terminal, use the following command: 

```
git clone https://github.com/wendyvosu/blog-api.git
```

### Install dependencies
Cd into the project directory and use the following commands in the terminal: 

```
npm init -y
npm i bcrypt
npm i dotenv
npm i express
npm i helmet
npm i jsonwebtoken
npm i mongodb
npm i mongoose
npm i morgan
```
Endpoints and Parameters
-
### /Auth
- router.post("/"): User login.

### /Users
- router.post("/"): Register a new user.

### /Blogs
- router.get("/"): Get blogs. 
- router.post("/"): Create blogs. 
- router.get("/:id"): Get blog by id. 
- router.put("/:id"): Update blog by id. 
- router.delete("/:id"): Delete a blog. 

Schemas
-
### User Schema
- username: string, required
- email: string, required
- birthday: date, required
- age: number
- password: string, required

### Blog Schema
- created_by: string, required
- created_at: date, required
- blog_title: string, required
- blog_content: string, required
- blog_content: string, required
- private: blooean, required
