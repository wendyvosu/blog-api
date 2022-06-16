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
asdf

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
