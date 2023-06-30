# Blog-o-Sphere Website - MERN Stack

Blog-o-Sphere is an assesssment test given by BOSON TECH to test full-stack proficiency. The website uses the MERN (MongoDB, Express.js, React, Node.js) stack to run a blogging wesbite with user authentication using jwt token. 

The blog website allows users to create, read, update, and delete blog posts. By utilizing the power of the MERN stack, this project demonstrates my proficiency in both front-end and back-end development. I have worked with React for the front-end user interface, Express.js for the back-end server, and MongoDB as the database to store the blog post data.
## Demo

https://github.com/parth-khanolkar/Blog-website-Boson-Assessment/assets/75361189/31f5e929-d9b7-41dc-9cfe-7e6f060a8056


## Prerequisites

Before running the project, make sure you have the following software installed:

- Node.js (v14 or above)
- MongoDB (Make sure the MongoDB service is running)

## Getting Started

To run the blog website locally, follow these steps:




1. Clone the repository to your local machine using the following command:

   ```
   git clone https://github.com/parth-khanolkar/Blog-website-Boson-Assessment.git
   ```

2. Navigate to the project directory:

   ```
   cd Blog-website-Boson-Assessment
   ```

### Backend Setup

1. Open a terminal and navigate to the `server` directory:

   ```
   cd server
   ```

2. Install the dependencies by running the following command:

   ```
   npm install
   ```

3. Create a `.env` file in the `backend` directory and add the following environment variables:

   ```
   CONNECTION_URL = <your-mongodb-connection-string>
   ```

4. Start the backend server by running the following command:

   ```
   npm start
   ```

   The backend server will start running on `http://localhost:5000`.

### Frontend Setup

1. Open another terminal and navigate to the `client` directory:

   ```
   cd client
   ```

2. Install the dependencies by running the following command:

   ```
   npm install
   ```

3. Start the frontend development server by running the following command:

   ```
   npm start
   ```

   The React development server will start running on `http://localhost:3000`, and the browser will automatically open the website.

## Usage

Once the project is set up and running locally, you can access the blog website by visiting `http://localhost:3000` in your web browser. From there, you can explore the website, create new blog posts, edit existing ones, and delete posts as needed.

## Additional Information

- The backend server is built using Express.js and provides a RESTful API to handle CRUD operations on blog posts.
- The frontend is built using React and communicates with the backend API to fetch and manipulate blog post data.
- The MongoDB database is used to store the blog post information.

## Credits

This project was developed as part of the MERN stack assessment test.
