# Kanbas Learning (Node.js Backend) 🚀

**End-To-End Deployed Application:** [Kanbas Learning](https://kanbas-react-web-app-f24.netlify.app/#/Kanbas)

**Backend for Kanbas Learning (Canvas Clone)**

This repository contains the backend code for the **Kanbas Learning** platform, a Canvas clone with various features like user authentication, course management, and quizzes. The backend is built with **Node.js** and **Express.js**, and it is responsible for handling data requests, managing users, courses, and quizzes, and integrating with the frontend.

### **Features** ✨

- **User Authentication** 🔐: 
  - Express Session-based authentication system.
  - User roles: **Student** and **Faculty**.
  - Sign-up, login, and role-based access.

- **Course Management** 📚:
  - **Faculty** can create, update, and delete courses.
  - Students can view published courses and enroll or unenroll.

- **Module Management** 📑:
  - Faculty can add, edit, or delete modules within each course.

- **Assignment Management** 📃:
  - Faculty can add, update, or delete assignments for each course.
  - Students can view assignments within courses.

- **Quizzes** 📝:
  - Faculty can create quizzes with different types of questions (MCQ, FIB, True/False).
  - Students can attempt quizzes and see their scores.
  - Faculty can configure quiz settings, such as the number of attempts and answer visibility.

### **Technologies Used** ⚙️
- **Node.js**: JavaScript runtime for building the backend.
- **Express.js**: Web application framework for Node.js.
- **MongoDB**: NoSQL database for storing user data, courses, quizzes, and other information.
- **Mongoose**: ODM (Object Data Modeling) library for MongoDB to simplify database interactions.

---