# m-website-creatio
Website for my web development company
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>M Website Creation - Professional Web Development Services</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <!-- Navigation -->
    <nav class="navbar">
        <div class="container">
            <div class="logo">M Website Creation</div>
            <ul class="nav-links">
                <li><a href="#home">Home</a></li>
                <li><a href="#services">Services</a></li>
                <li><a href="#portfolio">Portfolio</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="home" class="hero">
        <div class="container">
            <h1>Welcome to M Website Creation</h1>
            <p>Professional Web Development Services for Your Business</p>
            <button class="cta-button">Get Started</button>
        </div>
    </section>

    <!-- Services Section -->
    <section id="services" class="services">
        <div class="container">
            <h2>Our Services</h2>
            <div class="services-grid">
                <div class="service-card">
                    <h3>Web Design</h3>
                    <p>Beautiful, responsive designs that captivate your audience and drive conversions.</p>
                </div>
                <div class="service-card">
                    <h3>Web Development</h3>
                    <p>Custom websites built with the latest technologies for optimal performance.</p>
                </div>
                <div class="service-card">
                    <h3>E-Commerce</h3>
                    <p>Complete online store solutions to help you sell products and services online.</p>
                </div>
                <div class="service-card">
                    <h3>Maintenance</h3>
                    <p>Ongoing support and updates to keep your website secure and running smoothly.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Portfolio Section -->
    <section id="portfolio" class="portfolio">
        <div class="container">
            <h2>Recent Projects</h2>
            <div class="portfolio-grid">
                <div class="portfolio-item">
                    <div class="portfolio-placeholder">Project 1</div>
                    <h3>Project Title</h3>
                    <p>Description of your project and what you accomplished.</p>
                </div>
                <div class="portfolio-item">
                    <div class="portfolio-placeholder">Project 2</div>
                    <h3>Project Title</h3>
                    <p>Description of your project and what you accomplished.</p>
                </div>
                <div class="portfolio-item">
                    <div class="portfolio-placeholder">Project 3</div>
                    <h3>Project Title</h3>
                    <p>Description of your project and what you accomplished.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="about">
        <div class="container">
            <h2>About Us</h2>
            <p>M Website Creation is a dedicated team of web professionals committed to building exceptional digital experiences. With years of experience in web design and development, we help businesses establish a strong online presence.</p>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="contact">
        <div class="container">
            <h2>Get In Touch</h2>
            <form class="contact-form">
                <input type="text" placeholder="Your Name" required>
                <input type="email" placeholder="Your Email" required>
                <textarea placeholder="Your Message" rows="5" required></textarea>
                <button type="submit" class="submit-button">Send Message</button>
            </form>
        </div>
    </section>

    <!-- Footer -->
    <footer class="footer">
        <div class="container">
            <p>&copy; 2026 M Website Creation. All rights reserved.</p>
        </div>
    </footer>

    <script src="script.js"></script>
    * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

:root {
    --primary-color: #2c3e50;
    --secondary-color: #3498db;
    --accent-color: #e74c3c;
    --text-color: #333;
    --light-bg: #ecf0f1;
    --white: #fff;
}

html {
    scroll-behavior: smooth;
}

body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    line-height: 1.6;
    color: var(--text-color);
}

.container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 20px;
}

/* Navigation */
.navbar {
    background-color: var(--primary-color);
    color: var(--white);
    padding: 1rem 0;
    position: sticky;
    top: 0;
    z-index: 100;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
}

