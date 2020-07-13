// Server for Robert Wes Thompson

const express = require("express");
const app = express();

//What I learned: Must include the app.use(express.static) method to point to the folder, ie, "public," which is where the CSS and image files are located.
app.use(express.static("public"));

//What I learned: Must use separate .get() method for each file, ie, "/"", style.css, and script.js

//Must also use the same filename for both .get() and res.sendFile statements.
app.get("/", function(req, res){
  res.sendFile(__dirname + "/index.html");
})

app.listen(3007, function(){
  console.log("Server sucessfully started on port 3007!");
})
