# Web Page Documentation

## Overview

This project provides a simple framework for creating a web application with navigation functionality. The primary feature of this project is the `jewelloNavigation.js` file, which contains JavaScript functions that facilitate navigation within the application. Each function sends a message to a JavaScript channel named `Toaster`, which triggers navigation to different sections of the application.

## Purpose

The purpose of this project is to help users, especially those unfamiliar with HTML and CSS, to design a basic web page that utilizes the navigation functions defined in `jewelloNavigation.js`. This documentation will guide you through the process of creating a web page, styling it with CSS, and integrating the JavaScript navigation functionality.

## Getting Started

To get started with this project, follow these steps:

1. **Clone the Repository**: Download or clone the repository to your local machine.
2. **Open the Project**: Use a code editor to open the project folder.
3. **Create an HTML File**: Create a new HTML file (e.g., `index.html`) in the project directory.
4. **Link the JavaScript File**: Include the `jewelloNavigation.js` file in your HTML file to enable navigation functionality.

## Creating a New Project on GitLab

To create a new project on GitLab, follow these steps:

1. **Sign In**: Go to the GitLab website and sign in to your account.
2. **Create a New Project**: Click on the "New Project" button on your dashboard.
3. **Fill in Project Details**: Enter the project name, description, and visibility level (public or private).
4. **Initialize the Repository**: You can choose to initialize the repository with a README file.
5. **Push Local Repository**: After creating the project, follow the instructions provided by GitLab to push your local repository to GitLab using Git commands.

## Displaying index.html through GitHub Pages

To host the `index.html` file using GitHub Pages, follow these steps:

1. **Create a GitHub Repository**: Go to GitHub and create a new repository for your project.
2. **Push Your Code**: Use Git commands to push your local project files to the newly created GitHub repository.
3. **Enable GitHub Pages**: Go to the repository settings, scroll down to the "GitHub Pages" section, and select the branch you want to use (usually `main` or `master`).
4. **Access Your Page**: After enabling GitHub Pages, your `index.html` file will be accessible via a URL in the format `https://<username>.github.io/<repository-name>/`.

## Usage

To use the navigation functions, you will need to call them from your HTML elements (e.g., buttons or links). Each function corresponds to a specific navigation action. For example, to navigate to the scheme section, you would call `navigateToScheme()`.

## Documentation

For detailed instructions on how to create a basic web page using HTML and CSS, please refer to the guide located in the `docs/GUIDE.md` file.

## Prerequisites

- Basic understanding of HTML and CSS (refer to `docs/GUIDE.md` for a beginner-friendly guide).
- A web browser to test your web application.

## Conclusion

This project serves as a foundation for building web applications with navigation capabilities. By following the instructions in the documentation, you will be able to create a functional web page that utilizes the provided JavaScript navigation functions.