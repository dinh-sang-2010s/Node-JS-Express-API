# Node-JS-Express-API

- S1. Http protocol
- S2. Sever side rendering & Client side rendering
  - Server side rendering: return all html and data from server render from server.
  - client side rendering: return only html and js and render from client.
- S3. Express
  - npm init
  - npm install express
- S4. Nodemon & Debug
  - Nodemon save and restart server.
  - npm install -g nodemon --save-dev
  - "scripts": {"start": "nodemon --inspect index.js" }
- S5. Morgan
  - npm install morgan --save-dev
  - show logs of request
- S6. Template engines (Handlebars)
  - Express handlebars
  - npm install express-handlebars
- S7. Static file & SASS
  - npm install node-sass --save-dev
  - "watch": "node-sass -w src/resources/scss/ -o src/public/css/"
  - nodemon.json {
    "ext":"js json scss hbs"
    }
