<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Case.Ro Technologies, Inc.</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="container">
            <h1>Case.Ro Technologies, Inc.</h1>
            <nav>
                <ul>
                    <li><a href="#how-it-works">How It Works</a></li>
                    <li><a href="#become-a-host">Become a Host</a></li>
                    <li><a href="#about-us">About Us</a></li>
                    <li><a href="#contact-us">Contact Us</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section class="main-banner">
        <div class="container">
            <h2>Connecting You to Authentic Homemade Meals</h2>
            <a href="#" class="btn">Order Now</a>
            <a href="#" class="btn">Become a Host</a>
        </div>
    </section>

    <section id="how-it-works">
        <div class="container">
            <h2>How It Works</h2>
            <p>Discover how you can enjoy homemade meals or become a host and share your culinary talents.</p>
            <ol>
                <li><strong>Browse Menus:</strong> Explore a variety of homemade meals prepared by local hosts.</li>
                <li><strong>Place Your Order:</strong> Choose your favorite dishes and place your order.</li>
                <li><strong>Enjoy Your Meal:</strong> Receive your freshly made meal at your doorstep.</li>
            </ol>
        </div>
    </section>

    <section id="become-a-host">
        <div class="container">
            <h2>Become a Host</h2>
            <p>Join our community of cooks and share your homemade meals with others.</p>
            <ul>
                <li>Earn extra income</li>
                <li>Flexible schedule</li>
                <li>Share your passion for cooking</li>
            </ul>
            <a href="#" class="btn">Join Now</a>
        </div>
    </section>

    <section id="about-us">
        <div class="container">
            <h2>About Us</h2>
            <p>Our mission is to connect communities through authentic, homemade food.</p>
        </div>
    </section>

    <section id="contact-us">
        <div class="container">
            <h2>Get in Touch</h2>
            <form action="#">
                <label for="name">Name</label>
                <input type="text" id="name" name="name">
                <label for="email">Email</label>
                <input type="email" id="email" name="email">
                <label for="message">Message</label>
                <textarea id="message" name="message"></textarea>
                <button type="submit">Send</button>
            </form>
        </div>
    </section>

    <footer>
        <div class="container">
            <p>&copy; 2024 Case.Ro Technologies, Inc. All rights reserved.</p>
        </div>
    </footer>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

.container {
    width: 80%;
    margin: 0 auto;
}

header {
    background: #f8b400;
    padding: 10px 0;
}

header h1 {
    margin: 0;
    font-size: 24px;
}

header nav ul {
    list-style: none;
    padding: 0;
}

header nav ul li {
    display: inline;
    margin: 0 10px;
}

header nav ul li a {
    text-decoration: none;
    color: #000;
}

.main-banner {
    background: url('banner-image.jpg') no-repeat center center/cover;
    color: white;
    text-align: center;
    padding: 100px 0;
}

.main-banner h2 {
    font-size: 36px;
}

.main-banner .btn {
    background: #f8b400;
    color: #000;
    padding: 10px 20px;
    text-decoration: none;
    margin: 10px;
    display: inline-block;
}

section {
    padding: 50px 0;
}

h2 {
    font-size: 28px;
}

ol, ul {
    margin: 20px 0;
    padding-left: 20px;
}

form {
    display: flex;
    flex-direction: column;
}

form label {
    margin: 10px 0 5px;
}

form input, form textarea {
    padding: 10px;
    margin-bottom: 10px;
    border: 1px solid #ccc;
    border-radius: 5px;
}

form button {
    background: #f8b400;
    color: #000;
    padding: 10px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
}

footer {
    background: #333;
    color: white;
    text-align: center;
    padding: 10px 0;
}
