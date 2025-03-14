# Application Architecture, MVC Design Pattern

**1.** What are the Pillars of Object Oriented Programming (`OOP`)?
<!-- enter you answer in the space below -->
```
Encapsulation, Abstraction, Inheritance, Polymorphism
```
**2.** How would you access the `name` of the below object using the `property` variable?
```js
let staff = {
  name: "Tim",
  age: 26,
  job: "Code Monkey"
  }
let property = 'name'
```
<!-- enter you answer in the space below -->
```
let property = staff.name
```
**3.** What is Encapsulation?
<!-- enter you answer in the space below -->
```
An object maintaining a private state.
```
**4.** What does the S stand for in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
Single responsibility
```
**5.** What the difference between a `class` and an instance of a `class`?
<!-- enter you answer in the space below -->
```
A class is the "blueprints" of what the object will be and the instance is the actually object itself with specifics.
```
**6.** What is a `Proxy` object?
<!-- enter you answer in the space below -->
```
Takes an object and makes a copy so it can be manipulated then returned to as a string to be used else where in the Dom.
```

**7.** What is the purpose of the `MVC` pattern?
<!-- enter you answer in the space below -->
```
To keep things organized and easy to read. It allows future developers to access pieces of the code easily and manipulate things as needed. 
```
**8.** What is the job of the `Controller` in the `MVC` Pattern?
<!-- enter you answer in the space below -->
```
The controller takes info from the user on the screen and reports back to the service what is needed. Then once it recieves the info it brings it back to the user o the screen.
```

**9.** What is the job of the `Service` in `MVC`?
<!-- enter you answer in the space below -->
```
Manipulates data then passes the info to the Conroller to tell the user.
```
**10.** What is the job of the `Model` in `MVC`?
<!-- enter you answer in the space below -->
```
The model is where you create blueprints for your object to be accessed in the service and manipulated. 
```

