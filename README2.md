Project Management Tool

A robust, full-stack project management application designed to streamline team collaboration and task execution. 
This platform provides a centralized dashboard for tracking project lifecycles, managing team assignments, and monitoring real-time task status with role-based 
access control.

🚀 Live Demo
App Link:[http://localhost:3000/]  
The application is fully functional and deployed on Railway.

🛠️ Tech Stack
*   Frontend: React.js, CSS3/Tailwind CSS
*   Backend: Node.js, Express.js
*   Database: SQLite
*   Authentication: JWT (JSON Web Tokens)
*   Deployment: Railway

✨ Key Features

🔐 Secure Authentication
*   User Signup and Login functionality with encrypted password storage.
*   Persistent sessions using secure token-based authentication.

👥 Project & Team Management
*   Ability to create multiple projects and organize them efficiently.
*   Team collaboration features to manage members within specific project scopes.

✅ Task Lifecycle Tracking
*   Creation & Assignment: Define tasks with descriptions and assign them to specific team members.
*   Status Tracking: Move tasks through stages (e.g., To-Do, In Progress, Completed).
*   Overdue Alerts: Visual indicators for tasks that have passed their deadlines.

📊 Comprehensive Dashboard
*   High-level overview of all active tasks.
*   Data visualization for task distribution by status.
*   Real-time updates on project progress.

⚙️ Technical Requirements & Implementation

RESTful API Architecture
The backend is built on a structured REST API that handles data flow between the client and the database, ensuring high performance and scalability.

Role-Based Access Control (RBAC)
To ensure data integrity and security, the application implements distinct roles:
*   Admin/Manager: Can create projects, assign tasks, and manage users.
*   Member: Can view assigned tasks and update their specific status.

Data Integrity & Relationships
*   Proper Validations: Server-side and client-side validation to ensure clean data entry.
*   Database Relationships: Optimized schema design to handle complex relationships between users, projects, and tasks.

🌐 Deployment
This application is deployed using **Railway**, ensuring a seamless CI/CD pipeline. The live version includes a fully connected database and functional 
backend services.




How to use this application, if there is an error:
1. First download the zip file.
2. Open it on you system and extract all the file.
3. Install node for feature extraction. Then check its version from cmd.
4. Install the project dependencies using npm install in that file by opening the cmd.
5. From the env.example file generate the api key for the application from google AI studio for secure connection.
6. Then open vs code and from the new terminal run the application.
7. If there is an error in opening the site. First run it in the terminal and then manually type localhost and the port name.
8. You can view the app on the server.
