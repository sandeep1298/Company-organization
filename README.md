Client (Frontend - React with Vite)

 Template: Vite React app for fast development and optimized builds.
 State Management: Uses Redux Toolkit for global state management.
 Image Upload: Cloudinary for handling image uploads efficiently.
 UI Framework: React-Bootstrap for styling and UI components.

Folder Structure

 src/features - Contains all API calls and Redux slice methods (state management logic).
 src/app - Manages centralized application-level data (e.g., Redux store configuration).
 src/utils - Contains reusable utility functions, including a loader component.
 src/config - Defines a custom Axios instance with a base URL from environment variables and enables credentials for authenticated API requests.
 src/components - Includes reusable UI components such as an employee form and an organization tree for displaying employees hierarchically.


Server (Backend - Express & MongoDB)

 Express: Backend framework for handling API routes.
 Database: MongoDB for storing employee records.

Folder Structure
 /models - Defines Mongoose models for employees.
 /routes - Contains route handlers with POST and GET methods for employee operations.


Coding Design Pattern

Frontend Design Pattern

 Feature-Based Architecture: Organizes the frontend by feature, keeping API calls, Redux slices, and components modular and easy to maintain.

 Redux Toolkit: Used for efficient and scalable state management.

 Axios with Custom Config: Ensures API calls are centralized with a consistent base URL and authentication settings.


Backend Design Pattern

 Model-View-Controller (MVC) Pattern: The backend follows the MVC pattern:

 Model (/models): Defines the structure of employee data in MongoDB.

 Controller (/routes): Handles business logic for API requests.

 View (Client-Side Components): Managed by React in the frontend.

 RESTful API Structure: Uses clear and consistent REST API endpoints.
