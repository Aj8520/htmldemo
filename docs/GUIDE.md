# Web Page Design Guide

Welcome to the Web Page Design Guide! This document is intended for users who are new to HTML and CSS. It will provide you with step-by-step instructions on how to create a basic web page that utilizes the navigation functions defined in the `jewelloNavigation.js` file.

## Table of Contents
1. Introduction to HTML
2. Basic HTML Structure
3. Introduction to CSS
4. Adding CSS to Your Web Page
5. Integrating JavaScript Navigation
6. Example Web Page
7. Conclusion

## 1. Introduction to HTML
HTML (HyperText Markup Language) is the standard language for creating web pages. It uses a series of elements to structure content on the page.

## 2. Basic HTML Structure
A basic HTML document consists of the following structure:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Web Page Title</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <h1>Welcome to My Web Page</h1>
    <div id="user-name-display"></div>
    <nav>
        <ul>
            <li><a href="#" onclick="navigateToScheme()">Scheme</a></li>
            <li><a href="#" onclick="navigateToBankDetails()">Bank Details</a></li>
            <li><a href="#" onclick="navigateToKyc()">KYC</a></li>
            <li><a href="#" onclick="navigateToRate()">Rate</a></li>
            <li><a href="#" onclick="navigateToFeedback()">Feedback</a></li>
            <li><a href="#" onclick="navigateToSetting()">Settings</a></li>
        </ul>
    </nav>
    <script src="jewelloNavigation.js"></script>
</body>
</html>
```

## 3. Introduction to CSS
CSS (Cascading Style Sheets) is used to style HTML elements. It allows you to change colors, fonts, layouts, and more.

## 4. Adding CSS to Your Web Page
You can add CSS to your web page by creating a separate CSS file (e.g., `styles.css`) and linking it in the `<head>` section of your HTML document. Here’s a simple example of CSS:

```css
body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f4;
    margin: 0;
    padding: 20px;
}

nav {
    background-color: #333;
    color: white;
    padding: 10px;
}

nav ul {
    list-style-type: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin-right: 15px;
}

nav ul li a {
    color: white;
    text-decoration: none;
}
```

## 5. Integrating JavaScript Navigation
To use the navigation functions from `jewelloNavigation.js`, include the script at the end of your HTML document, just before the closing `</body>` tag. Each navigation link should call the corresponding JavaScript function using the `onclick` attribute.

## 6. Example Web Page
Here’s a complete example of a simple web page that incorporates HTML, CSS, and JavaScript navigation:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Web Page</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <h1>Welcome to My Web Page</h1>
    <div id="user-name-display"></div>
    <nav>
        <ul>
            <li><a href="#" onclick="navigateToScheme()">Scheme</a></li>
            <li><a href="#" onclick="navigateToBankDetails()">Bank Details</a></li>
            <li><a href="#" onclick="navigateToKyc()">KYC</a></li>
            <li><a href="#" onclick="navigateToRate()">Rate</a></li>
            <li><a href="#" onclick="navigateToFeedback()">Feedback</a></li>
            <li><a href="#" onclick="navigateToSetting()">Settings</a></li>
        </ul>
    </nav>
    <script src="jewelloNavigation.js"></script>
</body>
</html>
```

## 7. Conclusion
Congratulations! You have now learned the basics of creating a web page using HTML, CSS, and JavaScript. You can expand upon this foundation by exploring more advanced topics and features. Happy coding!