.navbar .container {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.logo {
    font-size: 1.5rem;
    font-weight: bold;
    color: var(--secondary-color);
}

.nav-links {
    display: flex;
    list-style: none;
    gap: 2rem;
}

.nav-links a {
    color: var(--white);
    text-decoration: none;
    transition: color 0.3s ease;
}

.nav-links a:hover {
    color: var(--secondary-color);
}

/* Hero Section */
.hero {
    background: linear-gradient(135deg, var(--primary-color) 0%, var(--secondary-color) 100%);
    color: var(--white);
    padding: 100px 0;
    text-align: center;
    min-height: 60vh;
    display: flex;
    align-items: center;
    justify-content: center;
}

.hero h1 {
    font-size: 3rem;
    margin-bottom: 1rem;
}

.hero p {
    font-size: 1.3rem;
    margin-bottom: 2rem;
}

.cta-button {
    background-color: var(--accent-color);
    color: var(--white);
    padding: 12px 30px;
    border: none;
    border-radius: 5px;
    font-size: 1rem;
    cursor: pointer;
    transition: background-color 0.3s ease;
}

.cta-button:hover {
    background-color: #c0392b;
}

/* Services Section */
.services {
    padding: 60px 0;
    background-color: var(--light-bg);
}

.services h2 {
    text-align: center;
    font-size: 2.5rem;
    margin-bottom: 3rem;
    color: var(--primary-color);
}

.services-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 2rem;
}

.service-card {
    background-color: var(--white);
    padding: 2rem;
    border-radius: 8px;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    transition: transform 0.3s ease, box-shadow 0.3s ease;
    text-align: center;
}

.service-card:hover {
    transform: translateY(-5px);
    box-shadow: 0 6px 12px rgba(0, 0, 0, 0.15);
}

.service-card h3 {
    color: var(--secondary-color);
    margin-bottom: 1rem;
    font-size: 1.5rem;
}

/* Portfolio Section */
.portfolio {
    padding: 60px 0;
}

.portfolio h2 {
    text-align: center;
    font-size: 2.5rem;
    margin-bottom: 3rem;
    color: var(--primary-color);
}

.portfolio-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 2rem;
}

.portfolio-item {
    background-color: var(--white);
    border-radius: 8px;
    overflow: hidden;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    transition: transform 0.3s ease;
}

.portfolio-item:hover {
    transform: scale(1.05);
}

.portfolio-placeholder {
    background: linear-gradient(135deg, var(--secondary-color), var(--primary-color));
    color: var(--white);
    height: 200px;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 1.5rem;
    font-weight: bold;
}

.portfolio-item h3 {
    padding: 1.5rem 1.5rem 0.5rem;
    color: var(--primary-color);
}

.portfolio-item p {
    padding: 0 1.5rem 1.5rem;
    color: #666;
}

/* About Section */
.about {
    background-color: var(--light-bg);
    padding: 60px 0;
    text-align: center;
}

.about h2 {
    font-size: 2.5rem;
    margin-bottom: 2rem;
    color: var(--primary-color);
}

.about p {
    font-size: 1.1rem;
    max-width: 600px;
    margin: 0 auto;
    line-height: 1.8;
}

/* Contact Section */
.contact {
    padding: 60px 0;
}

.contact h2 {
    text-align: center;
    font-size: 2.5rem;
    margin-bottom: 3rem;
    color: var(--primary-color);
}

.contact-form {
    max-width: 600px;
    margin: 0 auto;
    display: flex;
    flex-direction: column;
    gap: 1rem;
}

.contact-form input,
.contact-form textarea {
    padding: 12px;
    border: 1px solid #ddd;
    border-radius: 5px;
    font-family: inherit;
    font-size: 1rem;
}

.contact-form input:focus,
.contact-form textarea:focus {
    outline: none;
    border-color: var(--secondary-color);
    box-shadow: 0 0 5px rgba(52, 152, 219, 0.3);
}

.submit-button {
    background-color: var(--secondary-color);
    color: var(--white);
    padding: 12px 30px;
    border: none;
    border-radius: 5px;
    font-size: 1rem;
    cursor: pointer;
    transition: background-color 0.3s ease;
}

.submit-button:hover {
    background-color: #2980b9;
}

/* Footer */
.footer {
    background-color: var(--primary-color);
    color: var(--white);
    text-align: center;
    padding: 2rem 0;
}

/* Responsive Design */
@media (max-width: 768px) {
    .nav-links {
        gap: 1rem;
        font-size: 0.9rem;
    }

    .hero h1 {
        font-size: 2rem;
    }

    .hero p {
        font-size: 1rem;
    }

    .services h2,
    .portfolio h2,
    .about h2,
    .contact h2 {
        font-size: 2rem;
    }

    .services-grid,
    .portfolio-grid {
        grid-template-columns: 1fr;
    }
}
</body>
</html>
