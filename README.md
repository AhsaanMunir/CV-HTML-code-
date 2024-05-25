<!DOCTYPE html>
<html lang="en">
<head>
    <title>Personal Portfolio</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="container">
            <h1>Ahsaan Munir</h1>
            <h2>Begnieer web Developer</h2>
            <p>"Crafting Digital Experiences through Innovative Web Solutions"</p>
        </div>
    </header>

    <section id="education">
        <div class="container">
            <h2>Education</h2>
            <ul>
                <li>Metric</li>
                <li>Intermediate</li>
                <li>Bachelor's Degree(BSCS)(Continue)</li>
            </ul>
        </div>
    </section>

    <section id="skills">
        <div class="container">
            <h2>Skills</h2>
            <ul>
                <li>HTML (Hypertext Markup Language)</li>
                <li>CSS (Cascading Style Sheets)</li>
                <li>JavaScript</li>
            </ul>
        </div>
    </section>

    <section id="experience">
        <div class="container">
            <h2>Experience</h2>
            <p>Dynamic web developer with over 2 years of experience crafting engaging and responsive websites. Proficient in a wide range of programming languages including HTML, CSS, JavaScript, and frameworks.  </p>
        </div>
    </section>

    <section id="projects">
        <div class="container">
            <h2>Complete Projects</h2>
	    <ul>
            	<li>University Management System using (C# Windows winform)(My Sql)</li>
	    	<li>Farmacy System using (C++)</li>
		<li>Web Page using (HTML)(Jawa Script)</li>
        </div>
    </section>

    <section id="contact">
        <div class="container">
            <h2>Contact Form</h2>
            <form action="#" method="POST">
                <label for="name">Name:</label><br>
                <input type="text" id="name" name="name" required><br>
                <label for="email">Email:</label><br>
                <input type="email" id="email" name="email" required><br>
                <label for="message">Message:</label><br>
                <textarea id="message" name="message" rows="4" cols="50" required></textarea><br>
                <input type="submit" value="Submit">
            </form>
        </div>
    </section>
</body>
</html>
