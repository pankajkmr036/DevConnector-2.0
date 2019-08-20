# DevConnector 2.0

> Social network for developers
An online portal for developers around the world to connect with each other and share their experiences and knowledge. Complete profile of a developer is displayed to anyone using the app.
• The app has an extensive backend API with Node.js and Express.
• Private routes are protected using JSON Web Tokens(JWT)
• A front end React App integrated to work with the API.
• The app state management is done in an elegant way using Redux.
• Application is successfully deployed on Heroku.com.
Followed es6 syntax.

## Quick Start

```
# change default.json file in config folder

# this file is located in config/default.json

# add uri of your mongodb connection for example

 "mongoURI": "mongodb://localhost/dev-social",
 
```

```bash
# Install server dependencies
npm install

# Install client dependencies
cd client
npm install

# Run both Express & React from root
npm run dev

# Build for production
cd client
npm run build
