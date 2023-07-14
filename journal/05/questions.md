# Intro to Server side concerns with JavaScript
01. What do the letters of the acronym `CRUD` stand for?

  > Create, Read, Update, Delete

02. Each action that `CRUD` represents maps to an HTTP request. What HTTP request does each `CRUD` action correspond to?

  > C= .post() R= .get() U= .put() D= .delete()

03. What does `ORM` stand for? Which `ORM` do we use when interacting with MongoDB

  > Object Relational Mapper. We use mongoose to interact with mongoDb.

04. Which two `HTTP` request types include a body?

  > .post() and .put()

05. In a/an _______ coding model, when you call a function, it returns only when the action has finished and stops your program for the time the action takes. Likewise in a/an _______ coding model, multiple things are allowed to happen at one time. When you perform an action, your program continues to run.  Fill in the blanks.

  > Synchronous and Asynchronous

06. What are the three types of data relationships? Provide an example of each.

  > One to Many, i.e pages within a book.
  > One to One, 
  > Many to Many, i.e an Author to a book or a book to an author.

07. What is middleware?

  > Application that serves as a path from your database to your client. i.e: an API

08. The ______ pipeline delivers information from the client while the ______ pipeline returns it. Fill in the blanks. 

  > request ,response

09. Demonstrate the pattern that is used to include a request query with the client's `HTTP` request providing the property `tag` and the value `winter`.

  > ?tag=winter (?key=value pattern)

10. What is a ***virtual property***?

  > A virtual property is an additional property for the model being used. These do not persist
