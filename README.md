<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>M.A.J Presents</title>
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;700;900&display=swap" rel="stylesheet">
<style>
*{margin:0;padding:0;box-sizing:border-box;font-family:'Poppins',sans-serif}
body{background:#000;color:#fff}
header{padding:20px 8%;display:flex;justify-content:space-between;align-items:center}
.logo{color:#fbbf24;font-weight:700;font-size:20px;letter-spacing:3px}
nav a{color:#fff;text-decoration:none;margin-left:25px;font-size:14px}
.hero{height:100vh;display:flex;flex-direction:column;justify-content:center;padding:0 8%}
.hero h1{font-size:60px;font-weight:900}
.hero h1 span{color:#fbbf24}
.hero p{margin:20px 0;color:#aaa;font-size:18px}
.btns{margin-top:20px}
.btn{
padding:12px 30px;
border-radius:30px;
text-decoration:none;
font-weight:600;
margin-right:15px;
display:inline-block;
}
.btn-primary{background:#fbbf24;color:#000}
.btn-outline{border:1px solid #555;color:#fff}
section{padding:80px 8%}
.section-title{font-size:35px;margin-bottom:40px;color:#fbbf24}
.services{display:grid;grid-template-columns:repeat(auto-fit,minmax(250px,1fr));gap:30px}
.card{
background:#111;
padding:30px;
border-radius:10px;
transition:0.3s;
}
.card:hover{transform:translateY(-10px);background:#1a1a1a}
footer{text-align:center;padding:20px;background:#111;color:#777}
input,textarea{
width:100%;
padding:12px;
margin:10px 0;
background:#111;
border:1px solid #333;
color:#fff;
border-radius:5px;
}
button{
background:#fbbf24;
border:none;
padding:12px 30px;
border-radius:25px;
font-weight:600;
cursor:pointer;
}
</style>
</head>
<body>

<header>
<div class="logo">M.A.J PRESENTS</div>
<nav>
<a href="#">Home</a>
<a href="#services">Services</a>
<a href="#about">About</a>
<a href="#contact">Contact</a>
</nav>
</header>

<div class="hero">
<h1>The Rise of an <span>Empire</span></h1>
<p>From Khairabad to the World — a vision, a mission, a future foundation.</p>
<div class="btns">
<a href="#services" class="btn btn-primary">Explore Services</a>
<a href="#contact" class="btn btn-outline">Connect</a>
</div>
</div>

<section id="services">
<h2 class="section-title">Our Services</h2>
<div class="services">
<div class="card">
<h3>Media Production</h3>
<p>Drama, films, comedy & digital content creation.</p>
</div>
<div class="card">
<h3>App Development</h3>
<p>Android & Web applications for future growth.</p>
</div>
<div class="card">
<h3>Web Development</h3>
<p>Modern, responsive & powerful websites.</p>
</div>
<div class="card">
<h3>Branding & Design</h3>
<p>Logos, posters, banners & full brand identity.</p>
</div>
</div>
</section>

<section id="about">
<h2 class="section-title">About M.A.J</h2>
<p>M.A.J Presents is not just a name — it is a mission to build an unshakeable empire across media, IT and digital innovation. Founded by CEO Muhammad Abdul Jalil, the vision is to serve Pakistan and the world.</p>
</section>

<section id="contact">
<h2 class="section-title">Contact Us</h2>
<form>
<input type="text" placeholder="Your Name" required>
<input type="email" placeholder="Your Email" required>
<textarea rows="5" placeholder="Your Message"></textarea>
<button type="submit">Send Message</button>
</form>
</section>

<footer>
© 2026 M.A.J Presents | All Rights Reserved
</footer>

</body>
</html>
