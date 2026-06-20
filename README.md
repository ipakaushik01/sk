<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>S.K Engineers & Contractors</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:'Poppins',sans-serif;
}

body{
background:#f8f9fa;
color:#222;
}

.container{
width:90%;
max-width:1200px;
margin:auto;
}

/* HEADER */

header{
background:#0f172a;
padding:20px 0;
position:sticky;
top:0;
z-index:1000;
}

nav{
display:flex;
justify-content:space-between;
align-items:center;
}

.logo{
color:#fff;
font-size:28px;
font-weight:700;
}

nav ul{
display:flex;
list-style:none;
gap:30px;
}

nav ul li a{
color:white;
text-decoration:none;
font-weight:500;
}

/* HERO */

.hero{
height:90vh;
background:
linear-gradient(rgba(0,0,0,.65),rgba(0,0,0,.65)),
url('https://images.unsplash.com/photo-1504307651254-35680f356dfd');
background-size:cover;
background-position:center;
display:flex;
align-items:center;
}

.hero-content{
color:white;
max-width:700px;
}

.hero h1{
font-size:58px;
margin-bottom:20px;
}

.hero p{
font-size:20px;
margin-bottom:30px;
line-height:1.6;
}

.btn{
display:inline-block;
background:#f97316;
color:white;
padding:15px 35px;
text-decoration:none;
border-radius:5px;
font-weight:600;
}

/* ABOUT */

section{
padding:80px 0;
}

.section-title{
text-align:center;
margin-bottom:50px;
font-size:40px;
}

.about-grid{
display:grid;
grid-template-columns:1fr 1fr;
gap:50px;
align-items:center;
}

.about img{
width:100%;
border-radius:10px;
}

/* STATS */

.stats{
background:#0f172a;
color:white;
}

.stats-grid{
display:grid;
grid-template-columns:repeat(4,1fr);
gap:20px;
text-align:center;
}

.stat h2{
font-size:50px;
color:#f97316;
}

/* SERVICES */

.services-grid{
display:grid;
grid-template-columns:repeat(3,1fr);
gap:30px;
}

.card{
background:white;
padding:30px;
border-radius:10px;
box-shadow:0 5px 20px rgba(0,0,0,.08);
transition:.3s;
}

.card:hover{
transform:translateY(-8px);
}

.card h3{
margin-bottom:15px;
}

/* PROJECTS */

.projects{
background:#f1f5f9;
}

.project-grid{
display:grid;
grid-template-columns:repeat(3,1fr);
gap:25px;
}

.project{
background:white;
border-radius:10px;
overflow:hidden;
}

.project img{
width:100%;
height:220px;
object-fit:cover;
}

.project-content{
padding:20px;
}

/* TESTIMONIALS */

.testimonial-grid{
display:grid;
grid-template-columns:repeat(3,1fr);
gap:25px;
}

.testimonial{
background:white;
padding:30px;
border-radius:10px;
box-shadow:0 5px 20px rgba(0,0,0,.08);
}

/* CTA */

.cta{
background:#f97316;
color:white;
text-align:center;
}

.cta h2{
font-size:42px;
margin-bottom:20px;
}

/* CONTACT */

.contact-grid{
display:grid;
grid-template-columns:1fr 1fr;
gap:40px;
}

input,textarea{
width:100%;
padding:15px;
margin-bottom:15px;
border:1px solid #ddd;
border-radius:5px;
}

button{
background:#0f172a;
color:white;
padding:15px 30px;
border:none;
cursor:pointer;
}

/* FOOTER */

footer{
background:#0f172a;
color:white;
text-align:center;
padding:30px;
}

@media(max-width:768px){

.hero h1{
font-size:38px;
}

.about-grid,
.contact-grid,
.stats-grid,
.services-grid,
.project-grid,
.testimonial-grid{
grid-template-columns:1fr;
}

nav ul{
display:none;
}
}

</style>
</head>

<body>

<header>
<div class="container">
<nav>
<div class="logo">S.K Engineers</div>

<ul>
<li><a href="#">Home</a></li>
<li><a href="#">About</a></li>
<li><a href="#">Services</a></li>
<li><a href="#">Projects</a></li>
<li><a href="#">Contact</a></li>
</ul>
</nav>
</div>
</header>

<section class="hero">
<div class="container">
<div class="hero-content">

<h1>Building Excellence, Delivering Trust</h1>

<p>
Leading Civil Engineering & Construction Company delivering
Industrial, Commercial & Residential Projects across India.
</p>

