#### Heathers notes that still need to be changed to markdown style wise
---
My name is Heather and these are my notes today is April 17th

req.body
!!!!!! LOOK INTO THIS
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Property_Accessors
'JavaScript dot notation to access properties of the JSON object'

!!!!!! READ EXPRESS DOCS
http://expressjs.com/en/4x/api.html

why are knex.js and knexfile.js two separate files?


The questions and answers that Christian asked me that I should have know, and taken notes on earlier:

What are the two ways to access values from an object?
dot notation:
objectName.propertyName;

bracket notation:
objectName["propertyName"];

var person = {
    firstName:"John",
    lastName:"Doe",
    age:50,
    eyeColor:"blue"
};

person.lastName;
person["lastName"];

What is req.body?
An object containing text parameters from the parsed request body, defaulting to {}.
Contains key-value pairs of data submitted in the request body

What is bodyParser?
Parse incoming request bodies in a middleware before your handlers, available under the req.body property.

What is bcrypt?
bcrypt is a password hashing function

What is a cookie?
Is a small piece of data sent from a website and stored on the user's computer by the user's web browser while the user is browsing

What is a jwt?
https://jwt.io/introduction/
Is an open standard (RFC 7519) that defines a compact and self-contained way for securely transmitting information between parties as a JSON object

A way to authenticate/verify a user

What is token = jwt.sign({ foo: 'bar' }, 'shhhhh'); do?
It allows the browser to keep track of the current user
