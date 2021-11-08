# Intro to Server side concerns with JavaScript

**1.** What do the letters of the acronym `CRUD` stand for?
<!-- enter you answer in the space below -->
```
Create, Read, Update, Delete
```
**2.** Each action that `CRUD` represents maps to an HTTP request. What HTTP request does each `CRUD` action correspond to?
<!-- enter you answer in the space below -->
```
get, put, post and delete
```
**3.** What does `ORM` stand for? Which `ORM` do we use when interacting with MongoDB
<!-- enter you answer in the space below -->
```
object-relational mapping. We use Node.js
```
**4.** Which two `HTTP` request types include a body?
<!-- enter you answer in the space below -->
```
post and put
```
**5.** In a/an _______ coding model, when you call a function, it returns only when the action has finished and stops your program for the time the action takes. Likewise in a/an _______ coding model, multiple things are allowed to happen at one time. When you perform an action, your program continues to run.  Fill in the blanks.
<!-- enter you answer in the space below -->
```
synchronous, asynchronous
```

**6.** Fill in the missing piece of this snippet of code.
```js
import ______ from "_______"
let Schema = ________.Schema;
```
<!-- enter you answer in the space below -->
```
mongoose
```
**7.** What is middleware?
<!-- enter you answer in the space below -->
```
It is a 'body gaurd' in the code. Sometimes it changes code so that it can be understood. For example, when code comes in, it is passed as a JSON object, but that is not what our code is reading, so middleware will change it to the language we need. It also checks if you have authorization to access the data that you wanting to access. 
```
**8.** The ______ pipeline delivers information from the client while the ______ pipeline returns it. Fill in the blanks. 
<!-- enter you answer in the space below -->
```
data, delivery
```
**9.** 
Demonstrate the pattern that is used to include a request query with the client's `HTTP` request providing the property `tag` and the value `winter`.
<!-- enter you answer in the space below -->
```
async getAll(query = {}) {
    const winter = await dbContext.Winter.find(query).populate('creator', 'tag')
    return winter
  }

  ?tag=winter
```