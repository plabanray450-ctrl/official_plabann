* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'Poppins', sans-serif;
}

body {
  background: #0f0f0f;
  color: white;
}

/* HEADER */
header {
  display: flex;
  justify-content: space-between;
  padding: 20px 50px;
  position: fixed;
  width: 100%;
  background: rgba(0,0,0,0.7);
  backdrop-filter: blur(10px);
}

nav a {
  margin-left: 20px;
  color: white;
  text-decoration: none;
}

/* HERO */
.hero {
  height: 100vh;
  background: url('https://images.unsplash.com/photo-1492724441997-5dc865305da7') no-repeat center/cover;
  position: relative;
}

.overlay {
  position: absolute;
  width: 100%;
  height: 100%;
  background: rgba(0,0,0,0.6);
}

.hero-content {
  position: relative;
  top: 50%;
  transform: translateY(-50%);
  text-align: center;
}

.hero h1 {
  font-size: 50px;
}

.hero button {
  margin-top: 20px;
  padding: 12px 30px;
  border: none;
  background: #6c63ff;
  color: white;
  border-radius: 30px;
  cursor: pointer;
}

/* SERVICES */
.services {
  padding: 80px 20px;
  text-align: center;
}

.cards {
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
}

.card {
  background: #1c1c1c;
  margin: 15px;
  padding: 30px;
  border-radius: 15px;
  width: 220px;
  transition: 0.3s;
}

.card:hover {
  transform: translateY(-10px);
}

/* PORTFOLIO */
.portfolio {
  padding: 80px 20px;
  text-align: center;
}

.gallery {
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
}

.item {
  background: #222;
  margin: 10px;
  padding: 50px;
  border-radius: 10px;
}

/* CONTACT */
.contact {
  padding: 80px 20px;
  text-align: center;
}

/* WHATSAPP */
.whatsapp {
  position: fixed;
  bottom: 20px;
  right: 20px;
  background: #25D366;
  padding: 15px;
  border-radius: 50%;
  font-size: 20px;
  text-decoration: none;
}

/* FOOTER */
footer {
  text-align: center;
  padding: 20px;
  background: black;
}

/* MOBILE */
@media (max-width: 768px) {
  .hero h1 {
    font-size: 30px;
  }

  header {
    flex-direction: column;
    text-align: center;
  }
}# official_plabann
