# CRUD with Nodejs, Express and Mongodb

npm init

npm install express --save


Sample:
var express = require('express');
var app = express();app.get('/', function (req, res) {
  res.send('Hello World!');
});app.listen(3000, function () {
  console.log('Example app listening on port 3000!');
});


node app.js


After running the command, load http://localhost:3000/ in a browser to see the output. You should also see “Example app listening on port 3000!” get logged to the command line.

Happy coding :)

CRUD :

![](docs/screenshot.png)

