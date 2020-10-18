# 13-project
Module Project: Just Tech News, Back-End Edition
In this module, you’ll build the back end for your first completely full-stack application, Just Tech News—a tech news website where users can post, upvote, and comment on links to news articles. You’ll use Sequelize, an object-relational mapping (ORM) library, to simplify your MySQL queries, add password hashing so that users can create secure passwords, and connect your application to JawsDB, a MySQL add-on for Heroku. This project will set you up for next week’s project, in which you’ll add user authentication and the front end for the application.

## For `.env`

```plaintext
DB_NAME=''
DB_USER=''
DB_PW=''
```

## Run All Seeds

```bash
npm run seeds
# OR
node seeds/index.js
```
## By completing this module, you'll learn how to do the following:
* Implement the Sequelize ORM in a Node.js application.
* Define models that use datatype validations.
* Implement CRUD methods using Sequelize.
* Implement Sequelize associations to join one or more tables.
* Configure Heroku for deployment of an application using Sequelize & MySQL.
* Use the bcrypt package to hash password information and use environment variables to protect sensitive data.