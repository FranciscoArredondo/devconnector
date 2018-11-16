# DevConnector
> Small social network app aimed at developers built with the MERN stack. This was created as a brief introduction/exploration 
into full stack web development via the Udemy course ["MERN Stack Front To Back" by Brad Traversy](https://www.udemy.com/mern-stack-front-to-back). It was a fantastic course
and would highly recommend it to anyone interested in learning full stack web development. 

I plan to continue to implement new features and fix bugs, as I continue to learn.
I have deployed a live production version on heroku and can be visted at https://devconnectornetwork.herokuapp.com 
I would appreciate and welcome anyone to [try it out](https://devconnectornetwork.herokuapp.com/register) by signing up and create a profile.
If you have any comments or suggestions for improvements I would love to hear them. 

## Quick Start

```bash
# Install dependencies for server
npm install

# Install dependencies for client
npm run client-install

# Run the client & server with concurrently
npm run dev

# Run the Express server only
npm run server

# Run the React client only
npm run client

# Server runs on http://localhost:5000 and client on http://localhost:3000
```

You will need to create a keys_dev.js in the server config folder with

```
module.exports = {
  mongoURI: "YOUR_OWN_MONGO_URI",
  secretOrKey: "YOUR_OWN_SECRET"
};
```

You will also need to create a keys_dev.js in the client/src/ config folder with
```
module.exports = {
  githubClientId: "YOUR_GITHUB_CLIENT_ID",
  githubClientSecret: "YOUR_GITHUB_CLIENT_SECRET"
};

```

## App Info

### Author

Francisco Arredondo

### Contact

frarredo@gmail.com


### Version

1.0.0

### License

This project is licensed under the MIT License
