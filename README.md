#webdevcode
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Forms</title>
</head>
<body>
    <h1>html forms</h1>
    <p>this form collects some basic data</p>
    <form action="">
    <h1>Text Inputs</h1>
    <label for="name">Name:</label>
    
    <input type="text" id="name" name="name" placeholder="Enter your Name">
    <br>
       <label for="Email">Email</label>
       <input type="Email"id="Email" name="Email" placeholder="Enter your Email"> 
       <br>
        <label for="password">password</label>
        <input type="password" id="password" name="password" placeholder="password">
        <br>
        <h1>checkbox Button</h1>
        <label for="subscirbe">Subscribe to my yt channel </label>
        <input type="checkbox" name="terms" id="terms">
        <br>
        <label for="newsletter">i want to receive newsletter</label>
        <input type="checkbox" name="terms" id="terms">
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
        <h1>long area </h1>
        <label for="message">Enter your message</label>
        <textarea name="message" id="message" placeholder="Enter your message"></textarea>
        <button type="reset">reset</button>
        <br>
        <button type="submit">submit</button>
    </form>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <header>
        <h1>ARNAV BOLE</h1>
        <P>WEB DEVELOPER</P>
        <nav>
            <a href="about.html">about</a>
            <a href="project.html">project</a>
            <a href="contact.html">contact</a>
        </nav>
    </header>
    <main>
        <section id=""about>
            <h2>About me </h2>
            <img src="" alt="profile picture">
            <p>i am a student of computer science </p>
            <ul>
                <li> html </li>
                <li> css </li>
                <li> javascript</li>
                <li>react </li>
            
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
                <p>MIT ADT University</p>
            </article>
            <article>
                <h3>Master of Technology</h3>
                <p>Computer Science and Engineering</p>
                <p>2024-2026</p>
                <p>MIT ADT University</p>
            </article>
        </section>
    </main>
    <footer>
        <p>Copyright 2026 ARNAV BOLE</p>
    </footer>

</body>
</html>

