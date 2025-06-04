# Typing Master Website

This repository contains the front-end code for the "Typing Master" website, designed to help users improve their typing speed and accuracy.

## Features

The website includes the following pages and functionalities:

1.  **First/Landing Page (`First.html`):**
    * Introduction to the website with a modern, inviting design.
    * Navigation to other key sections (Start Test, My Results, About Us, Login, Sign Up).
    * Highlights core features and includes testimonials.
2.  **User Registering Page (`register.html`):**
    * Form for new users to create an account.
    * Includes client-side password matching validation.
    * *Note: Actual user registration and storage require a backend server.*
3.  **User Reset Password Page (`reset_password.html`):**
    * Form for users to request a password reset link via email.
    * *Note: Sending actual reset emails requires a backend server.*
4.  **User Login Page (`login.html`):**
    * Form for existing users to log in.
    * Includes simulated login authentication for demonstration purposes.
    * *Note: Real user authentication and session management require a backend server.*
5.  **List of Test Results for a User (`results.html`):**
    * Displays a list of mock typing test results.
    * *Note: Fetching and saving real user-specific results requires a backend server and database.*
6.  **User Typing Test Page (`typing_test.html`):**
    * Core typing functionality with a selection of random quotes.
    * Real-time display of WPM (Words Per Minute) and Accuracy.
    * Provides character-by-character visual feedback (correct, incorrect, and current character).
    * Includes a timer.
    * *Note: Saving test results to a user's profile requires a backend server.*
7.  **About Us Page (`about.html`):**
    * Static page providing information about the Typing Master project and its mission.

## Technologies Used

* **HTML5:** For structuring the web content.
* **CSS3:** For styling and layout, including a `global.css` for shared styles and specific CSS files for each page to ensure modularity and maintainability.
* **JavaScript:** For interactive elements, form handling, and the core typing test logic.

## How to Set Up and Run Locally

This project is a client-side web application, meaning it runs directly in your web browser without needing a complex server setup or compilation step.

### 1. Project Setup

To get started, you need to organize the provided files into a specific directory structure on your local machine.

* **Create a Main Project Folder:**
    Create a new folder on your computer, for example, `TYPING`.

* **Place the Files:**
    Copy all the HTML (`.html`), CSS (`.css`), and JavaScript (`.js`) files that I've provided into this `TYPING` folder. Ensure the file names are exactly as specified.

    - I do each page in html file include css and javascript. So, my folder structure look like this.

### Folder structure:

```
TYPING/
├── First.html              <-- Landing page with embedded CSS/JS
├── register.html           <-- Register page with embedded CSS/JS
├── reset_password.html     <-- Reset password page with embedded CSS/JS
├── login.html              <-- Login page with embedded CSS/JS
├── results.html            <-- Results page with embedded CSS/JS
├── typing_test.html        <-- Typing test page with embedded CSS/JS
├── about.html              <-- About Us page with embedded CSS
└── README.md               <-- Updated documentation
```

### 2. Running the Project

Since this is a static website, there's no "compilation" step. You simply open the HTML files in your web browser.

* **Open `First.html`:**
    Navigate to the `TYPING` folder on your computer.
    Double-click the `First.html` file. This will open the landing page of the website in your default web browser.

    Alternatively, you can right-click `First.html` and choose "Open with Live Server" and select your preferred browser (e.g., Google Chrome, Mozilla Firefox, Microsoft Edge).

* **Access Other Pages:**
    From the landing page, you can navigate to other sections of the website using the provided links (e.g., "Start Test", "Login", "Register", "About Us").

    You can also directly open any other HTML file (e.g., `typing_test.html`, `login.html`) in your browser to jump to that specific page.

## Contributing

Feel free to explore, modify, and enhance this project. If you have suggestions or improvements, you can make changes and adapt it to your needs.