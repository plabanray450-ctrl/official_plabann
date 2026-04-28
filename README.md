# Official_plabann
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Plaban | Cinematic Editor</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;600&display=swap" rel="stylesheet">

<style>
*{margin:0;padding:0;box-sizing:border-box;font-family:'Poppins',sans-serif;}
body{background:#0f0f0f;color:white;}

/* HEADER */
header{
display:flex;
justify-content:space-between;
padding:20px 40px;
position:fixed;
width:100%;
background:rgba(0,0,0,0.7);
backdrop-filter:blur(10px);
z-index:1000;
}
nav a{margin-left:20px;color:white;text-decoration:none;}

/* HERO */
.hero{
height:100vh;
background:url('https://images.unsplash.com/photo-1492724441997-5dc865305da7') center/cover no-repeat;
display:flex;
align-items:center;
justify-content:center;
text-align:center;
}
.hero::after{
content:"";
position:absolute;
width:100%;
height:100%;
background:rgba(0,0,0,0.6);
top:0;left:0;
}
.hero-content{
position:relative;
z-index:1;
}
.hero h1{font-size:50px;}
.hero button{
margin-top:20px;
padding:12px 30px;
border:none;
background:#6c63ff;
color:white;
border-radius:30px;
cursor:pointer;
}

/* SERVICES */
.services{text-align:center;padding:80px 20px;}
.cards{display:flex;justify-content:center;flex-wrap:wrap;}
.card{
background:#1c1c1c;
margin:15px;
padding:30px;
border-radius:15px;
width:220px;
transition:.3s;
}
.card:hover{transform:translateY(-10px);}

/* PORTFOLIO */
.portfolio{text-align:center;padding:80px 20px;}
.gallery{display:flex;flex-wrap:wrap;justify-content:center;}
.video{
margin:10px;
}

/* CONTACT */
.contact{text-align:center;padding:80px 20px;}

/* WHATSAPP */
.whatsapp{
position:fixed;
bottom:20px;
right:20px;
background:#25D366;
padding:15px;
border-radius:50%;
text-decoration:none;
font-size:20px;
}

/* FOOTER */
footer{text-align:center;padding:20px;background:black;}

/* MOBILE */
@media(max-width:768px){
.hero h1{font-size:30px;}
header{flex-direction:column;text-align:center;}
}
</style>
</head>

<body>

<header>
<h2>Plaban</h2>
<nav>
<a href="#services">Services</a>
<a href="#portfolio">Work</a>
<a href="#contact">Contact</a>
</nav>
</header>

<!-- HERO -->
<section class="hero">
<div class="hero-content">
<h1>Cinematic Video Editor</h1>
<p>I create stunning cinematic edits for brands & creators</p>
<a href="#contact"><button>Hire Me</button></a>
</div>
</section>

<!-- SERVICES -->
<section id="services" class="services">
<h2>My Services</h2>
<div class="cards">
<div class="card">🎥 Cinematic Editing</div>
<div class="card">📸 Photography</div>
<div class="card">🎬 Cinematic Shooting</div>
<div class="card">🎞️ Color Grading</div>
</div>
</section>

<!-- PORTFOLIO (YouTube Video Embed) -->
<section id="portfolio" class="portfolio">
<h2>My Work</h2>

<div class="gallery">

<div class="video">
<iframe width="300" height="200" src="https://www.youtube.com/embed/VIDEO_ID" frameborder="0" allowfullscreen></iframe>
</div>

<div class="video">
<iframe width="300" height="200" src="https://www.youtube.com/embed/VIDEO_ID" frameborder="0" allowfullscreen></iframe>
</div>

</div>

<p>👉 Replace VIDEO_ID with your YouTube video ID</p>

</section>

<!-- CONTACT -->
<section id="contact" class="contact">
<h2>Contact Me</h2>
<p>📞 9332160383</p>
<p>📷 <a href="https://instagram.com/6x_alive" target="_blank" style="color:#6c63ff">@6x_alive</a></p>
</section>

<!-- WHATSAPP -->
<a href="https://wa.me/919332160383" class="whatsapp">💬</a>

<footer>
<p>© 2026 Plaban | Cinematic Editor</p>
</footer>

</body>
</html>