<a href="#" class="btn">Request a Quote</a>

</div>
</div>
</section>

<section class="about">
<div class="container">

<h2 class="section-title">About Us</h2>

<div class="about-grid">

<div>
<h3>Who We Are</h3>

<p>
S.K Engineers & Contractors is a trusted construction and
engineering company committed to delivering high-quality
infrastructure projects with safety, innovation and excellence.
</p>

<br>

<p>
From industrial facilities to residential developments,
our experienced team ensures timely and cost-effective project
execution.
</p>
</div>

<img src="https://images.unsplash.com/photo-1541888946425-d81bb19240f5">

</div>
</div>
</section>

<section class="stats">

<div class="container">

<div class="stats-grid">

<div class="stat">
<h2>150+</h2>
<p>Projects Completed</p>
</div>

<div class="stat">
<h2>20+</h2>
<p>Years Experience</p>
</div>

<div class="stat">
<h2>50+</h2>
<p>Equipment Units</p>
</div>

<div class="stat">
<h2>100%</h2>
<p>Client Satisfaction</p>
</div>

</div>
</div>
</section>

<section>

<div class="container">

<h2 class="section-title">Our Services</h2>

<div class="services-grid">

<div class="card">
<h3>Industrial Construction</h3>
<p>Factories, warehouses, plants and industrial facilities.</p>
</div>

<div class="card">
<h3>Commercial Projects</h3>
<p>Office buildings, retail complexes and commercial spaces.</p>
</div>

<div class="card">
<h3>Residential Construction</h3>
<p>Apartments, villas and residential developments.</p>
</div>

<div class="card">
<h3>Civil Engineering</h3>
<p>Roads, drainage systems and infrastructure works.</p>
</div>

<div class="card">
<h3>Project Management</h3>
<p>Planning, execution and quality control services.</p>
</div>

<div class="card">
<h3>Turnkey Solutions</h3>
<p>End-to-end construction project delivery.</p>
</div>

</div>

</div>
</section>

<section class="projects">

<div class="container">

<h2 class="section-title">Featured Projects</h2>

<div class="project-grid">

<div class="project">
<img src="https://images.unsplash.com/photo-1486406146926-c627a92ad1ab">
<div class="project-content">
<h3>Industrial Plant</h3>
<p>Large-scale industrial infrastructure project.</p>
</div>
</div>

<div class="project">
<img src="https://images.unsplash.com/photo-1511818966892-d7d671e672a2">
<div class="project-content">
<h3>Commercial Complex</h3>
<p>Modern commercial development.</p>
</div>
</div>

<div class="project">
<img src="https://images.unsplash.com/photo-1460317442991-0ec209397118">
<div class="project-content">
<h3>Residential Township</h3>
<p>Premium housing project.</p>
</div>
</div>

</div>

</div>
</section>

<section>

<div class="container">

<h2 class="section-title">Client Testimonials</h2>

<div class="testimonial-grid">

<div class="testimonial">
★★★★★
<br><br>
"S.K Engineers delivered our project on time and exceeded expectations."
<br><br>
<strong>Industrial Client</strong>
</div>

<div class="testimonial">
★★★★★
<br><br>
"Outstanding quality and professionalism throughout the project."
<br><br>
<strong>Commercial Developer</strong>
</div>

<div class="testimonial">
★★★★★
<br><br>
"Reliable partner with excellent technical expertise."
<br><br>
<strong>Project Consultant</strong>
</div>

</div>

</div>
</section>

<section class="cta">

<div class="container">

<h2>Let's Build Something Great Together</h2>

<p>Contact our team for your next construction project.</p>

<br>

<a href="#" class="btn">Get Free Consultation</a>

</div>
</section>

<section>

<div class="container">

<h2 class="section-title">Contact Us</h2>

<div class="contact-grid">

<div>
<h3>S.K Engineers & Contractors</h3>

<br>

<p>📞 +91 XXXXX XXXXX</p>
<p>📧 info@skengineers.com</p>
<p>📍 Punjab, India</p>
</div>

<form>

<input type="text" placeholder="Your Name">

<input type="email" placeholder="Email Address">

<input type="text" placeholder="Phone Number">

<textarea rows="5" placeholder="Your Message"></textarea>

<button>Submit Inquiry</button>

</form>

</div>

</div>
</section>

<footer>
© 2025 S.K Engineers & Contractors | All Rights Reserved
</footer>

</body>
</html>
