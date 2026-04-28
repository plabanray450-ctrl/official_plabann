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
nav a{margin-left:20px;color:white;text-decoration:none;}

/* HERO */
.hero{
height:100vh;
display:flex;align-items:center;justify-content:center;
background:linear-gradient(135deg,#0f0f0f,#2b1d14);
text-align:center;
}
.hero h1{font-size:50px;}
.hero button{
margin-top:20px;padding:12px 30px;
border:none;border-radius:30px;
background:#8B5E3C;
color:white;cursor:pointer;
}

/* SECTION */
section{padding:100px 20px;text-align:center}

/* SERVICES */
.card{
background:rgba(255,255,255,0.05);
margin:15px;padding:25px;
border-radius:15px;
backdrop-filter:blur(10px);
cursor:pointer;
transition:.4s;
}
.card:hover{
transform:translateY(-10px);
box-shadow:0 0 20px #8B5E3C;
}

.desc{display:none;margin-top:10px;color:#ccc;}
.card.active .desc{display:block}

/* GRID */
.cards{display:flex;flex-wrap:wrap;justify-content:center}

/* PORTFOLIO BUTTONS */
.btn{
display:inline-block;
margin:10px;
padding:12px 25px;
background:#8B5E3C;
color:white;
border-radius:25px;
text-decoration:none;
transition:.3s;
}
.btn:hover{background:#a97449}

/* CONTACT */
.contact a{color:#a97449}

/* WHATSAPP */
.whatsapp{
position:fixed;
bottom:20px;right:20px;
background:#25D366;
padding:15px;
border-radius:50%;
text-decoration:none;
font-size:20px;
}

/* ANIMATION */
.fade{opacity:0;transform:translateY(40px);transition:1s;}
.show{opacity:1;transform:translateY(0);}

/* MOBILE */
@media(max-width:768px){
.hero h1{font-size:30px;}
header{flex-direction:column;text-align:center;}
}
</style>
</head>

<body>

<header>
<h2>6x Alive Studio</h2>
<nav>
<a href="#home">Home</a>
<a href="#services">Services</a>
<a href="#portfolio">Portfolio</a>
<a href="#contact">Contact</a>
</nav>
</header>

<!-- HOME -->
<section id="home" class="hero">
<div>
<h1>Cinematic Video Editor</h1>
<p>I create stunning cinematic edits for brands & creators</p>
<a href="#contact"><button>Hire Me</button></a>
</div>
</section>

<!-- SERVICES -->
<section id="services">
<h1>My Services</h1>

<div class="cards">

<div class="card fade">
🎬 Cinematic Shooting
<div class="desc">Professional cinematic shots with storytelling visuals.</div>
</div>

<div class="card fade">
🎥 Video Editing
<div class="desc">Smooth cuts, transitions and high-quality editing.</div>
</div>

<div class="card fade">
📱 Reels Editing
<div class="desc">Viral short edits optimized for Instagram.</div>
</div>

<div class="card fade">
📸 Photography
<div class="desc">Creative photography for brands & personal use.</div>
</div>

<div class="card fade">
🎞️ Color Grading
<div class="desc">Film-like cinematic color tones.</div>
</div>

</div>
</section>

<!-- PORTFOLIO -->
<section id="portfolio">
<h1>My Work</h1>

<p>Check out my content:</p>

<a href="https://www.youtube.com/@PlabanRay-p8f3d" target="_blank" class="btn">🎥 YouTube Channel</a>

<a href="https://instagram.com/6x_alive" target="_blank" class="btn">📷 Instagram Profile</a>

</section>

<!-- CONTACT -->
<section id="contact" class="contact">
<h1>Contact Me</h1>

<p>📞 9332160383</p>
<p>📷 <a href="https://instagram.com/6x_alive" target="_blank">@6x_alive</a></p>

</section>

<!-- WHATSAPP -->
<a href="https://wa.me/919332160383" class="whatsapp">💬</a>

<footer style="text-align:center;padding:20px;background:black;">
© 2026 6x Alive Studio | Plaban
</footer>

<script>
// CLICK EXPAND
document.querySelectorAll(".card").forEach(card=>{
card.addEventListener("click",()=>{
card.classList.toggle("active");
});
});

// SCROLL ANIMATION
const elements=document.querySelectorAll(".fade");
window.addEventListener("scroll",()=>{
elements.forEach(el=>{
if(el.getBoundingClientRect().top < window.innerHeight-100){
el.classList.add("show");
}
});
});
</script>

</body>
</html>
