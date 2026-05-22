<!DOCTYPE html>
<html lang="lt">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Mados pasaulis | Premium</title>

<link href="https://fonts.googleapis.com/css2?family=Noto+Sans:wght@300;400;600;700&display=swap" rel="stylesheet">

<style>
*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:'Noto Sans','Segoe UI',Tahoma,sans-serif;
scroll-behavior:smooth;
}

body{
background:#f6f1f4;
color:#1f1f1f;
line-height:1.6;
}

/* HEADER */
header{
height:100vh;
background:
linear-gradient(rgba(0,0,0,0.55),rgba(0,0,0,0.55)),
url('https://images.unsplash.com/photo-1520975916090-3105956dac38?auto=format&fit=crop&w=1600&q=80') center/cover;
display:flex;
flex-direction:column;
}

/* NAV */
nav{
display:flex;
justify-content:space-between;
align-items:center;
padding:20px 50px;
flex-wrap:wrap;
}

nav ul{
display:flex;
gap:15px;
list-style:none;
flex-wrap:wrap;
}

nav a{
color:white;
text-decoration:none;
}

nav a:hover{
color:#ff4d88;
}

.logo{
color:white;
font-size:26px;
font-weight:700;
}

/* HERO */
.hero{
flex:1;
display:flex;
flex-direction:column;
justify-content:center;
padding:60px;
color:white;
}

.hero h1{
font-size:70px;
}

.hero p{
max-width:700px;
font-size:20px;
margin-top:10px;
}

/* SECTIONS */
section{
padding:90px 10%;
}

.title{
font-size:40px;
margin-bottom:30px;
color:#c2185b;
}

/* GRID */
.grid{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:20px;
}

.card{
background:white;
padding:18px;
border-radius:15px;
box-shadow:0 10px 25px rgba(0,0,0,0.08);
transition:0.3s;
}

.card:hover{
transform:translateY(-8px);
}

img{
width:100%;
border-radius:12px;
object-fit:cover;
}

/* BUTTON */
button{
margin-top:10px;
padding:10px 16px;
border:none;
border-radius:10px;
background:#c2185b;
color:white;
cursor:pointer;
}

button:hover{
background:#880e4f;
}

/* FOOTER */
footer{
background:#111;
color:white;
padding:40px;
}

</style>
</head>

<body>

<header>

<nav>
<div class="logo">Mados pasaulis</div>
<ul>
<li><a href="#apie">Apie</a></li>
<li><a href="#istorija">Istorija</a></li>
<li><a href="#galerija">Galerija</a></li>
<li><a href="#zaidimai">Žaidimai</a></li>
<li><a href="#kontaktai">Kontaktai</a></li>
</ul>
</nav>

<div class="hero">
<h1>Mados pasaulis</h1>
<p>Mada, istorija, stilius ir kūryba vienoje vietoje.</p>
</div>

</header>

<!-- APIE -->
<section id="apie">
<h2 class="title">Apie madą</h2>
<div class="grid">
<div class="card">Mada yra saviraiškos forma.</div>
<div class="card">Ji nuolat keičiasi ir grįžta.</div>
<div class="card">Kiekvienas žmogus turi savo stilių.</div>
</div>
</section>

<!-- ISTORIJA -->
<section id="istorija">
<h2 class="title">Mados istorija</h2>
<div class="grid">

<div class="card">
<img src="https://images.unsplash.com/photo-1487412720507-e7ab37603c6f">
<h3>1920-ieji</h3>
<p>Elegancijos ir klasikos era.</p>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1512436991641-6745cdb1723f">
<h3>2000-ieji</h3>
<p>Ryškios spalvos ir Y2K stilius.</p>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1496747611176-843222e1e57c">
<h3>2026</h3>
<p>Minimalizmas ir modernus stilius.</p>
</div>

</div>
</section>

<!-- GALERIJA -->
<section id="galerija">
<h2 class="title">Galerija</h2>
<div class="grid">

<img src="https://images.unsplash.com/photo-1529139574466-a303027c1d8b">
<img src="https://images.unsplash.com/photo-1515886657613-9f3515b0c78f">
<img src="https://images.unsplash.com/photo-1495385794356-15371f348c31">
<img src="https://images.unsplash.com/photo-1509631179647-0177331693ae">
<img src="https://images.unsplash.com/photo-1483985988355-763728e1935b">
<img src="https://images.unsplash.com/photo-1512436991641-6745cdb1723f">
<img src="https://images.unsplash.com/photo-1496747611176-843222e1e57c">
<img src="https://images.unsplash.com/photo-1524504388940-b1c1722653e1">

</div>
</section>

<!-- ŽAIDIMAI -->
<section id="zaidimai">
<h2 class="title">Žaidimai</h2>
<div class="grid">

<div class="card">
<p>Kokia spalva elegantiška?</p>
<button onclick="a1()">Atsakymas</button>
<p id="r1"></p>
</div>

<div class="card">
<p>Stiliaus generatorius</p>
<button onclick="a2()">Generuoti</button>
<p id="r2"></p>
</div>

<div class="card">
<p>Outfit idėja</p>
<button onclick="a3()">Kurti</button>
<p id="r3"></p>
</div>

</div>
</section>

<!-- KONTAKTAI -->
<section id="kontaktai">
<h2 class="title">Kontaktai</h2>
<div class="card">
<p>📧 mada@gmail.com</p>
<p>📍 Lietuva</p>
<p>📷 Instagram: mados_pasaulis</p>
<p>🗺 Google Maps</p>
</div>
</section>

<footer>
<p>© 2026 Mados pasaulis</p>
</footer>

<script>

function a1(){
document.getElementById("r1").innerText="Juoda spalva";
}

function a2(){
let s=["Old Money","Streetwear","Y2K","Minimal"];
document.getElementById("r2").innerText=s[Math.floor(Math.random()*s.length)];
}

function a3(){
document.getElementById("r3").innerText="Džinsai + švarkas + sportbačiai";
}

</script>

</body>
</html>
