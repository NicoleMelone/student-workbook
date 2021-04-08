# UnderStanding Asynchronous Code, and API's

**1.** What is the difference between `asynchronous` code and `synchronous` code?
<!-- enter you answer in the space below -->
```
async can tell a method to wait for the response without interupting the entire code thereafter. It's a way to let things load without the user waiting too long for the rest of the page to load.
```
**2.** What is an event listener?
<!-- enter you answer in the space below -->
```
It is the part that watches for something to change then performs an action when it sees it.
```
**3.** What does the `O` represent in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
Open closed principle. Open means future developers should be able to add new features or components without breaking the existing code. Closed means there should be no breaking changes to existing functionality. 
```
**4.** What is a callback / higher order function?
<!-- enter you answer in the space below -->
```
A higher order is a function that takes another function as an argument and returns a function to it's callers. A callback is a function that is passed into another function with the expectation that the other function will call it.
```
**5.** What is a `promise`? How do you capture an error from a `promise`?
<!-- enter you answer in the space below -->
```
A promise uses a constructor to create the object, ti takes in 2 parameters a resolve and a reject, then it needs a condition to be met to determine resolve or reject. 
Using catch() method allows an error to be console.logged console.error(error)
```
**6.** Name three processes used to make requests over `HTTP`?
<!-- enter you answer in the space below -->
```
Axios, fetch, Ajax
```
**7.** What does the `API` acronym stand for?
<!-- enter you answer in the space below -->
```
Application Programming Interfaces
```
**8.** In the `MVC` design pattern, who is responsible for making calls to `APIs`?
<!-- enter you answer in the space below -->
```
The Service
```
**9.** What is the purpose of encapsulation in programming?
<!-- enter you answer in the space below -->
```
Helps prevent bugs from shared mutable state, helps the code to be cleaner and easier to read for future developers.
```
**10.** What is `HTTP` response code for a successful request?
<!-- enter you answer in the space below -->
```
then() is only for resolved promises and catch() is for rejected promises.
```
**11.** What is a 500 error?
<!-- enter you answer in the space below -->
```
It is an internal server error. It means something went wrong on the side of the server. It's letting the developer know there is an error in the connection. Could be the URL or parameters or lack of GET.
```