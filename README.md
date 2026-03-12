# Jesscamille16.github.io
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Jessie Guy | Portfolio</title>

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family: "Helvetica Neue", Arial, sans-serif;
}

body{
background:#0f172a;
color:white;
line-height:1.6;
}

.container{
width:90%;
max-width:1100px;
margin:auto;
}

/* NAVBAR */

nav{
background:#020617;
padding:20px 0;
position:sticky;
top:0;
}

nav ul{
display:flex;
justify-content:center;
gap:40px;
list-style:none;
}

nav a{
text-decoration:none;
color:#94a3b8;
font-weight:500;
}

nav a:hover{
color:white;
}

/* HERO */

.hero{
padding:80px 0;
text-align:center;
}

.hero h1{
font-size:3rem;
margin-bottom:15px;
}

.hero p{
color:#cbd5f5;
font-size:1.2rem;
}

/* SECTIONS */

section{
padding:60px 0;
}

h2{
margin-bottom:20px;
font-size:2rem;
}

/* PROJECT GRID */

.projects{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:25px;
}

.project-card{
background:#1e293b;
padding:25px;
border-radius:10px;
transition:0.3s;
}

.project-card:hover{
transform:translateY(-5px);
background:#334155;
}

.project-card h3{
margin-bottom:10px;
}

/* SKILLS */

.skills{
display:flex;
flex-wrap:wrap;
gap:10px;
}

.skill{
background:#334155;
padding:8px 14px;
border-radius:20px;
font-size:.9rem;
}

/* CONTACT */

.contact{
text-align:center;
}

.contact a{
color:#60a5fa;
text-decoration:none;
}

footer{
margin-top:40px;
text-align:center;
color:#64748b;
font-size:.9rem;
}

</style>
</head>

<body>

<nav>
<ul>
<li><a href="#about">About</a></li>
<li><a href="#projects">Projects</a></li>
<li><a href="#skills">Skills</a></li>
<li><a href="#contact">Contact</a></li>
</ul>
</nav>

<div class="container">

<section class="hero">
<h1>Jessie Guy</h1>
<p>Computer Science Graduate | Developer | Interactive Media</p>
</section>

<section id="about">
<h2>About Me</h2>
<p>
I am a Computer Science graduate from the University of South Alabama with
four years of experience working in the Computer Services Center. My background
includes software development, technical support, and interactive media
development using Unity and modern programming languages.
</p>

<p>
I enjoy building interactive applications and designing user-focused
experiences that combine creativity with technical problem solving.
</p>
</section>

<section id="projects">
<h2>Projects</h2>

<div class="projects">

<div class="project-card">
<h3>VR Escape Room</h3>
<p>
A virtual reality escape room experience developed in Unity featuring
puzzle-based gameplay and interactive objects.
</p>
</div>

<div class="project-card">
<h3>AR Starry Night Experience</h3>
<p>
Augmented reality project for Meta Quest 3 that brings the artwork
to life through AR marker detection and spatial audio.
</p>
</div>

<div class="project-card">
<h3>Space Shmup</h3>
<p>
A 2D shoot 'em up style game developed in Unity featuring enemy AI,
player upgrades, and fast paced gameplay.
</p>
</div>

<div class="project-card">
<h3>Quiz Data System</h3>
<p>
Unity project that automatically submits player quiz scores
to a Google Spreadsheet using Google Forms integration.
</p>
</div>

</div>
</section>

<section id="skills">
<h2>Skills</h2>

<div class="skills">
<span class="skill">C#</span>
<span class="skill">C++</span>
<span class="skill">Java</span>
<span class="skill">SQL</span>
<span class="skill">HTML</span>
<span class="skill">CSS</span>
<span class="skill">JavaScript</span>
<span class="skill">Unity</span>
<span class="skill">GitHub</span>
<span class="skill">Adobe Photoshop</span>
</div>

</section>

<section id="contact" class="contact">

<h2>Contact</h2>

<p>Email: your@email.com</p>
<p>GitHub: <a href="#">github.com/yourusername</a></p>

</section>

<footer>
<p>© 2026 Jessie Guy</p>
</footer>

</div>

</body>
</html>
