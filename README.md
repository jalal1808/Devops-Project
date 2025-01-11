# DevOps

## Objective
This assignment aimed at designing a web-based UI that allows users to fill out a form, automatically creates a unique identifier for each user, and creates individual containers displaying the information filled in by users. It ensures data integrity with strong form validation and has a mobile-responsive design.

## Modules

### UI Design
- Developed a friendly, modern interface using React Web.
- Ensured seamless navigation and accessibility across different devices.

### Backend Development
- Developed using Node.js and React.js.
- Implemented a RESTful API for handling data operations.
- Managed containerized deployment with Docker, ensuring scalability and consistency.

### Validation Logic
- Comprehensive form validation:
  - **Name**: Required field, minimum 3 characters.
  - **Email**: Ensured a valid email format.
  - **Age**: Must be numeric and ≥ 18.
  - **Gender**: Dropdown with required selection.
  - **Address**: Multiline text with a minimum of 10 characters.
- Provided real-time feedback for all user inputs to enhance user experience.

### Dynamic Containers
- Containers are created individually for every user with their unique ID and submitted data.
- Edit functionality allows users to modify their information.
- Delete functionality is added to dynamically remove user information.

## System Overview

### Frontend Framework
- React Web

### Backend Framework
- Node.js

### Form Fields
- Full Name
- Email Address
- Age
- Gender (Dropdown: Male, Female, Other)
- Address (Multiline Text Area)

## Features
- Dynamic creation of user containers.
- Editable and deletable containers.
- Responsive design ensuring accessibility across various screen sizes.

## Deployment Details

### Frontend
- React Web application bundled and optimized for production.

### Backend
- Hosted as a Docker container, providing isolated and efficient service management.
- APIs are designed to handle CRUD operations for user data.

### Integration
- Seamless integration of frontend and backend using RESTful APIs.
- Data is dynamically stored and retrieved to update the UI in real-time.

## Contribution
- **Muhammad Jalal** – Docker Integration
- **Husnain Ashraf** – Database Creation and Validation
- **Fariz Farouqui** – Frontend Form
- **Azib Siddiqui/Muhammad Daniyal** – UI Design and Report
- **Ameenuddin Zain u din** – Backend

