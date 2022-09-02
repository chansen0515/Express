
# NodeJS

Express
## Lessons Learned

Sept 1-2 2022

RESTFUL APIs
- POST
- PUT
- GET
- DELETE


EXPRESS
- framework used to make web servers
```bash
const express = require('express');
const app = express();
```

NODEMON
- automatically updates server without restarting it manually

JOI package
- input validation. Used to validate inputs given by the client 
(like if the name they input is string, etc.)

MIDDLEWARE
- Function that acts as middleman to control the response given //medyo di pa clear
```bash
  app.use(function(req,res,next)){

    //insert code here

    next();
  }
```


