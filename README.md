<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Shagun Sharma | Portfolio</title>
<link rel="stylesheet" href="style.css">
</head>

<body>

<header>
<h1>Shagun Sharma</h1>
<p>BCA Student | Web Developer | Data Analysis Enthusiast</p>

<nav>
<a href="#about">About</a>
<a href="#education">Education</a>
<a href="#skills">Skills</a>
<a href="#projects">Projects</a>
<a href="#internship">Internship</a>
<a href="#contact">Contact</a>
</nav>
</header>

<section id="about">
<h2>About Me</h2>
<p>
Motivated and detail-oriented BCA student at Surajmal University seeking
opportunities to apply knowledge of web development, design and business
technology. I enjoy building responsive websites and learning modern
technologies while improving my analytical and problem-solving skills.
</p>
</section>

<section id="education">
<h2>Education</h2>

<div class="card">
<h3>Bachelor of Computer Applications (BCA)</h3>
<p>Surajmal University – Pursuing (2026)</p>
<p>Current CGPA: 7.0</p>
</div>

<div class="card">
<h3>Intermediate (12th)</h3>
<p>CBSE – St. Mary Sr. Sec. School</p>
<p>Percentage: 61.8%</p>
</div>

<div class="card">
<h3>High School (10th)</h3>
<p>CBSE – St. Mary Sr. Sec. School</p>
<p>Percentage: 67.6%</p>
</div>

</section>

<section id="skills">
<h2>Skills</h2>

<ul>
<li>HTML</li>
<li>CSS</li>
<li>JavaScript</li>
<li>C Programming</li>
<li>Python (Basics)</li>
<li>Data Analysis</li>
<li>Responsive Web Design</li>
<li>MS Office (Excel, Word, PowerPoint)</li>
<li>Canva</li>
<li>Visual Studio Code</li>
</ul>

</section>

<section id="projects">
<h2>Projects</h2>

<div class="card">
<h3>Portfolio Website</h3>
<p>
Designed and developed a personal portfolio website using HTML, CSS and
JavaScript to showcase projects, skills and professional information.
Focused on responsive design and better user experience.
</p>
</div>

<div class="card">
<h3>Intrusion Detection System (Minor Project)</h3>
<p>
Developed a basic Intrusion Detection System as a college minor project
to analyze suspicious network activities and detect potential security
threats. The project helped in understanding cybersecurity concepts,
network monitoring and anomaly detection.
</p>
</div>

</section>

<section id="internship">
<h2>Internship</h2>

<div class="card">
<h3>Web Development Intern</h3>
<p>Prodesk IT & Engineering Services</p>
<p>Duration: 1 Month</p>

<p>
Worked on developing responsive web pages and improving UI layout.
Learned about client-side scripting, front-end design and teamwork
in a professional environment.
</p>

</div>

</section>

<section id="contact">
<h2>Contact</h2>

<p>Email: shagunsharma18.rdr@gmail.com</p>
<p>Phone: 7534971383</p>

<p>
LinkedIn:
<a href="https://www.linkedin.com/in/shagun-sharma-516480369" target="_blank">
View Profile
</a>
</p>

</section>

<footer>
<p>© 2026 Shagun Sharma | Portfolio</p>
</footer>

<script src="script.js"></script>

</body>
</html># personal.portfolio
body{
font-family: Arial, sans-serif;
margin:0;
background:#f1d2ed;


header{
background:#222;
color:white;
text-align:center;
padding:20px;
}

nav a{
color:pink;
margin:10px;
text-decoration:none;
font-weight:bold;
}

section{
padding:40px;
}

h2{
text-align:center;
margin-bottom:20px;
}

.card{
background:rgb(252, 249, 249);
padding:20px;
margin:15px auto;
width:80%;
border-radius:8px;
box-shadow:0 0 10px rgba(0,0,0,0.1);
}

ul{
list-style:none;
text-align:center;
}

ul li{
display:inline-block;
background:#f1d1f1;
color:white;
padding:10px 15px;
margin:5px;
border-radius:5px;
}

footer{
background:#222;
color:white;
text-align:center;
padding:10px;
}
// Simple smooth scroll effect

document.querySelectorAll('nav a').forEach(anchor => {
anchor.addEventListener('click', function(e) {
e.preventDefault();

document.querySelector(this.getAttribute('href')).scrollIntoView({
behavior: 'smooth'
});

});
});
