Social Media APi project in NodeJS

- System Requirements 
    - NodeJS
    - MongoDB
    - NPM
    
- Api Testing Tool
     -PostMan

- Setting up the project
    - Clone the repository
    - Go inside the cloned folder from your terminal/cmd
    - Run `npm install`
    - Create a new file `.env` and then configure the following environment variables
        - PORT=3000
    - Create DataBase in MongoDB Atlas and connect your application then `.env` file paste the following variables 
        - MONGO_URL=xyz

- Run the Project
    - Run `npm start`

- Category Resouece
    - POST `/api/auth/register`, create User Account,
    - POST `/api/auth/login`, login User,
    - PUT `/api/users/:id`, update a User Account,
    - DELETE `/api/users/:id`, delete a User Account`,
    - GET `/api/users/:id`, get all the users,
    - PUT`/api/users/:id/follow`, follow Users by user,
    - PUT`/api/users/:id/unfollow`,unfollow Users b user,
    - POST`api/posts`,create a post,
    - PUT`/api/posts/post:id`,update post,
    - DELETE`/api/posts/post:id`,delete a post,
    - PUT`/api/posts/post:id/like`,like a post,
    - GET`/api/posts/:id`,get post by user,
    - GET`/api/posts/timeline/all`,get timeline user

