# Portfolio
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>BEAS -Portfolio</title>
    <link rel="stylesheet" href="styles.css">
    <script src="scripts.js" defer></script>
</head>
<body>
    <header>
        <nav>
            <h1>BEAS JHA</h1>
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#skills">Skills</a></li>
                <li><a href="#certification">Certification</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section class="hero">
        <div class="hero-content">
            <h2>Hi,I'm<span class="highlight">BEAS JHA<span></h2>
            <h2><p>Data Science Enthusiast | AI & ML Developer | Web Innovator</p></h2>
            <a href="#contact" class="btn">Get in Touch</a>
        </div>
    </section>

    <section id="about">
        <h1>About Me</h1>
        <h2><p>I'm a 3rd-year Data Science student passionate about solving real-world problems using AI, ML, and scalable data solutions.</p></h2>
    </section>

    <section id="projects">
        <h2>My Projects</h2>
        <div class="project-container">
            <div class="project-box">
            <h2>Diabetes Prediction</h2>
            <p>Developed a regression model to predict Diabetes in Paitents with 90% accuracy.</p>
            <a href="https://github.com/Beasjha/Diabetes-Prediction" target="_blank">Learn more</a>
        </div>
        <div class="project-container"></div>
            <h2>Machine Learning Algorithms</h2>
            <p>Worked on various supervised and unsupervised machine learning algorithms to build predictive models.</p>
            <a href="https://github.com/Beasjha" target="_blank">Learn more</a>
        </div>
        <div class="project-container"></div>
            <h2>Calculator</h2>
            <p>Built a Calculator using Python and its Libraries.</p>
            <a href="https://github.com/Beasjha/Claculator" target="_blank">Learn more</a>
        </div>
    </section>

    <section id="skills">
        <h2>Skills</h2>
        <div class="skills-container">
            <div class="skill-row">
                <div class="skill-box">Python</div>
            </div>
            <p>Basics of Python and use of Numpy, Pandas used for Data Science.</p>
            
            <div class="skill-row">
                <div class="skill-box">SQL</div>
            </div>
            <p>I have strong SQL skills, enabling me to efficiently manage, query, and analyze structured data for data-driven decision-making.</p>
    
            <div class="skill-row">
                <div class="skill-box">Machine Learning</div>
            </div>
            <p>I have knowledge in Machine Learning, building predictive models to solve real-world problems.</p>
    
            <div class="skill-row">
                <div class="skill-box">Data Visualization</div>
            </div>
            <p>I have proficiency in data visualization using Matplotlib and Seaborn, creating insightful and visually appealing graphs for data analysis.</p>
        </div>
    </section>
    

    <section id="certification">
        <h2>Certification</h2>
        <div class="certification-container">
            <div class="certification-row">
                <div class="certification-box">SQL (Basic) Certificate</div>
            </div>
            <div class="certification-row">
                <div class="certification-box">Front End Development - HTML</div>
            </div>
            <div class="certification-row">
                <div class="certification-box">NumPy, SciPy, Matplotlib & Pandas A-Z</div>
            </div>
            <div class="certification-row">
                <div class="certification-box">Introduction to Generative AI</div>
            </div>
        </div>
    </section>
    

    <section id="contact">
        <h2>Contact Me</h2>
        <div class="contact-container">
            <div class="contact-info">
                <p><img src="email.png" alt="Email Icon">beasjha@gmail@gmail.com</p>
                <p><img src="phone.png" alt="Phone Icon"> +91 9822801046</p>
            <div class="social-links">
            <p><a href="https://www.linkedin.com/in/beas-jha-10525b2b3/" target="_blank"><img src="linkedin.png" alt="LinkedIn"></p>
            </a>
           <p><a href="https://github.com/Beasjha" target="_blank"><img src="github.png" alt="GitHub"></p>
            </a>
        </div>
        <button class="cv-button">Download CV</button>
       </div>
       <div class="contact-form">
        <form id="contact-form">
            <input type="text" id="name" placeholder="Your Name" required>
            <input type="email" id="email" placeholder="Your Email" required>
            <textarea id="message" placeholder="Your Message" required></textarea>
            <button type="submit" class="submit-button">Submit</button>
        </form>
    </div>
</div>
</section>
/* Import Font */
@import url('https://fonts.googleapis.com/css2?family=Orbitron:wght@400;700&display=swap');

body {
    font-family: 'Orbitron', sans-serif;
    background: #0a0a0a;
    color: white;
    margin: 0;
    padding: 0;
    text-align: center;
}

header {
    background: rgba(0, 0, 0, 0.8);
    padding: 15px 0;
    position: fixed;
    width: 100%;
    top: 0;
    z-index: 1000;
    box-shadow: 0px 0px 15px #00eaff;
}

nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 0 30px;
}

nav ul {
    list-style: none;
    display: flex;
}

nav ul li {
    margin: 0 15px;
}

