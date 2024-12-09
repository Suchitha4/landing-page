# landing-page.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Landing Page</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <!-- Header -->
    <header>
        <nav>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">Features</a></li>
                <li><a href="#">Contact</a></li>   
                     </ul>
        </nav>
    </header>

    <!-- Main Section (Hero) -->
    <main>
        <section class="hero">
            <h1>Welcome to Our Website!</h1>
            <p>Your one-stop solution for all your needs.</p>
            <button>Get Started</button>
        </section>

        <!-- Features Section -->
        <section class="features">
            <div class="feature-box">
                <h2>Feature 1</h2>
                <p>Learn more about Feature 1 and how it can help you.</p>
            </div>
            <div class="feature-box">
                <h2>Feature 2</h2>
                <p>Discover the benefits of Feature 2 for your business.</p>
            </div>
            <div class="feature-box">
                <h2>Feature 3</h2>
                <p>Find out how Feature 3 makes everything easier.</p>
            </div>
        </section>
    </main>

    <!-- Footer -->
    <footer>
        <p>© 2024 Your Company. All rights reserved.</p>
    </footer>

</body>
</html>

# landing page.css
/* General Reset */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

/* Body Styling */
body {
    font-family: 'Arial', sans-serif;
    background-color: #f9f9f9;
    color: #333;
    line-height: 1.6;
}

/* Header (Introduction) */
.intro {
    background-color: #4CAF50;
    color: white;
    text-align: center;
    padding: 50px 0;
}

.profile-img {
    width: 150px;
    height: 150px;
    border-radius: 50%;
    margin-bottom: 20px;
}

.intro h1 {
    font-size: 2.5rem;
}

.intro p {
    font-size: 1.2rem;
    font-style: italic;
}

/* About Section */
.about {
    padding: 30px 20px;
    text-align: center;
    background-color: #ffffff;
}

.about h2 {
    font-size: 2rem;
    margin-bottom: 20px;
}

.about p {
    font-size: 1.1rem;
    color: #666;
}

/* Skills Section */
.skills {
    padding: 30px 20px;
    text-align: center;
    background-color: #f4f4f4;
}

.skills h2 {
    font-size: 2rem;
    margin-bottom: 20px;
}

.skills ul {
    list-style: none;
    display: flex;
    justify-content: center;
    gap: 30px;
}

.skills ul li {
    font-size: 1.1rem;
    background-color: #4CAF50;
    color: white;
    padding: 10px 20px;
    border-radius: 5px;
}

/* Projects Section */
.projects {
    padding: 30px 20px;
    background-color: #ffffff;
}

.projects h2 {
    font-size: 2rem;
    margin-bottom: 20px;
    text-align: center;
}

.project-card {
    background-color: #f4f4f4;
    padding: 20px;
    margin: 15px 0;
    border-radius: 5px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

.project-card h3 {
    font-size: 1.5rem;
    margin-bottom: 10px;
}

.project-card p {
    font-size: 1rem;
    color: #666;
}

/* Contact Section */
.contact {
    padding: 30px 20px;
    background-color: #4CAF50;
    color: white;
    text-align: center;
}

.contact a {
    color: #fff;
    text-decoration: underline;
}

/* Footer Section */
footer {
    padding: 15px;
    text-align: center;
    background-color: #333;
    color: white;
    font-size: 0.9rem;
}
