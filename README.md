# Tech-Blog


  <div align="center">
  <h1 align="center">tech blog</h1>
  <h3>Codebase for the tech blog platform</h3>
  <h3>◦ Developed with the software and tools below.</h3>
  <p align="center"><img src="https://img.shields.io/badge/-Node.js-004E89?logo=Node.js&style=social" alt='Node.js\' />
<img src="https://via.placeholder.com/1/0000/00000000" alt="spacer" /><img src="https://img.shields.io/badge/-Express.js-004E89?logo=Express.js&style=social" alt='Express.js\' />
<img src="https://via.placeholder.com/1/0000/00000000" alt="spacer" /><img src="https://img.shields.io/badge/-MySQL-004E89?logo=MySQL&style=social" alt='MySQL\' />
<img src="https://via.placeholder.com/1/0000/00000000" alt="spacer" /><img src="https://img.shields.io/badge/-Sequelize-004E89?logo=Sequelize&style=social" alt='Sequelize\' />
<img src="https://via.placeholder.com/1/0000/00000000" alt="spacer" /><img src="https://img.shields.io/badge/-Handlebars-004E89?logo=Handlebars&style=social" alt='Handlebars\' />
<img src="https://via.placeholder.com/1/0000/00000000" alt="spacer" /><img src="https://img.shields.io/badge/-Dotenv-004E89?logo=Dotenv&style=social" alt='Dotenv\' />
<img src="https://via.placeholder.com/1/0000/00000000" alt="spacer" /><img src="https://img.shields.io/badge/-Bcrypt-004E89?logo=Bcrypt&style=social" alt='Bcrypt"' />
<img src="https://via.placeholder.com/1/0000/00000000" alt="spacer" />
  </p>
  </div>


  ## 📚 Table of Contents
  - [📚 Table of Contents](#-table-of-contents)
  - [🔍 Overview](#-overview)
  - [🌟 Features](#-features)
  - [📁 Repository Structure](#-repository-structure)
  - [💻 Code Summary](#-code-summary)
  - [🚀 Getting Started](#-getting-started)
  

  ## 🔍 Description

 This is a Node.js project with a focus on building a blogging platform. The project includes a server, client-side rendering, and database integration. The server is built using Express.js and the client-side is built using Handlebars.js. The project also includes a database schema for storing user data, posts, and comments.

  ## 🌟 Features

 Node.js, Express.js, Handlebars.js, Blogging platform, User data, Posts, Comments, Database integration


## 💻 Code Summary

<details><summary>\controllers</summary>

| File | Summary |
| ---- | ------- |
| api-routes.js |  The code defines a router for an Express.js application that handles various HTTP requests and interacts with the Sequelize ORM to perform CRUD (create, read, update, delete) operations on models. |
| html-routes.js |  The code defines an Express.js router that handles requests for a social media platform, including rendering homepage, dashboard, individual post pages, and login/logout functionality. |
| index.js |  The code defines an Express.js router and imports two sets of routes, then uses them in the order they were imported, exporting the router for use in the application. |

</details>

---

## Installation

To run this application locally, you'll need Node.js and a MySQL database set up on your machine.

1. Clone the repository: ```git clone```

2. Install the dependencies: ```npm i```

3. Create a `.env` file in the root directory with the following contents:
```bash
DB_NAME='your_database_name'
DB_USER='your_username'
DB_PASSWORD='your_password'
```
4. Run the ```schema.sql``` in your MySQL database to create the necessary database.

5. Start the server: ```node server.js```

6. Visit ```http://localhost:3000``` in your local browser.

 
