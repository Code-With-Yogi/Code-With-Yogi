<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Yogesh Dahatonde | SDET Portfolio</title>

<!-- AOS Animation Library -->
<link href="https://cdnjs.cloudflare.com/ajax/libs/aos/2.3.4/aos.css" rel="stylesheet">

<!-- Font Awesome -->
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">

<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Segoe UI', sans-serif;
}

body {
    background: #0f172a;
    color: #fff;
    scroll-behavior: smooth;
}

/* Navbar */
nav {
    display: flex;
    justify-content: space-between;
    padding: 20px 10%;
    background: #111827;
    position: fixed;
    width: 100%;
    z-index: 1000;
}

nav h2 {
    color: #38bdf8;
}

nav a {
    color: white;
    text-decoration: none;
    margin-left: 20px;
    transition: 0.3s;
}

nav a:hover {
    color: #38bdf8;
}

/* Hero Section */
.hero {
    height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
    flex-direction: column;
    padding: 0 20px;
}

.hero h1 {
    font-size: 48px;
    margin-bottom: 15px;
}

.hero span {
    color: #38bdf8;
}

.hero p {
    font-size: 20px;
    margin-bottom: 25px;
}

.btn {
    padding: 12px 25px;
    background: #38bdf8;
    color: #000;
    border-radius: 6px;
    text-decoration: none;
    font-weight: bold;
    transition: 0.3s;
}

.btn:hover {
    background: #0ea5e9;
}

/* Section */
section {
    padding: 80px 10%;
}

section h2 {
    text-align: center;
    margin-bottom: 40px;
    font-size: 32px;
    color: #38bdf8;
}

/* Skills */
.skills-container {
    display: flex;
    justify-content: center;
    gap: 30px;
    flex-wrap: wrap;
}

.skill-card {
    background: #1e293b;
    padding: 25px;
    width: 280px;
    border-radius: 10px;
    transition: 0.4s;
}

.skill-card:hover {
    transform: translateY(-10px);
}

.skill-card h3 {
    margin-bottom: 15px;
    color: #38bdf8;
}

.skill-card ul {
    list-style: none;
}

.skill-card li {
    margin-bottom: 8px;
}

/* Projects */
.project-card {
    background: #1e293b;
    padding: 25px;
    margin: 20px auto;
    max-width: 600px;
    border-radius: 10px;
    text-align: center;
    transition: 0.4s;
}

.project-card:hover {
    transform: scale(1.05);
}

.project-card a {
    display: inline-block;
    margin-top: 10px;
    color: #38bdf8;
    text-decoration: none;
}

/* Contact */
.contact {
    text-align: center;
}

.contact i {
    font-size: 24px;
    margin: 15px;
    color: #38bdf8;
}

/* Footer */
footer {
    text-align: center;
    padding: 20px;
    background: #111827;
    margin-top: 40px;
}

/* Responsive */
@media(max-width:768px){
    .hero h1{
        font-size: 32px;
    }
}
</style>
</head>

<body>

<!-- Navbar -->
<nav>
    <h2>Yogesh</h2>
    <div>
        <a href="#about">About</a>
        <a href="#skills">Skills</a>
        <a href="#projects">Projects</a>
        <a href="#contact">Contact</a>
    </div>
</nav>

<!-- Hero Section -->
<div class="hero" id="about" data-aos="fade-up">
    <h1>Hi, I'm <span>Yogesh Dahatonde</span></h1>
    <p>SDET | QA Automation Engineer | Java • Rest Assured • Selenium • Jenkins</p>
    <a href="https://github.com/Code-With-Yogi" target="_blank" class="btn">
        View GitHub
    </a>
</div>

<!-- Skills Section -->
<section id="skills">
    <h2 data-aos="fade-up">Automation Expertise</h2>

    <div class="skills-container">

        <div class="skill-card" data-aos="fade-right">
            <h3><i class="fas fa-code"></i> API Automation</h3>
            <ul>
                <li>Rest Assured (Java)</li>
                <li>4000+ Test Cases Written</li>
                <li>JSON & Schema Validation</li>
                <li>Token Authentication</li>
            </ul>
        </div>

        <div class="skill-card" data-aos="fade-up">
            <h3><i class="fas fa-laptop-code"></i> UI Automation</h3>
            <ul>
                <li>Selenium WebDriver</li>
                <li>200+ UI Test Cases</li>
                <li>Page Object Model</li>
                <li>Cross Browser Testing</li>
            </ul>
        </div>

        <div class="skill-card" data-aos="fade-left">
            <h3><i class="fas fa-cogs"></i> Tools & CI/CD</h3>
            <ul>
                <li>Jenkins Integration</li>
                <li>OpenText Octane</li>
                <li>Maven & Git</li>
                <li>Agile Methodology</li>
            </ul>
        </div>

    </div>
</section>

<!-- Projects Section -->
<section id="projects">
    <h2 data-aos="zoom-in">Automation Projects</h2>

    <div class="project-card" data-aos="flip-left">
        <h3>API Automation Framework</h3>
        <p>Rest Assured + Java + TestNG + CI/CD Integration</p>
        <a href="https://github.com/Code-With-Yogi" target="_blank">View Project</a>
    </div>

    <div class="project-card" data-aos="flip-right">
        <h3>UI Automation Framework</h3>
        <p>Selenium WebDriver + Java + Maven</p>
        <a href="https://github.com/Code-With-Yogi" target="_blank">View Project</a>
    </div>

</section>

<!-- Contact Section -->
<section id="contact" class="contact">
    <h2 data-aos="fade-up">Contact Me</h2>
    <p data-aos="fade-up">Open to SDET / QA Automation opportunities</p>
    
    <a href="https://github.com/Code-With-Yogi" target="_blank">
        <i class="fab fa-github"></i>
    </a>
    <a href="https://linkedin.com" target="_blank">
        <i class="fab fa-linkedin"></i>
    </a>
    <a href="mailto:your-email@gmail.com">
        <i class="fas fa-envelope"></i>
    </a>
</section>

<footer>
    © 2026 Yogesh Dahatonde | SDET Portfolio
</footer>

<!-- AOS Script -->
<script src="https://cdnjs.cloudflare.com/ajax/libs/aos/2.3.4/aos.js"></script>
<script>
  AOS.init({
      duration: 1000,
      once: true
  });
</script>

</body>
</html>
