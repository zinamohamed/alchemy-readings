## Synchronous and Asynchronous JavaScript
    1) JavaScript is synchronous by default, meaning code cannot create new threads and run in parallel.
          - Lines are executed in series, one after another, at least that's how we've worked with them so far.
      - Asynchronous means that things can happen independently of the main program flow, computers are asynchornous by design.
      - A callback is a simple function that's passed as a value to another function, and will only be executed when the events happens.
      - Callbacks are great for simple things, but when you have a lot code starts to get complication very quickly!!
    2) This is where promises come in. Promises are one way to deal with asynchronous code without writing too many callbacks in your code.
        - Promises act as a proxy for a value that will eventually become available.
        - Once a promise is called new Promise():, it will sart a pending state. It takes an executor, which is some kind of function that we're using whose return results we need to control asynchronously.
        - A promise can be returned to another promise, creating a chain of promises.
    3) The FETCH API provides a JavaScript interface for accessing and manipulating parts of the HTTP pipelines.
        - The simplest use of fetch() takes one argument - the path to the resource you want to fetch - and returns a promise containing the response.
        - fetch () makes a network request to a url and returns a promise. It can go to any url, including your own server.
        


