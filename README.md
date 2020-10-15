# Node Deployment Module Project

In this challenge, you will **deploy** an API of your choosing to `heroku`.

## Instructions

You are allowed, and **encouraged**, to collaborate with other peers. Please follow the twenty-minute rule, before seeking support from your PM and Instructor.

### Task 1: Minimum Viable Product

Initial Commit

Git Ignore: npx gitignore node 
Package.json: npm init -y
Nodemon: npm i -D nodemon
Express: npm i express helmet
Create Folders and Files: 
  - index.js
  - api (folder)
    - server.js
Build out basic files:
  server.js
    import express to create basic server/endpoint
  index.js
    listen for server to eventually be sent to PORT || environment
Build out heroku server
Create new app on heroku > Deploy
(Add another environment to server.json statement)


Pick any API, could be one of your past projects, and deploy it to `heroku`.

### Task 2: Stretch Goal

- add support for environment variables using `.env` files. You can use the [dotenv](https://www.npmjs.com/package/dotenv) npm module.
