# QuestionHub

QuestionHub is a social media application similar to the application Quora! Users can login and logout from the page to leave likes and answers to other questions/answers. Each post has a title that will explain the question needed to be answered.

Videozz is built with React/Redux on the frontend and GraphQL in the backend.

# FEATURES

**Login/Signup**

- Passwords are secured using BCrypt to generate a passord_digest. A user session_token is stored in the database to keep track of each user session. When a user successfully logs in, a session token is generated, stored in the database, and stored on the client-side as a browser cookie.

- There is also a demologin for the user to automatically login with a premade account


