# Code 301 - Intermediate Software Development

## Class 14 - Authentication

Block intro

> We are who we choose to be. – Green Goblin

### What is OAuth ([Article](https://www.csoonline.com/article/3216404/what-is-oauth-how-the-open-authorization-framework-works.html))

* What is OAuth?
* Give an example of what using OAuth would look like.
* How does OAuth work? What are the steps that it takes to authenticate the user?
* What is OpenID?

OAuth is an authorization feature that allows the user to be authenticated by a third party site. Without the need for another login and password.
Google's automated sign in that works with multiple sites like paypal, linked in, and amazon to name a few.
OAuth is a multi step process that in short, the current client website request authentication from a third party website. The two sites exchange temporary access tokens and then when authenticated exchange permanent tokens to grant access to the original client website.
OpenID is another authentication platform that is far less known and more tedious to implement, according to the article.

### Authorization and Authentication flows ([Article](https://auth0.com/docs/authorization/flows))

* What is the difference between authorization and authentication?
* What is Authorization Code Flow?
* What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?
* What is Implicit Flow with Form Post?
* What is Client Credentials Flow?
* What is Device Authorization Flow?
* What is Resource Owner Password Flow?

Authentication validates, authorization permits.
The exchange of authorization code for a token.
The same as a authorization code flow, with additional security requirements/steps.
An authentication code flow for public clients or applications unable to securely store client secrets.
Machine to machine authorization, ie user name and password.
Authorization based on the device accessing versus the user.
Requests user credentials via an interactive form.

### Bookmark/Skim 

([Auth0 for single page apps](https://auth0.com/docs/libraries/auth0-react))

### Things I want to know more about

* 


Go [Home](index.md)