nav ul li a {
    color: #00eaff;
    text-decoration: none;
    font-size: 18px;
    transition: 0.3s;
}

nav ul li a:hover {
    color: #ff007f;
    text-shadow: 0 0 5px #ff007f;
}

/* Hero Section */
.hero {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    background: url("C:\Users\beasj\beas\Project\Beu.jpg") no-repeat center center/cover;
    text-align: center;
}

.hero-content h2 {
    font-size: 2.5em;
    color: white;
}

.hero-content .highlight {
    color: #00eaff;
    text-shadow: 0 0 10px #00eaff;
}

.btn {
    background: #00eaff;
    padding: 10px 20px;
    color: white;
    border-radius: 5px;
    text-decoration: none;
    font-size: 28px;
    transition: 0.3s;
}

.btn:hover {
    background: #ff007f;
    box-shadow: 0 0 15px #ff007f;
}

/* Sections */
section {
    padding: 80px 20px;
    max-width: 900px;
    margin: auto;
}

#projects {
    text-align: center;
    padding: 50px;
    color: white;
}

.project-container {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); /* Responsive columns */
    gap: 30px;
    justify-content: center;
    align-items: stretch;
}

.project-box {
    background-color: #1a1a1a;
    padding: 30px;
    border-radius: 10px;
    text-align: center;
    transition: transform 0.3s ease-in-out;
}

.project-box:hover {
    transform: scale(1.05);
}

.project-box h3 {
    font-size: 22px;
    margin-bottom: 10px;
}

.project-box p {
    font-size: 16px;
    color: #ddd;
}


/* Skills */
.skills-container {
    display: flex;
    flex-direction: column; /* Ensure stacking */
    align-items: center;
    gap: 20px;
    max-width: 800px;
    margin: auto;
}

.skill-row {
    display: flex;
    justify-content: center;
    gap: 20px;
    flex-wrap: wrap; /* Ensures wrapping for responsiveness */
}

.skill-box {
    background: #222;
    padding: 10px 20px;
    border-radius: 8px;
    text-align: center;
    color: white;
    font-weight: bold;
    min-width: 120px;
}

/*Cerifications*/
.certification-container {
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 20px;
    max-width: 800px;
    margin: auto;
}

.certification-row {
    display: flex;
    justify-content: center;
    gap: 20px;
    flex-wrap: wrap; /* Ensures wrapping for responsiveness */
}

.certification-box {
    background: #222;
    padding: 10px 20px;
    border-radius: 8px;
    text-align: center;
    color: white;
    font-weight: bold;
    min-width: 200px;
}


/* Contact */
#contact {
    text-align: left;
    padding: 50px;
    color: white;
}

h2 {
    font-size: 40px;
    font-weight: bold;
}

.contact-container {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.contact-info {
    flex: 1;
}

.contact-info p {
    display: flex;
    align-items: center;
    gap: 10px;
    font-size: 18px;
}

.contact-info img {
    width: 25px;
    height: 25px;
}

.social-links {
    display: flex;
    gap: 15px;
    margin-top: 15px;
}

.social-links img {
    width: 40px;
    height: 40px;
    transition: transform 0.3s ease-in-out;
}

.social-links img:hover {
    transform: scale(1.2);
}

.cv-button {
    background-color: #1abc9c;
    color: white;
    font-size: 18px;
    border: none;
    padding: 10px 20px;
    cursor: pointer;
    border-radius: 5px;
    margin-top: 20px;
}

.cv-button:hover {
    background-color: #16a085;
}

.contact-form {
    flex: 1;
}

.contact-form input,
.contact-form textarea {
    width: 100%;
    padding: 10px;
    margin-bottom: 10px;
    background: #1a1a1a;
    border: none;
    color: white;
    font-size: 16px;
}

.contact-form textarea {
    height: 150px;
}

.submit-button {
    background-color: #1abc9c;
    color: white;
    font-size: 18px;
    border: none;
    padding: 10px 20px;
    cursor: pointer;
    border-radius: 5px;
}

.submit-button:hover {
    background-color: #16a085;
}
document.addEventListener("DOMContentLoaded", function() {
    // Smooth Scrolling for Navigation
    document.querySelectorAll("nav ul li a").forEach(anchor => {
        anchor.addEventListener("click", function(e) {
            e.preventDefault();
            const targetId = this.getAttribute("href").substring(1);
            const targetSection = document.getElementById(targetId);
            targetSection.scrollIntoView({ behavior: "smooth" });
        });
    });

    // Hero Text Animation
    const heroText = document.querySelector(".hero-content h2");
    const textArray = ["BIAS", "Data Scientist", "AI Innovator", "Tech Enthusiast"];
    let textIndex = 0;

    setInterval(() => {
        heroText.innerHTML = `Hi, I'm <span class="highlight">${textArray[textIndex]}</span>`;
        textIndex = (textIndex + 1) % textArray.length;
    }, 2000);
});


</body>
</html>


