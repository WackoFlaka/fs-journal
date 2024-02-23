# Intro to Server side concerns with JavaScript
01. What do the letters of the acronym `CRUD` stand for?

  > C - Create
  > R - Read
  > U - Update
  > D - Delete

02. Each action that `CRUD` represents maps to an HTTP request. What HTTP request does each `CRUD` action correspond to?

  > C - Create - POST
  > R - Read - GET
  > U - Update - PUT
  > D - Delete - DELETE

03. What does `ORM` stand for? Which `ORM` do we use when interacting with MongoDB

  > ORM stands for Object-relational mapping and we use mongoose when we interact with MongoDB

04. Which two `HTTP` request types include a body?

  > POST and PUT

05. In a/an _______ coding model, when you call a function, it returns only when the action has finished and stops your program for the time the action takes. Likewise in a/an _______ coding model, multiple things are allowed to happen at one time. When you perform an action, your program continues to run.  Fill in the blanks.

  > await and async 

06. What are the three types of data relationships? Provide an example of each.

  > One-To-One (Author- 1:1 -Address)
  > One-To-Many (Blog- 1:N -Comments)
  > Many-T0-Many (Book- N:M -Author)

07. What is middleware?

  > They are functions which are passed control during execution of asycnrhonous functions.

08. The ______ pipeline delivers information from the client while the ______ pipeline returns it. Fill in the blanks. 

  > | ANSWER HERE |

09. Demonstrate the pattern that is used to include a request query with the client's `HTTP` request providing the property `tag` and the value `winter`.

  > http://localhost:3000/api?tag=winter

10. What is a ***virtual property***?

  > Virtuals are additional fields for a given model.
