# Blogging Website Version 2.0
*For **Hacktoberfest** please refer [Contributing.md](https://github.com/Prashant0664/Blog-website/blob/master/CONTRIBUTING.md)* <br/>

For older version checkout the branch named *version1*

## Table of Contents
- [Introduction](#introduction)
- [New Features](#new-features)
- [Demo](#demo-link)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

---

## Introduction
Welcome to the Blogging Website project! This is a web application built using the MERN (MongoDB, Express.js, React.js, Node.js) stack. It allows users to create and manage their blogs, post projects, follow other users, comment on blogs, save content, bookmark blogs, like blogs and a lot more. The application also includes features such as email verification for user registration and Redux for state management.

---

## New Features:
🔥 **Like:** Users can now like Blogs and can see their liked blogs in profile.
🔥 **Filter:** User can now filter the content from dropdown menu below Navbar.
🔥 **Share:** User can now share blogs on social media using share button.
🔥 **Use of Params:** Blog Article now use params decreasing the coupling and increasing speed.
🔥 **Optimised:** More optimised than ever.
🔥 **User Frinedly:** More user friendly tha ever.

---

## Demo Link: 

is provided in this repository

---


## Features
Here are some of the key features of this Blogging Website:

🔥 **User Authentication and Profiles:** Users can create and manage their profiles, with email verification for account security.

🔥 **Blogging:** Users can create and publish their blogs with rich text formatting.

🔥 **Sharing:** Users can share any blogs on social media platforms;

🔥 **Filter Blogs:** Users can search other users and filter content according to category.

🔥 **Project Posting:** Users can share and showcase their projects on their profile.

🔥 **Social Features:** Users can follow other users, comment on blogs, and save, like and bookmark content they like.

🔥 **Responsive Design:** The website is designed to work seamlessly on various screen sizes and devices.

🔥 **Secure:** The application follows best practices for security, including password hashing and user authentication.

🔥 **Content Management:** Users can easily edit, delete, or download their own posts.

---

## Technologies Used
The Blogging Website is built using the following technologies:

- **MERN Stack:**
  <br/>
  💫 MongoDB: A NoSQL database used to store user data, blogs, and other application data. <br/>
  💫 Express.js: A Node.js web application framework used for building the server.<br/>
  💫 React.js: A JavaScript library for building the user interface.<br/>
  💫 Node.js: A JavaScript runtime used for server-side code execution.<br/>

- **Additional Technologies:**<br/>
  💫 Redux: Used for state management within the React application.<br/>
  💫 Nodemailer: Used for email verification and sending email notifications.<br/>

---

## Getting Started
To set up this project locally, follow the instructions below.

### Prerequisites
Before you begin, make sure you have the following installed on your system:
- Node.js and npm (Node Package Manager)
- Git

 Install the backend dependencies:
   ```
   cd backend
   npm install
   ```

 Install the frontend dependencies:
   ```
   cd ../client
   npm install
   ```

 Set up your MongoDB database and configure the connection details in the backend's `.env` file.

 Start the backend server:
   ```
   cd ../backend
   npm start
   ```

 Start the frontend development server:
   ```
   cd ../client
   npm start
   ```

 Open your web browser and navigate to `http://localhost:3000` to access the Blogging Website.
