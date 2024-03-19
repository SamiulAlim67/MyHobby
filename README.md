<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cricket Hobby Website</title>
</head>
<body>
    <header>
        <h1>Welcome to My Cricket Hobby Website</h1>
        <nav>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">About</a></li>
                <li><a href="#">Gallery</a></li>
                <li><a href="#">Contact</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section>
            <h2>About Me</h2>
            <p>Hi.My name is Samiul Alim Sami.Im 23 years old.im a student of Ulsan college.Cricket is not just a game for me; it's my passion. I have been playing cricket since childhood and enjoy every aspect of it - from batting to bowling to fielding.</p>
        </section>

        <section>
            <h2>Gallery</h2>
            <figure>
                <img src="https://www-static-blogs.operacdn.com/india/wp-content/uploads/sites/8/2015/06/Friends-enjoying-cricket2.png" alt="Cricket Image 1">
                <figcaption>Enjoying a cricket match with friends.</figcaption>
            </figure>
            <figure>
                <img src="https://im.rediff.com/cricket/2015/oct/27sachin1.jpg" alt="Cricket Image 2">
                <figcaption>Practicing batting techniques at the nets.</figcaption>
            </figure>
        </section>

        <section>
            <h2>Contact Me</h2>
            <form>
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required><br>
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required><br>
                <label for="message">Message:</label>
                <textarea id="message" name="message" required></textarea><br>
                <input type="submit" value="Submit">
            </form>
        </section>
    </main>

    <footer>
        <p>&copy; 2024 Cricket Hobby Website. All rights reserved.</p>
    </footer>
</body>
</html>