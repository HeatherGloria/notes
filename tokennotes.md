Things I'm not clear on:
---
######  What is the difference between a *cookie*, *token*, and a *jwt*?


#### The answers to the questions that Christian asked me and I should have know, and taken notes on earlier:

##### What are the two ways to access values from an object?
* dot notation:
objectName.propertyName;

* bracket notation:
objectName["propertyName"];

```JavaScript
> var person = {
    firstName:"John",
    lastName:"Doe",
    age:50,
    eyeColor:"blue"
};
```

* person.lastName;
* person["lastName"];

##### What is req.body?
* An object containing text parameters from the parsed request body, defaulting to {}.
Contains key-value pairs of data submitted in the request body

##### What is bodyParser?
* Parse incoming request bodies in a middleware before your handlers, available under the req.body property.

##### What is bcrypt?
* https://www.npmjs.com/package/bcrypt
 bcrypt is a password hashing function

##### What is a cookie?
* [HTTP cookies](https://developer.mozilla.org/en-US/docs/Web/HTTP/Cookies)
Is a small piece of data sent from a website and stored on the user's computer by the user's web browser while the user is browsing

##### What is a jwt?
* https://jwt.io/introduction/
* [site on jwt's](https://stormpath.com/blog/nodejs-jwt-create-verify)
Is an open standard (RFC 7519) that defines a compact and self-contained way for securely transmitting information between parties as a JSON object

* A way to authenticate/verify a user

##### What is a token = jwt.sign({ foo: 'bar' }, 'shhhhh'); do? How do you use it?
* [Doc that Jen sent me](https://docs.google.com/document/d/1E2fY7wRG35MmI-vcdZUhiXpH-x51UcfY8acxFQNynYw/edit)
It allows the browser to keep track of the current user
