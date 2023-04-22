---
title: "Getting Started With Express!"
datePublished: Sat Apr 08 2023 16:07:08 GMT+0000 (Coordinated Universal Time)
cuid: clg865jc0000509ldckf20jpp
slug: getting-started-with-express
cover: https://cdn.hashnode.com/res/hashnode/image/upload/v1680966876774/bf53fe34-4354-4136-a4c1-7a2feb518257.jpeg
ogImage: https://cdn.hashnode.com/res/hashnode/image/upload/v1680970015316/8d6d8b8d-d405-4ad9-8edb-754bc7bb92d3.jpeg
tags: web-development, nodejs, expressjs-cilb5apda0066e053g7td7q24

---

Node.js has revolutionized the world of web development with its ability to run server-side JavaScript code. One of the most popular frameworks for building web applications with Node.js is Express.js. In this article, we will explore the benefits of using Express.js and how it can help developers create high-performance and scalable web applications.

Express.js is an open-source web application framework that provides a wide range of features and utilities for web application development. One of its key features is routing, which allows developers to define the URLs and endpoints for their applications. Express.js provides a simple and easy-to-use API for defining routes, making it easy for developers to create RESTful APIs and web applications.

Another key feature of Express.js is middleware. Middleware is a function that sits between the request and response objects and can perform tasks such as logging, authentication, and compression. Express.js provides a wide range of middleware that can be easily integrated into your application, making it easy to add additional functionality as needed.

Express.js also supports template rendering, which makes it easy to generate HTML pages and other types of content dynamically. It provides a variety of template engines such as EJS, Pug, and Handlebars, making it easy for developers to choose the one that best suits their needs.

One of the biggest advantages of Express.js is its flexibility. It is designed to be modular and extensible, allowing developers to customize and extend it to meet the specific needs of their application. This makes it easy to build complex applications that require advanced functionality.

Another advantage of Express.js is its extensive community support. With a large and active community, developers can easily find resources and support when using Express.js. This community has contributed to a vast array of third-party packages and tools that make it even easier to work with Express.js.

In conclusion, Express.js is an excellent choice for building web applications with Node.js. Its wide range of features, utilities, flexibility, and community support make it a powerful and easy-to-use framework for creating high-performance and scalable web applications. Whether you are building a simple API or a complex web application, Express.js has the tools and features you need to get the job done.

**Express is a minimal and flexible Node.js web application framework that provides a robust set of features for web and mobile applications.**

### **Let's dive into Express!!**

**1\. Installation:**

```bash
npm install express
```

**2\. Hello World Server:**

```bash
const express = require('express')
cont app = express()
const PORT = 8000;

app.get('/', (req,res)=>{
res.send("Hello World")
})

app.listen(PORT, () =>{
console.log(`App is listening on port ${PORT}`)
})
```

**Curious to see how this will look on the Web?**

[Click Me](https://3bq2ixzihz9x.runkit.sh/) to see the response.

**3\. Basic Routing:**

```bash
//Get
app.get('/', (req,res)=>{
res.send("Hello World")
})

//Post
app.post('/', (req,res)=>{
res.post('POST req.body:', req.body)
})

//Delete
app.get('/:id', (req,res)=>{
res.delete('DELETE req for id', req.params.id)
})
```

**4\. Static File Serving:**

```bash
app.use(express.static(__dirname+'Public'));
```

**5\. Logging All Routes:**

```bash
app._router.static.forEach(function(r)
if(r.route&&r.route.path){
console.log(r.route.path)
}
});
```

**6\. Defining Routes In A Different File:**

**File:** `/routes/users.js`

```bash
//File Path: /routes/users.js
const express = require('express')
const router = express.router();

//get from the database
router.get('/', (req,res)=>{
const user = [];
res.send(user);
});

//get from database
router.get('/:id', (req,res)=>{
const user = {}
res.send(user)
});

//save user to database
router.post('/', (req,res)=>{
const user = req.body;
res.send({staus:, 'Success'});
});

module.exports = router;
```

**7\. Adding routes from:** `/routes/users.js`

```bash
app.use('/user',require('./routes/user'));
```

**8\. Redirecting:**

```bash
//sends a 302
router.get('/old-path',(req,res)=>{
res.redirect('/temp-new-path');
});

//sends a 301
router.get('old-path', (req,res)=>{
res.redirect(301. '/permanent-new-path');
});
```

### **Thank you!!**