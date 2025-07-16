# Student Management System - Capstone Project

## Project Idea

The **Student Management System** is a full-stack web application built using the MERN stack (MongoDB, Express.js, React, Node.js) to manage student records efficiently. The system allows users to perform CRUD (Create, Read, Update, Delete) operations on student data, including details such as name, email, roll number, and phone number. It features a clean, responsive frontend with a modern design using Tailwind CSS and a robust backend with RESTful APIs. Additionally, the system includes a search functionality to filter students by name or roll number, making it user-friendly and scalable for educational institutions.

### Key Features
- **Add Students**: Create new student records with validation for unique email and roll number.
- **View Students**: Display a list of students in a table format with search functionality.
- **Edit Students**: Update existing student records through an intuitive form.
- **Delete Students**: Remove student records with a confirmation prompt.
- **Responsive Design**: Ensures accessibility across devices using Tailwind CSS.
- **RESTful API**: Backend APIs for seamless communication between frontend and MongoDB.

## Capstone Journey: Day-by-Day Plan

The capstone project will be developed over a 10-day period, with each day dedicated to specific tasks to ensure a structured and efficient development process. Below is the detailed plan:

### Day 1: Project Setup and Planning
- Initialize the project repository and set up Git.
- Create the project structure for the MERN stack (`client` and `server` folders).
- Install dependencies for Node.js (Express, Mongoose, CORS, dotenv) and React (Axios, Tailwind CSS).
- Set up MongoDB locally or on MongoDB Atlas.
- Define the project scope, database schema, and API endpoints.
- Create the initial `README.md` with project overview and plan.

### Day 2: Backend Development - Database and Models
- Set up MongoDB connection in `server/config/db.js`.
- Create the `Student` model in `server/models/Student.js` with fields: name, email, rollNo, phone.
- Test the database connection and schema using a MongoDB client (e.g., Compass).

### Day 3: Backend Development - API Routes
- Implement RESTful API routes in `server/routes/students.js` for:
  - GET `/api/students` (fetch all students).
  - POST `/api/students` (add a student).
  - PUT `/api/students/:id` (update a student).
  - DELETE `/api/students/:id` (delete a student).
  - GET `/api/students/search` (search students by name or roll number).
- Set up the Express server in `server/server.js`.
- Test API endpoints using Postman.

### Day 4: Backend Testing and Validation
- Add input validation in the backend to ensure unique email and roll number.
- Implement error handling for API responses.
- Test edge cases (e.g., duplicate entries, invalid inputs).
- Finalize and document the API in the `README.md`.

### Day 5: Frontend Development - Setup and Components
- Configure Tailwind CSS in the React app (`client/tailwind.config.js` and `client/src/index.css`).
- Create core React components:
  - `Navbar.jsx` for the header.
  - `StudentForm.jsx` for adding/editing students.
  - `StudentList.jsx` for displaying and managing student records.
- Set up Axios for API calls.

### Day 6: Frontend Development - Student Form
- Implement the `StudentForm` component with input fields for name, email, roll number, and phone.
- Add form validation and submission logic using Axios to call the POST API.
- Style the form using Tailwind CSS for a clean, modern look.
- Test form submission and error handling.

### Day 7: Frontend Development - Student List and Search
- Implement the `StudentList` component to display students in a responsive table.
- Add search functionality to filter students by name or roll number using the search API.
- Implement edit and delete buttons with Axios calls to the respective APIs.
- Style the table and buttons with Tailwind CSS.

### Day 8: Frontend - Edit Functionality and UI Polish
- Add edit functionality in `StudentList.jsx` to populate the form with existing student data.
- Implement update logic using the PUT API.
- Enhance UI with hover effects, loading states, and confirmation dialogs for delete operations.
- Test the entire CRUD flow (create, read, update, delete).

### Day 9: Testing and Debugging
- Perform end-to-end testing of the application (frontend and backend).
- Test responsiveness on different screen sizes (mobile, tablet, desktop).
- Debug any issues with API calls, form validation, or UI rendering.
- Optimize performance (e.g., reduce unnecessary API calls).

### Day 10: Documentation and Deployment Preparation
- Update `README.md` with detailed setup instructions, API documentation, and screenshots.
- Prepare the backend for deployment (e.g., configure environment variables for MongoDB Atlas).
- Prepare the frontend for deployment (e.g., build the React app).
- Test the build locally and push the final code to the Git repository.
- Optionally deploy to platforms like Render (backend) and Vercel (frontend).



