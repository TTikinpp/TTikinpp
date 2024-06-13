<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>@tt_ikinpp's Personal Website</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f8ff;
            color: #333;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #4caf50;
            color: white;
            padding: 1em 0;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #008080;
            padding: 1em 0;
        }
        nav a {
            color: white;
            margin: 0 1em;
            text-decoration: none;
            font-weight: bold;
        }
        section {
            padding: 2em;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 1em 0;
            position: absolute;
            bottom: 0;
            width: 100%;
        }
        .container {
            max-width: 1200px;
            margin: auto;
            padding: 0 2em;
        }
        .earth-element {
            background-image: url('https://example.com/earth.jpg');
            background-size: cover;
            background-position: center;
            padding: 4em 0;
            color: white;
            text-align: center;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to @tt_ikinpp's Personal Website</h1>
    </header>
    <nav>
        <a href="#about">About Me</a>
        <a href="#portfolio">Portfolio</a>
        <a href="#blog">Blog</a>
        <a href="#contact">Contact</a>
    </nav>
    <div class="earth-element">
        <h2>Exploring the World Through My Eyes</h2>
    </div>
    <section id="about" class="container">
        <h2>About Me</h2>
        <p>Hello! I'm @tt_ikinpp. Welcome to my personal website. Here, you can learn more about me, explore my portfolio, read my blog, and get in touch.</p>
    </section>
    <section id="portfolio" class="container">
        <h2>

```html
        Portfolio</h2>
        <p>Here is a collection of my work. Stay tuned for updates!</p>
    </section>
    <section id="blog" class="container">
        <h2>Blog</h2>
        <p>Welcome to my blog. Here, I share my thoughts and experiences. Check back often for new posts!</p>
    </section>
    <section id="contact" class="container">
        <h2>Contact Me</h2>
        <form action="mailto:wyh20090606@foxmail.com" method="post" enctype="text/plain">
            <label for="name">Name:</label><br>
            <input type="text" id="name" name="name" required><br><br>
            <label for="email">Email:</label><br>
            <input type="email" id="email" name="email" required><br><br>
            <label for="message">Message:</label><br>
            <textarea id="message" name="message" rows="4" required></textarea><br><br>
            <input type="submit" value="Send">
        </form>
        <p>Or reach me at: 15839442467</p>
    </section>
    <footer>
        <p>&copy; 2024 @tt_ikinpp. All rights reserved.</p>
    </footer>
</body>
</html>