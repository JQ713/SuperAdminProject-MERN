COSC 4351 - Group Prject
This project uses the following technologies:

- [React](https://reactjs.org) and [React Router](https://reacttraining.com/react-router/) for frontend
- [Express](http://expressjs.com/) and [Node](https://nodejs.org/en/) for the backend
- [MongoDB](https://www.mongodb.com/) for the database
- [Redux](https://redux.js.org/basics/usagewithreact) for state management between React components

## Medium Series

- [Build a Login/Auth App with the MERN Stack — Part 1 (Backend)](https://blog.bitsrc.io/build-a-login-auth-app-with-mern-stack-part-1-c405048e3669)
- [Build a Login/Auth App with the MERN Stack — Part 2 (Frontend & Redux Setup)](https://blog.bitsrc.io/build-a-login-auth-app-with-mern-stack-part-2-frontend-6eac4e38ee82)
- [Build a Login/Auth App with the MERN Stack — Part 3 (Linking Redux with React Components)](https://blog.bitsrc.io/build-a-login-auth-app-with-the-mern-stack-part-3-react-components-88190f8db718)

## Configuration

Make sure to add your own `MONGOURI` from your [mLab](http://mlab.com) database in `config/keys.js`.

```javascript
module.exports = {
  mongoURI: "mongodb+srv://cosc4351:houston23@cluster0-g0jwa.mongodb.net/test?retryWrites=true&w=majority",
  secretOrKey: "secret"
};
```
mongoDB: https://cloud.mongodb.com/user#/atlas/login  
login: jquintanilla713@gmail.com  
Password: houston23  

## Quick Start

```javascript
// Install dependencies for server & client
npm install 
and then...
npm run client-install

// Run client & server with concurrently
npm run dev

// Server runs on http://localhost:5000 and client on http://localhost:3000
```
admin user : admin@admin.com  
Password: 123456  

global admin : client1@email.com  
Password: 123456  

finance user : client2@email.com  
Password: 123456

sales user : client3@email.com  
Password: 123456

HR user : client4@email.com  
Password: 123456

engineering user : client5@email.com  
Password: 123456

unauhtorized user : coog@uh.edu  
Password: 123456
