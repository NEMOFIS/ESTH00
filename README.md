# ESTH00
esteh 00

const express = require('express')
const app = express()

app.get('/', function (req, res) {
  res.send('Hello World')
})

app.listen(3000)


This is a Node.js module available through the npm registry.

Before installing, download and install Node.js. Node.js 0.10 or higher is required.

If this is a brand new project, make sure to create a package.json first with the npm init command.

Installation is done using the npm install command:

$ npm install express
Follow our installing guide for more information.

The quickest way to get started with express is to utilize the executable express(1) to generate an application as shown below:

Install the executable. The executable's major version will match Express's:

$ npm install -g express-generator@4
Create the app:

$ express /tmp/foo && cd /tmp/foo
Install dependencies:

$ npm install
Start the server:

$ npm start
View the website at: http://localhost:3000
