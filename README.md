# JavaScript Core & Advanced Demos

## 🚀 About the Tasks
I built three interactive web apps—a Counter, a To-Do List, and a Quiz App—to practice and demonstrate my JavaScript skills. 

## 🧠 Core JavaScript Concepts Used
* **Scope & Closures:** Used in the Counter app to protect the 'count' variable so outside code can't accidentally break it.
* **Hoisting:** Demonstrated in the Counter app by calling the initialization functions before they are declared in the code.
* **DOM Manipulation & Events:** Used in the To-Do list to dynamically add and remove HTML list items when buttons are clicked.
* **Promises:** Used a Promise simulation in the Quiz app to handle data loading smoothly as if it were fetching questions from a real live server.

## 🎓 Advanced JavaScript Concepts Explained

### 1. The Prototype Chain
In JavaScript, objects have a hidden link to a parent object called a prototype. If I look for a variable or function on an object and it isn't there, JavaScript automatically searches up this "prototype chain" to the parent. It keeps going until it finds it or hits the end of the chain (`null`). This is how JavaScript handles inheritance.

### 2. ES6+ Syntax
I use modern shortcuts to keep my code clean and prevent crashes:
* **Destructuring:** Unpacking values from objects instantly (`const { name, age } = user`).
* **Spread (`...`):** Making fast, clean copies of arrays and objects without changing the original data.
* **Optional Chaining (`?.`):** Safely reading deep data without crashing the app if a parent property is missing.

### 3. Iterators and Generators
* **Iterators** step through a list of data one by one using a `.next()` method that tracks the position.
* **Generators** are special functions (written as `function*`) that can pause their execution using the `yield` keyword and resume exactly where they left off later when called again.

### 4. ES Modules vs CommonJS
* **ES Modules** use `import` and `export`. They are the modern standard for browsers and analyze code structure before it runs.
* **CommonJS** uses `require()` and `module.exports`. It is older, used mostly in traditional Node.js environments, and loads files dynamically while the code runs line-by-line.
