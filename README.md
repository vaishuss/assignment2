# assignment2
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>My Portfolio</h1>
        <nav>
            <ul>
                <li><a href="#about">About Me</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>
    <section id="about">
        <h2>About Me</h2>
        <img src="vaishnavi.jpg" alt="My Photo">
        <p>Hello! I am Vaishnavi singh  a web developer with a passion for creating beautiful and functional websites.My aim is to become india's leading developer</p>
    </section>
    <section id="projects">
        <h2>Projects</h2>
        <div class="project">
            <h3>Project One</h3>
            <img src="vaishnavi1.png" alt="Project One" width="300" height="400">
            <p>A basic signup page with details like email,password,username dob etc.</p>
        </div>
        
    </section>
    <section id="contact">
        <h2>Contact</h2>
        <form action="submit_form.php" method="post">
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            <label for="message">Message:</label>
            <textarea id="message" name="message" required></textarea>
            <button type="submit">Send</button>
        </form>
    </section>
    <footer>
        <p>&copy; 2024 [Vaishnavi Singh]. All rights reserved.</p>
    </footer>
</body>
</html>
<style>
    body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    margin: 0;
    padding: 0;
    background-image: url(https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSRtzmz-R4qJz9oWjtaF_S1cS_EgEPE6SKSYA&s);
    color: #333;
}

header {
    background: #000000;
    color: #fff;
    padding: 1rem 0;
    text-align: center;
}

nav ul {
    list-style: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 10px;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
}

section {
    padding: 20px;
    margin: 20px 0;
}

#about img {
    max-width: 150px;
    border-radius: 50%;
}

.project {
    margin-bottom: 20px;
}

.project img {
    max-width: 100%;
    height: auto;
}

form {
    display: flex;
    flex-direction: column;
}

form label {
    margin-top: 10px;
}

form input,
form textarea {
    padding: 10px;
    margin-top: 5px;
}

form button {
    padding: 10px;
    background: #333;
    color: #fff;
    border: none;
    cursor: pointer;
    margin-top: 10px;
}

footer {
    background: #333;
    color: #fff;
    text-align: center;
    padding: 1rem 0;
    position: fixed;
    bottom: 0;
    width: 100%;
}
</style>
