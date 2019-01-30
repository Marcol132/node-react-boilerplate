# Node React Boilerplate

One Paragraph of project description goes here

## Getting Started
```
#Install dependencies for server
npm install

#Install dependencies for client
npm run client-install

#Run the client & server with concurrently
npm run dev

#Run the Express server only
npm run server

#Run the React client only
npm run client

Server runs on http://localhost:5000 and client on http://localhost:3000
```
### Prerequisites

mLab account for your mongoURI link
google Oauth key (secret + public)
create a custom cookieKey

### Installing

You will need to create a dev.js file in /config

```
module.exports = {
    googleClientID: 'GOOGLE_CLIENT_ID',
    googleClientSecret: 'GOOGLE_CLIENT_SECRET',
    mongoURI: 'MONGO_URI',
    cookieKey: 'COOKIE_KEY'
};

```


### And coding style tests

Explain what these tests test and why

```
Give an example
```

## Deployment

I normaly deploy with Heroku, so the prod.js in /config is already there.
Just need to add you keys on Heroku Dashboard

## Built With

-Node.js = BackEnd
-React - Redux = Frontend
-mongoDb / mlab for NoSQL database

They call it MERN stack


