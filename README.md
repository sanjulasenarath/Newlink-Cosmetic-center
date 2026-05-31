<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Newlink Cosmetic Center</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial, sans-serif;
}

body{
    background:#f8f8f8;
    color:#333;
}

header{
    background:linear-gradient(rgba(0,0,0,0.5),rgba(0,0,0,0.5)),
    url('https://images.unsplash.com/photo-1522335789203-aabd1fc54bc9');
    background-size:cover;
    background-position:center;
    height:100vh;
    color:white;
    display:flex;
    justify-content:center;
    align-items:center;
    text-align:center;
}

.hero h1{
    font-size:60px;
    margin-bottom:15px;
}

.hero p{
    font-size:24px;
    margin-bottom:25px;
}

.btn{
    display:inline-block;
    padding:15px 35px;
    background:gold;
    color:black;
    text-decoration:none;
    border-radius:30px;
    font-weight:bold;
}

nav{
    position:fixed;
    top:0;
    width:100%;
    background:white;
    padding:15px;
    box-shadow:0 2px 10px rgba(0,0,0,.1);
    z-index:1000;
}

nav ul{
    display:flex;
    justify-content:center;
    list-style:none;
}

nav ul li{
    margin:0 20px;
}

nav ul li a{
    text-decoration:none;
    color:#333;
    font-weight:bold;
}

section{
    padding:80px 10%;
}

.section-title{
    text-align:center;
    margin-bottom:50px;
    font-size:40px;
    color:#c9a227;
}

.services{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:25px;
}

.card{
    background:white;
    padding:25px;
    border-radius:15px;
    text-align:center;
    box-shadow:0 5px 15px rgba(0,0,0,.1);
}

.card h3{
    margin-bottom:15px;
    color:#c9a227;
}

.gallery{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(300px,1fr));
    gap:20px;
}

.gallery img{
    width:100%;
    border-radius:15px;
}

.about{
    text-align:center;
    line-height:1.8;
}

.contact{
    text-align:center;
}

.contact p{
    margin:10px 0;
}

footer{
    background:#111;
    color:white;
    text-align:center;
    padding:20px;
}
</style>

</head>
<body>

<nav>
<ul>
<li><a href="#home">Home</a></li>
<li><a href="#services">Services</a></li>
<li><a href="#gallery">Gallery</a></li>
<li><a href="#about">About</a></li>
<li><a href="#contact">Contact</a></li>
</ul>
</nav>

<header id="home">
<div class="hero">
<h1>Newlink Cosmetic Center</h1>
<p>Enhance Your Beauty • Elevate Your Confidence</p>
<a href="#contact" class="btn">Book Appointment</a>
</div>
</header>

<section id="services">
<h2 class="section-title">Our Services</h2>

<div class="services">

<div class="card">
<h3>Skin Care Treatments</h3>
<p>Professional skin care solutions for healthy and glowing skin.</p>
</div>

<div class="card">
<h3>Facial Treatments</h3>
<p>Luxury facial treatments designed to rejuvenate your skin.</p>
</div>

<div class="card">
<h3>Beauty Consultation</h3>
<p>Expert beauty consultations tailored to your needs.</p>
</div>

<div class="card">
<h3>Cosmetic Procedures</h3>
<p>Advanced cosmetic services with professional care.</p>
</div>

</div>
</section>

<section id="gallery">
<h2 class="section-title">Gallery</h2>

<div class="gallery">

<img src="https://images.unsplash.com/photo-1524504388940-b1c1722653e1">
<img src="https://images.unsplash.com/photo-1515377905703-c4788e51af15">
<img src="https://images.unsplash.com/photo-1487412720507-e7ab37603c6f">

</div>
</section>

<section id="about">
<h2 class="section-title">About Us</h2>

<div class="about">
<p>
Welcome to Newlink Cosmetic Center. We are dedicated to helping
our clients achieve their beauty goals through professional cosmetic
care, advanced treatments, and personalized consultations.
</p>
</div>

</section>

<section id="contact">
<h2 class="section-title">Contact Us</h2>

<div class="contact">
<p>📍 Your Address Here</p>
<p>📞 +94 XX XXX XXXX</p>
<p>📧 info@newlinkcosmetic.com</p>
<p>🕒 Mon - Sat : 9.00 AM - 6.00 PM</p>
</div>

</section>

<footer>
<p>© 2026 Newlink Cosmetic Center. All Rights Reserved.</p>
</footer>

</body>
</html>
