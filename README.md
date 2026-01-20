# Project Management Tool

A **Web-Based Project Management Tool** developed as an academic project to streamline project planning, task assignment, progress tracking, and team collaboration.  
The system supports multiple user roles, including Project Owner, Project Manager, and Team Members, providing a centralized platform for efficient project execution.

> **Academic Project | 5th Semester**  
> **Duration:** September 2025 – January 2026  
> **Team Size:** 5 Members  
> **Role:** Frontend Developer
> **Tech Stack:** Node.js · Express · MongoDB (MERN Stack)

## Project Overview

Manual project management is prone to miscommunication, missed deadlines, and unclear task ownership.  
This Project Management Tool addresses these issues by providing:

- Role-based access for Project Owner, Manager, and Team Members  
- Centralized project and task management  
- Real-time task tracking with status updates (To-Do, In-Progress, Completed)  
- Notifications for task assignments and approaching deadlines  
- Dashboards for project progress visualization and performance monitoring  

The tool follows **Agile Scrum methodology**, supporting iterative development and continuous improvement.


## Key Features

- **User Authentication:** Secure login for all user roles  
- **Project Management:** Create, edit, and delete projects  
- **Task Management:** Assign tasks, set deadlines, and track progress  
- **Real-time Status Updates:** Team members can update task statuses  
- **Notifications:** Alerts for task assignments, deadlines, and project updates  
- **Dashboards & Analytics:** Visualize project progress and team contributions  
- **Role-Based Access:** Different permissions for Project Owner, Manager, and Members  


## Tech Stack

- **Frontend:** React.js / HTML, CSS, JavaScript  
- **Backend:** Node.js, Express.js  
- **Database:** MongoDB (via MongoDB Atlas)  
- **Authentication & Sessions:** JWT / express-session  
- **Development Methodology:** Agile Scrum  


## How to Run (Development)

**1️. Clone the Repository**
```bash
git clone https://github.com/02FE23BCS161/Project-management-system.git
cd Project-management-system
```
**2. Install Dependencies**
```bash
npm install
```
**3. Configure Environment Variables**

Create a `.env` file in the root directory
```bash
MONGO_URI=mongodb://localhost:27017/your-db
PORT=3000
SESSION_SECRET=your-secret-key
```
**4. Start the Server**
```bash
node server.js
```
**5. Access the Application**

Open your browser and go to:
`http://localhost:3000`


*Enjoy managing your projects efficiently!*
