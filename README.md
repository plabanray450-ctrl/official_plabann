# Official_plabann
<!DOCTYPE html>

<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>6x Alive Studio</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;600&display=swap" rel="stylesheet">

<style>
*{margin:0;padding:0;box-sizing:border-box;font-family:'Poppins',sans-serif;scroll-behavior:smooth;}
body{background:#f7f7f7;color:#111}

/* HEADER */
header{
position:fixed;width:100%;top:0;
display:flex;justify-content:space-between;
padding:20px 40px;
background:white;
box-shadow:0 5px 20px rgba(0,0,0,0.05);
z-index:1000;
}
nav a{margin-left:20px;color:#ff6a00;text-decoration:none}

/* HERO */
.hero{
height:100vh;
display:flex;align-items:center;
background:linear-gradient(135deg,#ffffff,#fff3eb);
}

.hero-flex{
display:flex;
align-items:center;
justify-content:space-between;
gap:40px;
padding:50px;
width:100%;
}

.hero-text h1{font-size:55px}
.hero-text span{color:#ff6a00}
.hero-text p{color:#555;margin-top:10px}

.hero-img img{
width:100%;
max-width:450px;
border-radius:20px;
box-shadow:0 20px 40px rgba(0,0,0,0.1);
}

/* BUTTON */
.btn{
display:inline-block;
margin-top:20px;
padding:12px 30px;
background:#ff6a00;
color:white;
border-radius:30px;
text-decoration:none;
transition:.3s;
}
.btn:hover{background:#ff8c42}

/* SECTION */
.section{padding:100px 20px;text-align:center}

/* SERVICES */
.cards{
display:grid;
grid-template-columns:repeat(3,1fr);
gap:20px;
margin-top:40px;
}

.card{
background:white;
padding:25px;
border-radius:15px;
box-shadow:0 10px 30px rgba(0,0,0,0.05);
transition:.3s;
position:relative;
overflow:hidden;
}

.card:hover{
transform:translateY(-10px);
}

.desc{
opacity:0;
transform:translateY(20px);
font-size:14px;
color:#666;
margin-top:10px;
transition:.4s;
}

.card:hover .desc{
opacity:1;
transform:translateY(0);
}

/* PRICING */
.pricing{
display:grid;
grid-template-columns:repeat(5,1fr);
gap:20px;
margin-top:50px;
}

.price-card{
background:white;
padding:25px;
border-radius:20px;
box-shadow:0 10px 30px rgba(0,0,0,0.05);
transition:.4s;
position:relative;
}

.price-card:hover{
transform:translateY(-15px) scale(1.05);
box-shadow:0 20px 50px rgba(255,106,0,0.2);
}

.popular{
border:2px solid #ff6a00;
}
.popular::before{
content:"MOST POPULAR";
position:absolute;
top:10px;left:50%;
transform:translateX(-50%);
background:#ff6a00;
color:white;
padding:5px 10px;
border-radius:20px;
font-size:12px;
}

.price{color:#ff6a00;font-size:22px;margin-top:10px}

/* CONTACT */
.contact-box{
background:white;
padding:30px;
border-radius:15px;
box-shadow:0 10px 30px rgba(0,0,0,0.05);
display:flex;
justify-content:space-around;
margin-top:30px;
}

/* WHATSAPP */
.whatsapp{
position:fixed;
bottom:20px;right:20px;
background:#25D366;
color:white;
padding:15px;
border-radius:50%;
}

/* MOBILE */
@media(max-width:900px){
.hero-flex{flex-direction:column}
.cards{grid-template-columns:1fr}
.pricing{grid-template-columns:1fr}
.contact-box{flex-direction:column;gap:20px}
.hero-text h1{font-size:30px}
}
</style>

</head>

<body>

<header>
<h2>6x Alive Studio</h2>
<nav>
<a href="#home">Home</a>
<a href="#services">Services</a>
<a href="#pricing">Pricing</a>
<a href="#contact">Contact</a>
</nav>
</header>

<!-- HERO -->

<section id="home" class="hero">
<div class="hero-flex">

<div class="hero-text">
<h1>I Edit. <span>You Shine.</span></h1>
<p>I create cinematic videos that grow your brand</p>
<a href="#contact" class="btn">Hire Me</a>
</div>

<div class="hero-img">
<img src="editor.jpg" alt="editor">
</div>

</div>
</section>

<!-- SERVICES -->

<section id="services" class="section">
<h2>My Services</h2>

<div class="cards">

<div class="card">🎥 Video Editing
<p class="desc">Cinematic edits for YouTube, Ads & brands.</p>
</div>

<div class="card">📱 Reels Editing
<p class="desc">Short viral reels for Instagram growth.</p>
</div>

<div class="card">🎬 Shooting
<p class="desc">Professional cinematic shooting.</p>
</div>

<div class="card">📸 Photography
<p class="desc">Creative and aesthetic photography.</p>
</div>

<div class="card">🎞️ Color Grading
<p class="desc">Film-style color tones.</p>
</div>

</div>

</section>

<!-- PRICING -->

<section id="pricing" class="section">
<h2>Simple Pricing</h2>

<div class="pricing">

<div class="price-card">
<h3>Video Editing</h3>
<p>Starting From</p>
<div class="price">₹999</div>
</div>

<div class="price-card">
<h3>Reels Editing</h3>
<p>Starting From</p>
<div class="price">₹199</div>
</div>

<div class="price-card popular">
<h3>Shooting</h3>
<p>Starting From</p>
<div class="price">₹1499+</div>
</div>

<div class="price-card">
<h3>Photography</h3>
<p>Starting From</p>
<div class="price">₹799-1499</div>
</div>

<div class="price-card">
<h3>Color Grading</h3>
<p>Starting From</p>
<div class="price">₹499</div>
</div>

</div>

<a href="https://wa.me/919332160383" class="btn">Hire Me Now</a>

</section>

<!-- PORTFOLIO -->

<section class="section">
<h2>Portfolio</h2>
<a href="https://www.youtube.com/@PlabanRay-p8f3d" class="btn">YouTube</a>
<a href="https://instagram.com/6x_alive" class="btn">Instagram</a>
</section>

<!-- CONTACT -->

<section id="contact" class="section">
<h2>Contact Me</h2>

<div class="contact-box">
<div>📞 9332160383</div>
<div>📷 @6x_alive</div>
<div>💬 WhatsApp</div>
</div>

</section>

<a href="https://wa.me/919332160383" class="whatsapp">💬</a>

</body>
</html>
