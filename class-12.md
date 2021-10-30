# Code 301 - Intermediate Software Development

## Class 12 - CRUD

Block intro

>  Everything that has a beginning has an end. I see the end coming. I see the darkness spreading. I see death. And you are all that stands in his way. - The Oracle

### Status Codes Based On REST Methods ([Article](https://www.moesif.com/blog/technical/api-design/Which-HTTP-Status-Code-To-Use-For-Every-CRUD-App/))

* In your own words, describe what each group of status code represents:
    * 100’s =
    * 200’s =
    * 300’s =
    * 400’s =
    * 500’s =
* What is a status code 202?
* What is a status code 308?
* What code would you use if an update didn’t return data to a client?
* What code would you use if a resource used to exist but no longer does?
* What is the ‘Forbidden’ status code?

100s - infomative codes
200s - success codes
300s - redirecting codes
400s - client error codes
500s - server error codes
A 202 code is an accepted code status.
A 308 is a permanent redirect status.
A 500 code.
A 410 code
A 403 code.

### Videos

 ([Build A REST API With Node.js, Express, & MongoDB - Quick](https://www.youtube.com/watch?v=fgTGADljAeg))

* Why do we need to pull our MongoDB database string out of our server and put it into our .env?
* What is middleware?
* What does app.use(express.json()) do?
* What does the /:id mean in a route?
* What is the difference beween PUT and PATCH?
* How do you make a defalut value in a schema?
* What does a 500 error status code mean?
* What is the difference between a status 200 and a status 201?

To maintain our important API/server information.
Creating a function or method to handle a task
It allows the server to recognize a .json file
Put updates the entire object, patch updates a selected attribute

```new Schema({ date: { type: Date, default: Date.now }})``` - pulled from mongoose docs
A 500 error is a problem with the server processing the request.
A 200 is Ok code. A 201 is successful in creating an object


### Things I want to know more about

* I would like to know more about options in creating routes and what type of routes are commonly used in various apps.

Go [Home](index.md)