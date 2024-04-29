# Login and Signup with API in Angular 17

In this tutorial, we'll learn how to build login and signup pages with Angular 17. we'll use HTML and CSS to create the pages then use Angular code to build the login and signup forms and get the login and signup data from the forms using a reactive approach and then submit it to the auth endpoint using HttpClient.

## Setting Up the Authentication Backend

We'll use this Node.js app from https://github.com/techiediaries/node-mongoose-jwt which provides an authentication backend so make sure you have MongoDB installed in your system then clone the repo, navigate inside of it and run the following command:

```
npm install
```

Next create an .env file and add the following contents:

```
CONNECTION_STRING= mongodb://127.0.0.1:27017/myapp
JWT_SECRET= secret123456789
```


Next, run the backend using this command:

```
npm start
```
You app JWT authentication backend will be listening at http://localhost:3000.

Read the full article from [https://www.techiediaries.com/login-signup-api-angular-17/](https://www.techiediaries.com/login-signup-api-angular-17/)

