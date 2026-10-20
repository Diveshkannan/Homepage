# Personal Workspace

## Overview
Personal Workspace is a front-end web development project designed to help users explore career paths, maintain personal details, and connect their workspace with useful development profiles. The project focuses on providing a simple interface for choosing a career direction and displaying related information.

## Features
- **Home Page:** Introduces the Personal Workspace platform.
- **About Us:** Explains the project's purpose, vision, and planned improvements.
- **Login Page:** Collects user details and links to development profiles.
- **Choose Path:** Allows users to select a career path related to computer science or engineering.
- **Profile Page:** Displays saved user information and provides workspace-related options.
- **Password Page:** Provides a basic password verification interface.
- **Error Page:** Displays a message when the allowed number of attempts is exceeded.
- **Navigation:** Enables users to move between the different pages.
- **Data Storage:** Uses browser `localStorage` and `sessionStorage` to store and manage information.
- **URL Display:** Supports displaying user-provided profile and development-related URLs.

## Technologies Used
- **HTML5** — Structures the web pages.
- **CSS3** — Styles the interface, layouts, buttons, gradients, and interactive elements.
- **JavaScript** — Handles navigation, input validation, browser storage, and page interactions.
- **Bootstrap 5** — Provides access to Bootstrap's front-end styling and JavaScript components.

## Project Structure
```text
Personal-Workspace/
├── index.html
├── about-us.html
├── choose-path.html
├── login.html
├── profile.html
├── password.html
├── error.html
├── styles.css
└── README.md
```

## Getting Started

### Prerequisites
- A modern web browser such as Google Chrome, Microsoft Edge, or Firefox.
- An internet connection to load Bootstrap resources from the CDN.

### Running the Project
1. Download or clone the project repository.
2. Open the project directory.
3. Open `index.html` in a web browser.
4. Navigate through the available pages using the navigation buttons.

No backend server or database is currently required for the basic front-end functionality.

## Data Storage
The project uses browser storage:
- `localStorage` stores selected career paths and user-provided details.
- `sessionStorage` stores temporary session-related information.

The data is stored in the browser and is not automatically synchronized across devices or browsers.


## The Real Reason Behind This Project

I have seen people trying to keep their dream work away from other eyes. I have also seen curious minds searching for direction but standing without a clear path in their hands.

That inspired me to build Personal Workspace — an intelligent platform designed to help people discover their direction, explore possible career paths, and keep their personal workspace protected.

**My vision is simple: help people find their path, protect their dreams, and give their curiosity a direction.** This is the real reason behind Personal Workspace.

**Note:** This is a front-end learning project. Browser storage is not a secure place to store real passwords or sensitive personal information. The current client-side password verification is intended for demonstration purposes, not production authentication.

## Future Improvements
- Integrate a Python Flask backend.
- Connect a SQL database for persistent data storage.
- Implement secure authentication and password handling.
- Add dynamic career-path information.
- Introduce AI-powered career guidance and an interactive chatbot.
- Improve responsiveness and accessibility across devices.

## Author
**Diveshkannan T**

## License
This project is intended for educational and personal development purposes.
