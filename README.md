# 🌟 Problem 20: Use a Template Engine with Express 🌟  

Welcome to the 20th Node.js challenge! In this task, you'll set up an Express server and integrate the **Pug** template engine to render dynamic HTML pages. This will help you create reusable and dynamic views for your web applications. 🚀  

---  

## 📝 Problem Statement  

Create an Express server using the **Pug** template engine to render a dynamic HTML page that displays:  

1. A **title**  
2. A **message**  

---  

## 🎯 Learning Goals  

- Configure and use a template engine with Express.  
- Pass dynamic data from the server to the template.  
- Create reusable and dynamic HTML templates using **Pug**.  

---  

## 📂 Project Structure  

```bash  
20-template-engine-pug-node-problem/
├── views/
│   └── index.pug       # Pug template file
├── server.js           # Node.js server file
├── README.md           # Documentation for this problem
└── package.json        # Project configuration file  
```

---

## 🖥️ Code Explanation

`server.js`

This file sets up an Express server and configures it to use the Pug template engine. The `/` route renders the `index.pug` file with dynamic content passed as variables (`title` and `message`).

`views/index.pug`

This Pug template defines the structure of the dynamic HTML page, displaying the title and message passed from the server.

---

## 🚀 Features to Enhance

Once you complete the basics, you can try the following:

- **Add More Pages**: Create additional routes and templates for about, contact, or other sections.

- **Reusable Layouts**: Use Pug mixins or layouts to create reusable templates.

- **Dynamic Data**: Pass dynamic data such as user details or items fetched from a database.

---

## 🧠 What You’ll Learn

- The basics of integrating template engines with Express.

- How to render dynamic HTML pages in Node.js.

- The syntax and features of the Pug template engine.

---

## 🤝 Contribute

Have ideas to improve this problem or want to add more challenges? Feel free to fork this repository and create a pull request. Contributions are always welcome! ❤️
