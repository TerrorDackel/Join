# Join – Task Management App

Team-based Kanban board for managing tasks, developed as a group project during the Developer Akademie frontend program. Users can register, log in and organize tasks across multiple status columns.

- Live app: https://www.join.jennifer-thomas.de/login
- Repository: https://github.com/TerrorDackel/DA_Join

## Features
- Task board with multiple status columns (for example To do, In progress, Await feedback, Done)
- Create, edit and delete tasks (title, description, category, due date, priority, assigned contacts)
- Drag and drop tasks between columns using Angular CDK
- Sign up and login with form validation and error messages
- Required acceptance of privacy policy during sign up
- Task detail view in a dialog with more information and actions
- Responsive layout for desktop, tablet and mobile
- Modern UI with icons, colors and subtle animations

## Tech stack
- **Framework:** Angular 17 (generated with Angular CLI)
- **Languages:** TypeScript, HTML5, SCSS
- **UI / UX:** Angular Material components, custom Sass styling
- **Drag & Drop:** Angular CDK DragDrop
- **Backend:** Firebase (Authentication and Firestore for user and task data)
- **Tooling:** Angular CLI, npm, Git & GitHub

## My role in the team
This is a fork of our team project (original repo: PaFunzFr/DA_Join). 
We worked as a group of four.
My focus areas in this fork:
- Sign up dialog and authentication UX (layout, validation messages, red error borders, handling of invalid inputs)
- Ensuring that the privacy policy checkbox is required and clearly communicated to users
- Responsive styling and spacing for login and sign up screens across different screen sizes
- Visual polish for the auth area (images, texts, alt attributes, spacing, hover states)
- JSDoc comments and code clean-up on legal pages (privacy policy and legal notice components)
- Iterative refinements to make the auth flow more robust, readable and maintainable

## Project structure (high level)
- src/app – main application, routing and layout
- src/app/components – UI components (login dialog, sign up dialog, board, task dialog, summary, contacts, etc.)
- src/app/services – services for tasks, contacts and Firebase integration
- src/assets – images, icons and static assets
- SCSS files – global styles and component-specific styles

## Getting started

### Prerequisites
- Node.js (LTS)
- npm (comes with Node.js)
- Angular CLI installed globally (optional but recommended)
- npm install -g @angular/cli

## Install and run locally
- git clone https://github.com/TerrorDackel/DA_Join.git

- cd DA_Join
- npm install
- npm start (or: ng serve)

## Open http://localhost:4200/
 in your browser.
The app will reload automatically when you change source files.

## Build
- ng build
- The build artifacts will be stored in the dist/ directory.

## Tests
- ng test (unit tests, if configured)
- ng e2e (end-to-end tests, after adding an e2e runner)

## Kurzbeschreibung (Deutsch)
JOIN ist ein gemeinsames Gruppenprojekt aus der Developer Akademie: eine Aufgaben- und Kanban-App auf Basis von Angular 17 mit Firebase-Anbindung. 
In meinem Fork habe ich vor allem am Sign-up-Dialog, der Validierung, der Darstellung der rechtlichen Seiten (Datenschutz/Impressum) und der responsiven Gestaltung der Login- und Sign-up-Ansichten gearbeitet.