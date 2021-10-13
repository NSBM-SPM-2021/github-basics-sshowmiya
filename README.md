# tomato-food-delivery-application

Tomato app is a full-stack system build in MERN.js which aims to offer a customer a range of food products to order. Then the customer can choose and order a menu build on its own.

The main features are:

- Complete guidance on the UI for the ordering process.
- 2 different roles (Role Based Access Control):
  - `Manager`: Can process the orders received in Real time, view a history, add new restaurants and new meals. Can change the order status.
  - `User`: Can order from the restaurants. Also view a orders history.
- Use of `state-machine` to validate transitions of order status.
- Follow React and Node.js best practices.

## Quick Start

```javascript
// Install dependencies for server & client
npm install && npm run client-install

// Run client & server with concurrently
npm run dev

// Server runs on http://localhost:5000 and client on http://localhost:3000
```

## MERNJS stack

- [React](https://reactjs.org) and [React Router](https://reacttraining.com/react-router/) for frontend.
- [Express](http://expressjs.com/) and [Node](https://nodejs.org/en/) for the backend.
- [MongoDB](https://www.mongodb.com/) for the database.
- [Redux](https://redux.js.org/basics/usagewithreact) for state management between React components.

## Demo

### Create Restaurant (Role: Manager)

![manager-login](https://recordit.co/CZ2wDzk7O4.gif)

### Order Food (Role: User)

Let's order food from the above restaurant.

![user-login](http://g.recordit.co/lFgzrDYcxY.gif)

![hosting](https://github.com/NSBM-SPM-2021/github-basics-sshowmiya/blob/master/screenshots/WhatsApp%20Image%202021-10-13%20at%2022.45.00.jpeg)
![hosting)(https://github.com/NSBM-SPM-2021/github-basics-sshowmiya/blob/master/screenshots/WhatsApp%20Image%202021-10-13%20at%2022.45.05.jpeg)
![testing](https://github.com/NSBM-SPM-2021/github-basics-sshowmiya/blob/master/screenshots/WhatsApp%20Image%202021-10-13%20at%2022.44.57.jpeg)
![action deploy](https://github.com/NSBM-SPM-2021/github-basics-sshowmiya/blob/master/screenshots/WhatsApp%20Image%202021-10-13%20at%2022.43.49.jpeg)



###JIRA

![issues](https://github.com/NSBM-SPM-2021/github-basics-sshowmiya/tree/master/JIRA%20screenshots.png)
![jira](https://github.com/NSBM-SPM-2021/github-basics-sshowmiya/tree/master/JIRA%20screenshots.png)

## Configuration

Make sure to add your own `MONGOURI` from your [mLab](http://mlab.com) database in `config/keys.js`.

```javascript
module.exports = {
  mongoURI: "YOUR_MONGO_URI_HERE",
  secretOrKey: "secret"
};
```
