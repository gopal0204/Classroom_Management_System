<h1 align="center">
    Classroom MANAGEMENT SYSTEM
</h1>

<h3 align="center">
Streamline classroom management, class organization, and add students and faculty.<br>
Seamlessly track attendance, assess performance, and provide feedback. <br>
Access records, view marks, and communicate effortlessly.
</h3>


# About

The Classroom Management System is a web-based application built using the MERN (MongoDB, Express.js, React.js, Node.js) stack. It aims to streamline school management, class organization, and facilitate communication between students, teachers, and administrators.

## Features

### Individualized Mark Tracking:
- Students should be able to view their marks for each assignment or assessment
within a subject.
- Teachers should have the capability to input and update marks for individual
students.
### Attendance Recording:
- Students should be able to mark their attendance for each class session.
- Teachers should have access to attendance records for each class session.
### Reminder System:
- Students should be able to set reminders for upcoming classes or assignments.
- Reminders should be customizable and timely.
### Weekly Timetable Management:
- Teachers should be able to create and update weekly timetables for their classes.
- Students should have easy access to their class timings through the platform

## Technologies Used

### Frontend:
- Utilizes React.js for building user interfaces.
- Enables creation of interactive and dynamic components.
- Renders UI elements for student and teacher interactions.
-Implements features like mark tracking, attendance recording, reminders, and timetable
management.

### Backend:
- Utilizes Node.js with Express.js for server-side scripting.
- Express.js provides a framework for building web applications and APIs.
- Handles server-side logic and API requests.
- Uses MongoDB with Mongoose as the backend database solution.
- Stores and manages data related to users, classes, assignments, marks, and
attendance records.
- Facilitates efficient data handling and communication between frontend and backend
components.


<br>

# Installation

Open 2 terminals in separate windows/tabs.

Terminal 1: Setting Up Backend 
```sh
cd backend
npm install
npm start
```

Create a file called .env in the backend folder.
Inside it write this :

```sh
MONGO_URL = mongodb://127.0.0.1/school
```
If you are using MongoDB Compass you can use this database link but if you are using MongoDB Atlas then instead of this link write your own database link.

Terminal 2: Setting Up Frontend
```sh
cd frontend
npm install
npm start
```
Now, navigate to `localhost:3000` in your browser. 
The Backend API will be running at `localhost:5000`.

