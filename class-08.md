# Code 301 - Intermediate Software Development

## Class 08 - APIs

Block intro

> Do or Do not. There is no try. - Yoda

### API Design Best Practices ([Article](https://docs.microsoft.com/en-us/azure/architecture/best-practices/api-design))

* What does REST stand for?
* REST APIs are designed around a ____.
* What is an identifer of a resource? Give an example.
* What are the most common HTTP verbs?
* What should the URIs be based on?
* Give an example of a good URI.
* What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?
* What status code does a successful GET request return?
* What status code does an unsuccessful GET request return?
* What status code does a successful POST request return?
* What status code does a successful DELETE request return?

REST Stands for Representational State Transfer
REST APIs are designed around resources.
An identifier is a resource that is uniquely defined. An example from the aritcle is ```https://adventure-works.com/orders/1```
The most common verbs are PUT, POST, GET, PATCH, and DELETE
Nouns
An example from the article is ```https://adventure-works.com/orders```
An API that has a large number of small resources. It is not a good thing as it may require multiple requests and impose a load on teh web server.
GET: 200-OK 404-Not found
POST: 200-OK 400-Bad Request
DELETE: 204-No content 404-not found

### Skim Articles
 
 1. ([RegExr](https://regexr.com/))
 1. ([Regex Tutorial](https://medium.com/factory-mind/regex-tutorial-a-simple-cheatsheet-by-examples-649dc1c3f285))
 1. ([Regex 101](https://regex101.com/))

### Things I want to know more about

* I want to know more about caches/lists of APIs 

Go [Home](index.md)