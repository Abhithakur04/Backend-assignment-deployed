# 🗓️ Task Log – Task Manager Backend

## 12:27 am – 12:57 am  
- Initialized the project folder and opened it in VS Code.  
- Ran `npm init` to set up `package.json`, and installed **Express** as a dependency.  
- Created `app.js` and set up a basic Express server with a test `GET /` route to verify everything was running.  
- Committed initial setup to GitHub and pushed to the remote repository.  
- Took some screenshots for documentation and began drafting the README file.

## 12:57 am – 1:27 am  
- Added user authentication functionality:
  - Created `POST /register` and `POST /login` routes.  
  - For simplicity, stored user data in an in-memory JavaScript object.  
- Implemented token-based session handling:
  - Generated tokens using the `uuid` package.  
  - Stored active sessions in a separate object to associate tokens with users.  
- Committed progress to GitHub.  
- Captured screenshots of registration and login requests via Postman.  
- Continued building out the README.

## 1:27 am – 1:57 am  
- Developed authentication middleware:
  - Middleware checks for a valid token in the `Authorization` header.  
  - Integrated middleware into protected task-related routes.  
- Added task functionality:
  - Implemented `POST /tasks` to allow users to create new tasks.  
  - Each task includes a unique `id` and `text` content, tied to the authenticated user.  
  - Implemented `GET /tasks` to retrieve all tasks belonging to the authenticated user.  
- Pushed the changes to GitHub and updated documentation accordingly.  
- Took additional screenshots and made notes for the README.

## 1:57 am – 2:27 am  
- Added ability to delete tasks:
  - Created `DELETE /tasks/:taskId` route to remove a task by its ID.  
  - Ensured tasks are only deleted if they belong to the authenticated user.  
  - Added error handling for cases where the task ID doesn’t exist or isn’t owned by the user.  
- Thoroughly tested all routes using Postman (register, login, create task, list tasks, delete task).  
- Committed and pushed all changes to GitHub.  
- Captured final round of screenshots and updated the README with examples and endpoint usage.

## 2:27 am – 2:57 am  
- Completed the README file:
  - Added project overview, setup instructions, and detailed documentation for each API endpoint.  
  - Included usage examples and screenshots of the API in action using Postman.  
- Performed a final full test of all routes to ensure stability and correct behavior.  
- Wrote this task log to document the development process.  
- Final commit and push to GitHub — **Project complete ✅**
