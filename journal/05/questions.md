# Intro to Server side concerns with JavaScript
01. What do the letters of the acronym `CRUD` stand for?

  > Create, Read, Update, Delete

02. Each action that `CRUD` represents maps to an HTTP request. What HTTP request does each `CRUD` action correspond to?

  > C: Post
  R: Get
  U: Put
  D: Delete

03. What does `ORM` stand for? Which `ORM` do we use when interacting with MongoDB

  > ORM stands for Object Relational Mapping, which is a layer between our object-oriented programs and databases that helps to translate the information in both directions. Mongoose is a popular ORM that we use when interacting with MongoDB.

04. Which two `HTTP` request types include a body?

  > Put (update) and Post (create)

05. In a/an _______ coding model, when you call a function, it returns only when the action has finished and stops your program for the time the action takes. Likewise in a/an _______ coding model, multiple things are allowed to happen at one time. When you perform an action, your program continues to run.  Fill in the blanks.

  > asynchronous; synchronous

06. What are the three types of data relationships? Provide an example of each.

  > • one-to-one: 
  • one-to-many: The bucketing method is a good way to handle one-to-many (1:M) cases such as paginating comments that could grow indefinitely.
  •many-to-many:

07. What is middleware?

  > Middleware is software that helps separate applications communicate with each other in meaningful ways. The ORM is a perfect example of middleware.

08. The ______ pipeline delivers information from the client while the ______ pipeline returns it. Fill in the blanks. 

  > Request; response

09. Demonstrate the pattern that is used to include a request query with the client's `HTTP` request providing the property `tag` and the value `winter`.

  > const res = await axios.get('http://localhost:3000/?tag=winter')

10. What is a ***virtual property***?

  > A virtual property is sort of like another schema attached to the current schema with matching properties mapped over. For example, if we want to link a location to missions that occurred there, we could create a virtual property showing that the 'missionId' property in the location schema should match the '_id' property in a mission. Then we can access whatever information we want from the mission dynamically, instead of updating mission data in both places. Pretty dang sweet.
