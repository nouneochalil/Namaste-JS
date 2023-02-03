-fetch->webAPI ->used to make network call  ->
- fetch goes and request for a API call and return a promise.->we have to pass a callback function which will be executed once this promise results -> 
Microtask Queue -> it has hiegher priority than callback queue.
all the call back function which comes from PROMISES and mutation observerwill go inside micro task queue.
mutation observer ->it observes any mutation in the dom tree or not.if there is some mutation it can execute some call back function.
Starvation of callback queue -> if there is 