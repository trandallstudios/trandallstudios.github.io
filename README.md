<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>Quantum Echo Studios</title>
</head>
<body>

    <!-- Header -->
    <header>
        <h1>Quantum Echo Studios</h1>
        <p>Designing Spaces, Building Dreams</p>
    </header>

    <!-- Navigation Bar -->
    <nav>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#projects">Projects</a></li>
            <li><a href="#team">Our Team</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>

    <!-- Main Section -->
    <section id="home">
        <h2>Welcome to Our Architecture Studio</h2>
        <p>Explore our portfolio of innovative architectural designs.</p>
    </section>

    <section id="projects">
        <h2>Featured Projects</h2>
        <!-- Add your project images and descriptions here -->
    </section>

    <section id="team">
        <h2>Meet Our Team</h2>
        <!-- Add information about your team members here -->
    </section>

    <!-- Contact Form -->
    <section id="contact">
        <h2>Contact Us</h2>
        <form action="#" method="post">
            <!-- Add form fields for name, email, message, etc. -->
            <button type="submit">Send Message</button>
        </form>
    </section>

    <!-- Footer -->
    <footer>
        <p>&copy; 2023 Architecture Studio. All rights reserved.</p>
    </footer>

</body>
</html>
body {
    font-family: 'Arial', sans-serif;
    margin: 0;
    padding: 0;
}

header {
    background-image: url('<img style="-webkit-user-select:none; display:block; margin:auto; padding:env(safe-area-inset-top) env(safe-area-inset-right) env(safe-area-inset-bottom) env(safe-area-inset-left);" src="file:///Users/tonyrandall/Desktop/Screen%20Shot%202023-12-15%20at%203.23.26%20PM.png">'); /* Add a background image */
    background-size: cover;
    color: white;
    text-align: center;
    padding: 100px 0;
}

nav {
    background-color: #333;
    color: white;
    padding: 10px;
    text-align: center;
}

nav ul {
    list-style: none;
}

nav ul li {
    display: inline;
    margin-right: 20px;
}

section {
    margin: 20px;
}

button {
    background-color: #333;
    color: white;
    padding: 10px;
    border: none;
    cursor: pointer;
}

button:hover {
    background-color: #555;
}

footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 10px 0;
}
