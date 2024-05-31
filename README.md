# Book Store MERN stack project

Welcome to the Book Store MERN stack project! This project demonstrates the development of a Book Store application using the MERN stack, which includes MongoDB for the database, Express.js for the server-side framework, React for the front-end framework, and Node.js as the runtime environment.

The backend of this application starts with setting up a Node.js project from scratch. An Express server is configured to handle HTTP routes for the application. MongoDB is integrated using Mongoose, which provides a straightforward schema-based solution to model the application data. This includes creating a Book model that defines the structure of a book document in the MongoDB collection.

With the backend setup, CRUD (Create, Read, Update, Delete) operations for books are implemented. This includes routes to save a new book, retrieve all books, get a single book by its ID, update a book, and delete a book from the database. The Express router is used to organize these routes, making the server code more modular and maintainable. Additionally, Cross-Origin Resource Sharing (CORS) is configured to allow the client-side React application to communicate with the server.

On the front end, a React project is created using Vite, a fast build tool, and Tailwind CSS for styling. The React application is designed as a Single Page Application (SPA) with React Router for navigation between different pages, such as the books list, book details, and forms for creating and editing books. The books are displayed in a list, and each book's details can be viewed individually. Users can add new books, edit existing ones, and delete books as needed.

To enhance the user experience, the book list is shown as cards, and a modal is used for adding or editing books. Alerts and notifications are added to provide feedback to users for actions such as successfully adding or deleting a book. These enhancements ensure the application is not only functional but also user-friendly and visually appealing.

This project serves as an excellent learning resource for building a full-stack application with the MERN stack, covering the complete workflow from backend development and database integration to frontend design and user experience improvements.
