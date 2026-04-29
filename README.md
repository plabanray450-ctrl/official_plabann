# Official_plabann
<!DOCTYPE html>

<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>6x Alive Studio | Plaban</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;600&display=swap" rel="stylesheet">

<style>
*{margin:0;padding:0;box-sizing:border-box;font-family:'Poppins',sans-serif;scroll-behavior:smooth;}
body{background:#0f0f0f;color:white}

/* HEADER */
header{
position:fixed;width:100%;top:0;
display:flex;justify-content:space-between;
padding:20px 40px;
background:rgba(0,0,0,0.6);
backdrop-filter:blur(10px);
z-index:1000;
}
nav a{margin-left:20px;color:#ff8533;text-decoration:none}

/* CONTAINER */
.container{max-width:1200px;margin:auto;padding:0 20px}

/* HERO */
.hero{
height:100vh;
display:flex;align-items:center;
background:linear-gradient(135deg,#0f0f0f,#2a1400);
}
.hero h1{font-size:55px}
.hero p{color:#ccc;margin-top:10px}

/* BUTTON */
.btn{
display:inline-block;
margin-top:20px;
padding:12px 30px;
background:#ff6b00;
color:white;
border-radius:30px;
text-decoration:none;
}

/* SECTION */
.section{padding:100px 0}

/* CARDS */
.cards{
display:grid;
grid-template-columns:repeat(3,1fr);
gap:20px;
margin-top:40px;
}
.card{
background:#1c1c1c;
padding:25px;
border-radius:12px;
cursor:pointer;
transition:.3s;
}
.card:hover{
transform:translateY(-10px);
box-shadow:0 0 20px #ff6b00;
}
.desc{display:none;color:#aaa;margin-top:10px}
.card.active .desc{display:block}

/* PRICING */
.pricing{
background:#1c1c1c;
padding:30px;
border-radius:15px;
margin-top:40px;
}
.price-item{
display:flex;
justify-content:space-between;
margin:15px 0;
border-bottom:1px solid #333;
padding-bottom:10px;
}

/* CTA */
.cta{
text-align:center;
padding:100px 0;
background:linear-gradient(135deg,#1a0d00,#000);
}

/* WHATSAPP */
.whatsapp{
position:fixed;
bottom:20px;right:20px;
background:#25D366;
padding:15px;
border-radius:50%;
text-decoration:none;
}

/* FOOTER */
footer{
text-align:center;
padding:20px;
background:black;
}

/* MOBILE */
@media(max-width:768px){
.cards{grid-template-columns:1fr}
.hero h1{font-size:32px}
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
<a href="#portfolio">Portfolio</a>
<a href="#contact">Contact</a>
</nav>
</header>

<!-- HERO -->

<section id="home" class="hero">
<div class="container">
<h1>Cinematic Video Editor</h1>
<p>I create high-quality cinematic edits for brands & creators</p>
<a href="#contact" class="btn">Hire Me</a>
</div>
</section>

<!-- SERVICES -->

<section id="services" class="section">
<div class="container">
<h2>My Services</h2>

<div class="cards">

<div class="card">🎥 Video Editing
<div class="desc">Cinematic edits with smooth transitions.</div>
</div>

<div class="card">📱 Reels Editing
<div class="desc">Viral short edits for Instagram.</div>
</div>

<div class="card">🎬 Shooting
<div class="desc">Professional cinematic shooting.</div>
</div>

<div class="card">📸 Photography
<div class="desc">Creative photography work.</div>
</div>

<div class="card">🎞️ Color Grading
<div class="desc">Film-style color tones.</div>
</div>

</div>

</div>
</section>

<!-- PRICING -->

<section id="pricing" class="section">
<div class="container">
<h2>Pricing</h2>

<div class="pricing">

<div class="price-item">
<span>Video Editing</span>
<span>Starting ₹999</span>
</div>

<div class="price-item">
<span>Reels Editing</span>
<span>₹199 / reel</span>
</div>

<div class="price-item">
<span>Shooting</span>
<span>₹1499+</span>
</div>

<div class="price-item">
<span>Photography</span>
<span>₹799 – ₹1499</span>
</div>

<div class="price-item">
<span>Color Grading</span>
<span>₹499</span>
</div>

<a href="https://wa.me/919332160383?text=Hi Plaban, I want your service" class="btn">Hire Now</a>

</div>

</div>
</section>

<!-- PORTFOLIO -->

<section id="portfolio" class="section">
<div class="container">
<h2>My Work</h2>

<a href="https://www.youtube.com/@PlabanRay-p8f3d" target="_blank" class="btn">🎥 YouTube</a> <a href="https://instagram.com/6x_alive" target="_blank" class="btn">📷 Instagram</a>

</div>
</section>

<!-- CONTACT -->

<section id="contact" class="section">
<div class="container">
<h2>Contact Me</h2>

<p>📞 9332160383</p>
<p>📷 <a href="https://instagram.com/6x_alive" style="color:#ff8533">@6x_alive</a></p>

<a href="https://wa.me/919332160383" class="btn">Message on WhatsApp</a>

</div>
</section>

<a href="https://wa.me/919332160383" class="whatsapp">💬</a>

<footer>
© 2026 6x Alive Studio | Plaban
</footer>

<script>
document.querySelectorAll(".card").forEach(card=>{
card.addEventListener("click",()=>{
card.classList.toggle("active");
});
});
</script>

</body>
</html>
