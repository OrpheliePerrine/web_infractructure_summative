Tasker Checker – Task Management Web Application

Project Overview
Tasker Checker is a simple and interactive web-based to-do list designed to help users stay organised and manage their daily tasks. The application allows users to add, complete, and delete tasks directly in their browser.
This project demonstrates how a static web application can be developed and deployed using basic web infrastructure concepts without backend development.

Problem Statement & Idea
Managing daily tasks can be challenging, especially for students and busy individuals. The goal of Tasker Checker is to provide a lightweight and easy-to-use task manager that helps users track their responsibilities efficiently.
This project also serves as a demonstration of how a web application can be delivered to users through standard web hosting methods.

Application Features
Add new tasks
Display a list of tasks
Mark tasks as completed
Delete tasks
Store tasks using browser LocalStorage
Bright and playful pastel user interface

Technology Stack
HTML – Provides webpage structure
CSS – Handles styling and visual design
JavaScript – Controls application logic and interaction
LocalStorage – Stores tasks locally in the browser
GitHub Pages – Used to host and deploy the application


How to Run the App Locally
To run the application on your local computer:

Method 1 – Open Directly
Download or clone the repository.
Open the project folder.
Double-click index.html.
The application will open in your browser.

Method 2 – Using Live Server (Recommended)
Open the project folder in Visual Studio Code.
Install the Live Server extension.
Right-click index.html.
Click Open with Live Server.


How the App is Deployed
The application is deployed using GitHub Pages, which is a static web hosting service provided by GitHub.

Deployment Steps:
Created a public GitHub repository.
Uploaded all application files (HTML, CSS, JavaScript).
Enabled GitHub Pages in repository settings.
Selected the main branch as the deployment source.
GitHub automatically generated a public website link.

Hosting Platform Used and Why
Hosting Platform: GitHub Pages
GitHub Pages was chosen because:
It supports static website hosting.
It is free and easy to configure.
It integrates directly with GitHub repositories.
It automatically updates the live website when files are updated.
GitHub Pages acts as a web server that delivers the website files to users when they access the application URL.


Explanation of Basic Web Infrastructure
This project demonstrates how web infrastructure works when a user accesses a website.

1. Browser
When a user enters the website URL into a browser (such as Chrome or Firefox), the browser sends a request to access the website.

2. DNS (Domain Name System)
DNS converts the website name into an IP address that identifies the web server hosting the website.

3. Web Server
The web server (GitHub Pages) receives the request and retrieves the website files.

4. Static File Delivery
The server sends the following files to the browser:
HTML file – Defines the webpage structure
CSS file – Styles the webpage layout and appearance
JavaScript file – Adds functionality and interactivity

5. Browser Rendering
The browser loads the HTML structure, applies CSS styling, and executes JavaScript to allow users to interact with the application.


Infrastructure Flow Diagram
User → Browser → Internet → Web Server (GitHub Pages) → HTML / CSS / JavaScript Files

Design Choices
The application was designed as a static website to simplify hosting and deployment.
LocalStorage was used instead of a database to store tasks.
A pastel colour theme was selected to create a friendly and engaging user experience.
The application focuses on simplicity and accessibility rather than advanced features.
The app is intended for single-user browser usage.


Live Application
.....
