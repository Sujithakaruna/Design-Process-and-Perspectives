<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hospital Management System</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Hospital Management System</h1>
        <nav>
            <ul>
               <li><a href="#home">Home</a></li>
                <li><a href="#about">About Us</a></li>
                <li><a href="#services">Services</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section id="home">
            <h2>Welcome to Our Hospital</h2>
            <p>Your health is our priority. We offer a wide range of medical services.</p>
        </section>
        <section id="about">
           <h2>About Us</h2>
            <p>We are committed to providing high-quality healthcare services to our patients.</p>
        </section>
        <section id="services">
            <h2>Our Services</h2>
            <ul>
                <li>Emergency Care</li>
               <li>Surgery</li>
                <li>Outpatient Services</li>
                <li>Laboratory Services</li>
                <li>Pharmacy</li>
            </ul>
        </section>
      <section id="contact">
            <h2>Contact Us</h2>
            <form>
                <label for="name">Name:</label>
                <input type="text" id="name" required>
                <label for="email">Email:</label>
                <input type="email" id="email" required>
                <label for="message">Message:</label>
                <textarea id="message" required></textarea>
                <button type="submit">Submit</button>
            </form>
      </section>
    </main>
    <footer>
        <p>&copy; 2024 Hospital Management System. All rights reserved.</p>
    </footer>
</body>
</html>
