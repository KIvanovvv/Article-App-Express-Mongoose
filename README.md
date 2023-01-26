
# ArticleApp

This is a personal project, in which I implement MVC architecture connected to Cloud MongoDB. Upon register or login the user recives a JsonWebToken. With a valid JWT the server create's a session wiht the user's "view information". The validity of the token is checked upon every request with middleware guards.


## Features

- Login/Register
- Reading articles for all users (Guests and Logged in)
- Create,Update and Delete articles for Logged in users
- Reading and Creating comments on selected article for Logged in users



## Deployment

Link to the deployed project https://modern-hen-necklace.cyclic.app/




## Tech Stack


**Server:**  Express, Mongodb, Mongoose, Handlebars, CSS, Cookie-parser, JWT, Bcrypt, 


## Screenshots
**Guests:**
![App Screenshot](https://firebasestorage.googleapis.com/v0/b/test-b53a1.appspot.com/o/homeGuest.PNG?alt=media&token=af50ff6a-aee3-4ca2-8aca-ed5211b36337)

![App Screenshot](https://firebasestorage.googleapis.com/v0/b/test-b53a1.appspot.com/o/articleGuest.PNG?alt=media&token=13d91e80-96f8-49f4-900f-2036602cbe9b)

![App Screenshot](https://firebasestorage.googleapis.com/v0/b/test-b53a1.appspot.com/o/loginGuest.PNG?alt=media&token=c4859d02-4c13-4df6-b2b7-eaaff2afc6ba)

![App Screenshot](https://firebasestorage.googleapis.com/v0/b/test-b53a1.appspot.com/o/registerGuest.PNG?alt=media&token=bf28c6c9-b287-4647-a4d5-0569014bdcd8)

**Users:**
![App Screenshot](https://firebasestorage.googleapis.com/v0/b/test-b53a1.appspot.com/o/homeUser.PNG?alt=media&token=04ecdcae-baf6-4498-b68a-8c9496d6f203)

![App Screenshot](https://firebasestorage.googleapis.com/v0/b/test-b53a1.appspot.com/o/article.PNG?alt=media&token=6bf9b19b-5a48-4f54-8e05-c9a0bb06d21a)

![App Screenshot](https://firebasestorage.googleapis.com/v0/b/test-b53a1.appspot.com/o/commentsUser.PNG?alt=media&token=992ae2fc-fd9b-46c4-b510-5aae833b0a31)

![App Screenshot](https://firebasestorage.googleapis.com/v0/b/test-b53a1.appspot.com/o/publishedUser.PNG?alt=media&token=080702e7-c812-4ee4-9ab9-570b8f03d382)

![App Screenshot](https://firebasestorage.googleapis.com/v0/b/test-b53a1.appspot.com/o/editUser.PNG?alt=media&token=88653ece-0423-4eb6-9d9f-3c5c81c156b0)

![App Screenshot](https://firebasestorage.googleapis.com/v0/b/test-b53a1.appspot.com/o/deleteUser.PNG?alt=media&token=eb91cd59-f70d-4532-a070-03cfeb0bfa15)

![App Screenshot](https://firebasestorage.googleapis.com/v0/b/test-b53a1.appspot.com/o/createUser.PNG?alt=media&token=ac43b66b-2af3-4b22-9dd1-8cd281c517e9)