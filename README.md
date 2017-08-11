# reactJS_blog

## Live demo

[Click Here](https://fabianchoxd.github.io/reactJS_blog/#/)

Easy Blog with Login (Mongodb - NodeJs - Express) API

# This is the CLIENT section - the API code it's Storage at HEROKU.

How to use it ? 

1. Clone the repo
2. npm install
3. Change the Api routes to locally mongoose routes.
4. open a console and type mongod to start MongoDB database "mongodb://127.0.0.1/react"
5. in a new console type npm start
6. Enjoy with a cool Blog.

## What can you do ?

### Register 

in postman (POST) - http://localhost:5000/api/register

``` javascript {
{
  "username" : "test",
  "password" : "123",
  "first_name" : "testName",
  "email" : "test@mail.com",
  "last_name" : "testLastName",
  "created_at" : "Date.now()"
}
```
you will get a 200 OK confirmation code.

- - - -

### Login 

in postman (POST) - http://localhost:5000/api/login

``` javascript {
{
  "email" : "test@mail.com",
  "password" : "123"
}
```
you will get a 200 OK confirmation code.

- - - -

You can Also make a CRUD with Posts...

Enjoy it 
