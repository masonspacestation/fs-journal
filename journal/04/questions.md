# Understanding Asynchronous Code, and API's
01. What is the difference between `asynchronous` code and `synchronous` code?

  > Synchronous code runs from start to finish until the code ends.
  Asynchronous code can be paused to wait for a promise to be fulfilled before it moves to the next line. Expecially useful for alerts asking the user for a response, or for receiving data from an API and formatting it into the structure of our data model.

02. What is an event listener?

  > An event listener observes the state of a given item and can call a function or method based on the listener's criteria.
  In our case, we have been watching arrays in the AppState, and acting on them based on new equivalencies being made (watches for '='), or for changes in the length of the array.

03. What does *REST* stand for, and in simple terms what does it mean??

  > REST stands for "REpresentational State Transfer".
  Simply put, it means that data received from an API will be representative of the current state of the requested resource.
  The information will be the same, regardless of who asks for it, and regardless of prior requests. A RESTful API will allow the developer to perform actions with the data.

04. What is a callback / higher order function?

  > A callback function is a function that performs a task that may take longer, and "calls back" with the result when it's finished. This can help with load times, allowing processes to take place in the right order, but without waiting around for everything to be ready.

05. What is a `promise`? How do you capture an error from a `promise`?

  > A promise is a way of making JavaScript slow down and wait for a response before continuing with the next line of code. It helps to make sure certain functions have all the information they need to carry out their task correctly, like a response from an API, or a user input like a confirmation alert.
  Errors can be caught by using a catch() method. We can tell the program what to do if the request is denied or if a user response comes back falsy.

06. Name three processes used to make requests over `HTTP`?

  > Get, post, put, delete

07. What does the `API` acronym stand for?

  > Application Programming Interface

08. What must you do in order to `await` a promise inside of a function?

  > Need to declare 'async' at the beginning of the function name.

09. What is the purpose of encapsulation in programming?

  > Encapsulation is a way of bundling data so that it is only visible to other parts of the code that are specifically granted access.
  There are a few different reasons why this is important:
    • We can make small changes with small effort. If we change the name or value of something that is referenced throughout the code stack, the change is reflected all throughout. We don't need to track down every reference and change them manually.
    • Access to certain portions of an application are limited for security and stability.

10. What is `HTTP` response code for a successful request?

  > 200 — OK

11. What is a 400 error?

  > 400 is a "Bad Request" error, meaning that the server sees or assumes an issue on the client side, and it cannot or will not process the request.
