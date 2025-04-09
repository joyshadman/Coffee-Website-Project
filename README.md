# Coffetto

A simple coffee website built using HTML and CSS.

## Overview

Coffetto is a basic static website designed to showcase a coffee shop. It includes sections for:

*   Home: A welcome section with a brief introduction.
*   Menu: A listing of available coffee drinks and potentially food items.
*   About Us: Information about the coffee shop's history and values.
*   Contact: Contact information and a form for inquiries.

This project is intended as a demonstration of HTML and CSS skills, focusing on creating a visually appealing and functional website layout without the use of JavaScript or backend technologies.

## Features

*   **Clean and Responsive Design:** The website layout adapts to different screen sizes for optimal viewing on desktops, tablets, and mobile devices (using media queries).
*   **Simple Navigation:**  A straightforward navigation bar allows users to easily browse different sections of the website.
*   **Semantic HTML:** HTML5 semantic elements are used to structure the content logically, improving accessibility and SEO.
*   **CSS Styling:**  CSS is used to control the visual appearance of the website, including colors, fonts, and layout.

## Technologies Used

*   HTML5
*   CSS3

## Project Structure

The project directory typically contains the following files:

*   `index.html`: The main HTML file containing the website's structure and content.
*   `style.css`: The CSS file containing the website's styling rules.
*   `images/`: A directory containing images used in the website (e.g., coffee beans, logos).

## Code Examples

**HTML (index.html):**

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Coffetto</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <nav>
            <h1>Coffetto</h1>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#menu">Menu</a></li>
                <li><a href="#about">About Us</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="home">
        <h2>Welcome to Coffetto!</h2>
        <p>Your local coffee shop serving the best brews.</p>
    </section>

    <section id="menu">
        <h2>Our Menu</h2>
        <ul>
            <li>Espresso</li>
            <li>Latte</li>
            <li>Cappuccino</li>
        </ul>
    </section>

    <section id="about">
        <h2>About Us</h2>
        <p>We are passionate about coffee.</p>
    </section>

    <section id="contact">
        <h2>Contact Us</h2>
        <p>Email: info@coffetto.com</p>
    </section>

    <footer>
        <p>&copy; 2023 Coffetto</p>
    </footer>
</body>
</html>
```

**CSS (style.css):**

```css
body {
    font-family: sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
    color: #333;
}

header {
    background-color: #333;
    color: #fff;
    padding: 10px 0;
}

nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 0 20px;
}

nav ul {
    list-style: none;
    display: flex;
}

nav ul li {
    margin-left: 20px;
}

nav a {
    color: #fff;
    text-decoration: none;
}

section {
    padding: 20px;
    margin: 20px;
    background-color: #fff;
    border-radius: 5px;
}

footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 10px 0;
}

/* Responsive Design */
@media (max-width: 600px) {
    nav {
        flex-direction: column;
        align-items: flex-start;
    }

    nav ul {
        flex-direction: column;
        padding: 0;
    }

    nav ul li {
        margin: 5px 0;
    }
}
```

## Contributing

Contributions are welcome! If you find any bugs or have suggestions for improvement, please submit an issue or pull request.
