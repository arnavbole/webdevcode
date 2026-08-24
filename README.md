# webdevcode
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Forms</title>
</head>
<body>
    <h1>HTML Forms</h1>
    <p>This form collects some basic data</p>
    <form action="#">
        <h1>Text Inputs</h1>
        <label for="name">Name:</label>
        <input type="text" id="name" name="name" placeholder="Enter your name">
        <br>
        <label for="email">Email:</label>
        <input type="email" id="email" name="email" placeholder="Enter your email">
        <br>
        <label for="password">Password:</label>
        <input type="password" id="password" name="password" placeholder="Enter your password">
        <br>
        <label for="confirm-password">Confirm Password:</label>
        <input type="password" id="confirm-password" name="confirm-password" placeholder="Confirm your password">

        <!-- Checkbox Buttons -->
        <h1>Checkbox Buttons</h1>
        <label for="subscribe">Subscribe to our newsletter</label>
        <input type="checkbox" id="subscribe" name="subscribe">
        <br>
        <label for="terms">I agree to the terms and conditions</label>
        <input type="checkbox" id="terms" name="terms">
        <br>
        <label for="newsletter">I want to receive newsletter</label>
        <input type="checkbox" id="newsletter" name="newsletter">
        <br>
        <h1>Dropdown</h1>
        <label for="country">Select your country</label>
        <select id="country" name="country">
            <option value="india">India</option>
            <option value="usa">USA</option>
            <option value="uk">UK</option>
            <option value="canada">Canada</option>
        </select>
        <br>
    <h1>long text area</h1>
    <label for="message">Enter your message</label>
    <textarea id="message" name="message" placeholder="Enter your message"></textarea>
    <br>
    <button type="reset">Reset</button>
    <button type="submit">Submit</button>
    </form>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>
        My Portfolio
    </title>
</head>
<body>
    <header>
<h1>Ayushman Mishra</h1>
<p>Web Developer</p>
<nav>
    <a href="about.html">About</a>
    <a href="projects.html">Projects</a>
    <a href="contact.html">Contact</a>
</nav>
    </header>
    <main>
        <section id=""about>
            <h2>About me</h2>
            <img src="https://via.placeholder.com/150" alt="profile picture">
            <p>I am a student of Computer Science and Engineering</p>
            <p>goal is to become rich and famous</p>
            <ul>
                <li>html</li>
                <li>css</li>
                <li>javascript</li>
                <li>react</li>
            </ul>
        </section>
        <section id="projects">
            <h2>Projects</h2>
           <article>
            <h3>Project 1</h3>
            <p>Description of project 1</p>
            <a href="forms.html">View Project</a>
           </article>
           <article>
            <h3>Project 2</h3>
            <p>Description of project 2</p>
            <a href="forms.html">View Project</a>
           </article>
           <article>
            <h3>Project 3</h3>
            <p>Description of project 3</p>
            <a href="forms.html">View Project</a>
           </article>
        </section>
        <section id="education">
            <h2>Education</h2>
            <article>
                <h3>Bachelor of Technology</h3>
                <p>Computer Science and Engineering</p>
                <p>2020-2024</p>
                <p>University of Delhi</p>
            </article>
            <article>
                <h3>Master of Technology</h3>
                <p>Computer Science and Engineering</p>
                <p>2024-2026</p>
                <p>University of Delhi</p>
            </article>
        </section>
    </main>
    <footer>
        <p>Copyright 2026 Ayushman Mishra</p>
    </footer>
</body>
</html>
