you can run this file using  <mark> nodemon index.js</mark>

<strong>mongodb connect using</strong> 
<mark>mongodb://127.0.0.1:27017/blog-app</mark>

### Authentication Endpoints

| Method | Route        | Description                  |
|--------|--------------|------------------------------|
| POST   | /register     | Register a new user          |
| POST   | /login        | Log in as an existing user   |
| GET    | /logout       | Log out the current user     |

##
### Blog Endpoints

| Method | Route           | Description                    |
|--------|-----------------|--------------------------------|
| GET    | /recipes        | Fetch all blog                 |
| POST   | /recipes        | Create a new blog              |
| PATCH  | /recipes/:id    | Update an existing blog        |
| DELETE | /recipes/:id    | Delete a blog                  |
