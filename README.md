# Blog App using MERN Stack

Welcome to the Blog App repository! This application is built using the MERN (MongoDB, Express, React, Node.js) stack and comes with various functionalities to manage and share your blogs.


## Functionalities

- **Authentication:** Secure user authentication system to protect your blogs.
- **Create Blog:** Easily create and publish your blogs with a user-friendly interface.
- **Delete Blog:** Remove unwanted blogs with a simple delete option.
- **Update Blog:** Edit and update your blogs as your content evolves.
- **View Other User Blogs:** Explore and read blogs published by other users.


## Getting Started

To get started with this project, follow these steps:

1. Fork this repository

2. Clone this repository to your local machine:

```bash
git clone https://github.com/your-username/Blog-App-using-MERN-stack.git
```

3. Install the required dependencies for both the backend and frontend:

```bash
cd Blog-App-using-MERN-stack
cd server && npm install
cd ../client && npm install
```

4. Make a .env file in the server and copy the following line:
```bash
MONGO_URI = mongodb://127.0.0.1:27017/BlogApp
```


5. Configure the database connection in the backend. You can use MongoDB Atlas or a local MongoDB server.

6. Start the backend server:

```bash
cd server && npm start
```

7. Start the frontend application:

```bash
cd client && npm start
```


8. Access the application in your web browser at [http://localhost:3000](http://localhost:3000).


## Using Docker

1. Docker should be set up and installed.


2. Run the following command from the root of your project:

```bash
docker-compose up --build
```

3. Access the application in your web browser at [http://localhost:3000](http://localhost:3000).


4. Stop the containers:

```bash
docker-compose down
```

## Contributing

We welcome contributions from the community. If you'd like to contribute to this project, please feel free to open an issue or Make a PR.


## Acknowledgments

We would like to thank all contributors and the open-source community for their support.

---

Feel free to explore the codebase and start creating and sharing your blogs with the world! If you have any questions or need assistance, please don't hesitate to reach out.

Happy blogging!
