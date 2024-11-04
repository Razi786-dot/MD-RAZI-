# MD-RAZI-
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MD RAZI HUSSAIN - Freelance Developer</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>MD RAZI HUSSAIN</h1>
        <p>Freelance Developer - Bringing Ideas to Life</p>
    </header>
    <section id="about">
        <h2>About Me</h2>
        <p>Experienced developer specializing in [specific skills]. Passionate about turning ideas into reality through code.</p>
    </section>
    <section id="portfolio">
        <h2>Portfolio</h2>
        <p>Check out some of my recent projects.</p>
        <!-- Add portfolio items here -->
    </section>
    <section id="services">
        <h2>Services</h2>
        <p>I offer high-quality services in web development, mobile app creation, and consulting.</p>
    </section>
    <section id="contact">
        <h2>Contact</h2>
        <form>
            <label for="Razi">Name</label>
            <input type="text" id="mdrazihussain786@gmail.com" name="Razi">
            <label for="mdrazihussain786@gmail.com">Email</label>
            <input type="mdrazihussain786@gmail.com" id="mdrazihussain786@gmail.com" name="mdrazihussain786@gmail.com">
            <button type="submit">Send Message</button>
        </form>
    </section>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f9;
    color: #333;
    text-align: center;
}

header {
    background-color: #0073e6;
    color: white;
    padding: 2em;
}

section {
    margin: 2em 0;
}

button {
    background-color: #0073e6;
    color: white;
    padding: 0.5em 1em;
    border: none;
    cursor: pointer;
}
// Smooth Scrolling
document.querySelectorAll('a[href^="#"]').forEach(anchor => {
    anchor.addEventListener('click', function (e) {
        e.preventDefault();
        document.querySelector(this.getAttribute('href')).scrollIntoView({
            behavior: 'smooth'
        });
    });
});

// Simple Form Validation
const form = document.querySelector('form');
form.addEventListener('submit', (e) => {
    const name = document.getElementById('name').value;
    const email = document.getElementById('email').value;
    if (!name || !email) {
        alert("Please fill in all fields.");
        e.preventDefault();
    } else {
        alert("Thank you! Your message has been sent.");
    }
});
