# About-Me
Hi there 👋 !
About Me 👨‍💻
const express = require("express");

const app = express();

app.get("/info", (req, res, next) => {
  return res.json({
    name: "Omar.A",
    email: "temp.dev.56@gmail.com",
    role: "Backend Developer",
    about:
      "self-taught developer, focused on back-end development, \
      Passionate about software engineering. \
      Seeking to design, and build secure, scalable, and high-performing back-end systems.",
    availableForHiring: true,
  });
});

app.listen(3000, () => {
  console.log("Server running on port 3000");
});
Social & Contacts 📱
 

My Github Stats 📉


My Top Languages 📚


Tools I Usually Use 🛠️
                         
