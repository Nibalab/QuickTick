# QuickTick

<br><br>

<!-- project philosophy -->
<img src="./readme/title2.svg" alt="Project Philosophy" />

> QuickTick is a task management web app that helps users stay organized by offering task creation, prioritization, and real-time updates. Whether you're a student, professional, or part of a team, QuickTick allows you to manage your to-do list efficiently. Prioritize, complete, and track tasks with ease.

### User Stories

## User

- As a user, I want to create, update, and delete tasks so that I can manage my to-do list.
- As a user, I want to mark tasks as complete so that I can track my progress.
- As a user, I want to filter tasks by priority (low, medium, high) so that I can focus on what matters most.
- As a user, I want to securely log in and register to save my tasks and settings across sessions.

<br>

<!-- Tech stack -->

### QuickTick is built using the following technologies:

- The **backend** is powered by [Node.js](https://nodejs.org/en/) with [Express.js](https://expressjs.com/), handling authentication, database management, and server-side logic.
- The **frontend** is built using [React](https://reactjs.org/) with [Next.js](https://nextjs.org/), a React framework for server-side rendering and static website generation.
- **MongoDB** is used for the database, offering flexible, schema-less storage for tasks and user data.
- **JWT (JSON Web Token)** is used for authentication, providing secure login and registration processes for users.
- **Postman** is used for API testing, ensuring the backend endpoints are working correctly.
- **Axios** is used for making HTTP requests between the frontend and backend, ensuring real-time interaction with the app.

<br>

<!-- Task Management Features -->

### Key Features:

- **Task Creation & Editing**: Users can create tasks, edit them, and manage task details such as title, description, due date, and priority.
- **Task Priority**: Tasks can be assigned priorities: low, medium, or high. Users can filter tasks based on priority to focus on urgent tasks.
- **Task Completion**: Users can mark tasks as completed to visually track their progress and declutter their workspace.
- **User Authentication**: Secure login and registration using JWT, ensuring tasks are associated with specific users.
- **API Testing**: Postman is used to manually test and validate all backend endpoints to ensure that creating, updating, deleting, and fetching tasks works as expected.

<br>

<!-- How to run -->
### How to Run QuickTick Locally:

#### Prerequisites:
Ensure you have the following installed before setting up QuickTick:

* **Node.js**  
  Download and install Node.js from [nodejs.org](https://nodejs.org/). Node.js comes with npm (the Node Package Manager).

* **MongoDB** (for the database)  
  - Install [MongoDB](https://www.mongodb.com/try/download/community) locally or use [MongoDB Atlas](https://www.mongodb.com/cloud/atlas) for a cloud solution.

#### Installation:

1. **Clone the repo:**
```sh
   git clone https://github.com/your-username/quicktick.git
   cd quicktick
   ```
2. **Install the frontend dependencied**
```sh
   cd frontend-quicktick
   npm install
   ```
3. **Install the backend dependencied**
```sh
    cd ../backend-quicktick
    npm install
   ``` 
4. **Set up environment variables:**
  ## Add these variables in your .env file 
* MONGO_URI=your_mongo_uri
* JWT_SECRET=secret or anything random
* CLIENT_URL=http://localhost:3000 or any localhost port that you are using
* PORT=8000

5. **Run the backend** 
 ```sh
   npm run dev
   ```  
6. **Run the frontend**
```sh
    cd frontend-quicktick
    npm run dev
    ``` 
4. **Access the app: **
  * Open http://localhost:3000 in your browser to access QuickTick and test all features.
   
   
         

