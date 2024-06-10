## Project Description:
This Angular application is designed for the registration and tracking of projects. It features components for project registration, viewing project details, and listing registered projects. The application ensures a user-friendly interface and responsive design, adhering to best practices in Angular development.

## Features:
1. Header Component:

-Displays the title of the portal.
-Responsive design adapts to different screen sizes.

2. Project Registration:

-Form for registering new projects with fields for project name, priority, manager, initiator department, contact person, start and end dates, description, file upload, team name, and team members.
-Validation for required fields and correct data formats.
-Ability to add and remove team members dynamically.
-Displays a success message upon successful registration.

3. Project List:

-Displays a list of registered projects with search functionality.
-Filters projects based on various criteria such as name, unique number, status, dates, manager, and team name.
-Sorts projects by different fields.
-Highlights overdue projects.
-Allows setting and updating the progress of ongoing projects.
-Provides links to project details and edit options.

4. Project Detail View:

-Displays detailed information about a specific project.
-Read-only fields for project information and team members.
-Status update functionality for ongoing projects.
-Back button to return to the project list.

## Technologies Used:
-Angular 14+: For building the single-page application.
-TypeScript: For type safety and advanced features.
-Angular Router: For navigation and routing.
-Reactive Forms: For handling forms and validation.
-Angular HttpClient: For HTTP communication.
-RxJS: For reactive programming.
-Bootstrap: For styling and responsive design.

## Project Structure:
Components:
-HeaderComponent: Displays the portal's header.
-ProjectRegistrationComponent: Handles project registration.
-ProjectListComponent: Displays the list of registered projects.
-ProjectDetailComponent: Shows detailed information of a project.

Services:
-ProjectService: Manages the list of projects and provides methods for adding and updating projects.

Models:
-Project: Defines the structure of a project.
-TeamMember: Defines the structure of a team member.

## Installation

### Clone the repository
```bash
git clone https://github.com/MariamDZE1/Projects-Portal.git

# Install dependencies
npm install

# Start the application
ng serve
