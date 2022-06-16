# blog-api

Environment Variables
-
- MONGODB_URI
- SECRET_KEY

Installing and Running Locally
-
### Clone the respository
In the terminal, use the following command: 

<code>
git clone https://github.com/wendyvosu/blog-api.git
</code>

### Install dependencies
Cd into the project directory and use the following commands in the terminal: 

npm init -y<br>
npm i bcrypt<br>
npm i dotenv<br>
npm i express<br>
npm i helmet<br>
npm i jsonwebtoken<br>
npm i mongodb<br>
npm i mongoose<br>
npm i morgan<br>

Endpoints
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

Parameters
-
asdf

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
