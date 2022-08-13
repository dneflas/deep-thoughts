# Deep Thoughts 💭

![license badge](https://img.shields.io/badge/license-MIT-blue)

## Description

Deep Thoughts is a MERN stack single-page social media application. The application uses a NoSQL Mongo database. An Apollo server is applied as middleware to an Express server. An Apollo Provider is used to communicate with the Apollo server. JSON Web Tokens is used for user authentication. GraphQL is used to build the API endpoints, and queries and mutations are used to fetch and modify server-side data. The application is deployed to Heroku.

## Technologies Used:

- ReactJS
- NodeJS
- MongoDB
- Mongoose ORM
- Express
- GraphQL
- JSON Web Tokens
- bcrypt package
- Apollo Server
- Apollo Client
- faker
- Heroku
  <br>

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Deployed Link](#deployed-link)
- [License](#license)
- [Questions](#questions)

  <br>

## Installation

Use the following command to download dependencies for the project:

```
npm install
```

  <br>

## Usage

![screenshot](./client/src/assets/images/screenshot.png)
</br>
The application allows users to sign up and create an account. On the home page, users will see a feed of all users thoughts with the username, creation date, time and the number of reactions. If logged in, a form to create a thought will conditionally render at the top, along with the user's friend list to the right of the page. On the me page, a feed of the logged in user's thoughts will appear, along with the friend list to the right, and a form to create a thought at the bottom. User's can view other user's profiles, see their friend list and add them as a friend.

<br>

## Deployed Link

[Deep Thoughts App](https://sleepy-reaches-36096.herokuapp.com/)
</br>

## License

This project is licensed under the [MIT License](https://choosealicense.com/licenses/mit/).  
 </br>

## Questions

[GitHub](https://github.com/dneflas)
