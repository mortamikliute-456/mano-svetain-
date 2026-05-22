<!DOCTYPE html>

<html lang="lt">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Mados pasaulis | Premium svetainė</title>

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
background:#f7f3f6;
color:#1f1f1f;
line-height:1.6;
transition:0.4s;
}

body.dark{
background:#0f0f12;
color:#eaeaea;
}

/* HEADER SU AIŠKIU PAVEIKSLĖLIU */
header{
height:100vh;
background:
linear-gradient(rgba(0,0,0,0.55),rgba(0,0,0,0.55)),
url('https://images.unsplash.com/photo-1520975916090-3105956dac38?auto=format&fit=crop&w=1600&q=80') center/cover;
position:relative;
}

.overlay{
height:100%;
display:flex;
flex-direction:column;
}

nav{
display:flex;
justify-content:space-between;
align-items:center;
padding:20px 50px;
flex-wrap:wrap;
}

.logo{
color:#fff;
font-size:30px;
font-weight:700;
}

nav ul{
display:flex;
list-style:none;
gap:18px;
flex-wrap:wrap;
}

nav a{
color:white;
text-decoration:none;
transition:0.3s;
font-weight:500;
}

nav a:hover{
color:#ff4d88;
}

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
max-width:750px;
font-size:20px;
margin-top:10px;
opacity:0.95;
}

section{
padding:90px 10%;
}

.title{
font-size:42px;
margin-bottom:35px;
color:#c2185b;
}

.grid{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(260px,1fr));
gap:20px;
}

.card{
background:white;
padding:20px;
border-radius:16px;
box-shadow:0 8px 25px rgba(0,0,0,0.08);
transition:0.3s;
}

body.dark .card{
background:#1a1a1a;
}

.card:hover{
transform:translateY(-8px);
}

img{
width:100%;
border-radius:14px;
object-fit:cover;
}

button{
padding:10px 18px;
border:none;
border-radius:10px;
cursor:pointer;
background:#c2185b;
color:white;
transition:0.3s;
margin-top:10px;
}

button:hover{
background:#880e4f;
}

#darkBtn{
position:fixed;
top:15px;
right:15px;
z-index:999;
}

footer{
background:#111;
color:white;
padding:40px;
text-align:left;
}

.small{
opacity:0.7;
font-size:14px;
}

</style>

</head>

<body>

<button id="darkBtn">🌙</button>

<header>
<div class="overlay">
<nav>
<div class="logo">Mados pasaulis</div>
<ul>
<li><a href="#apie">Apie</a></li>
<li><a href="#istorija">Istorija</a></li>
<li><a href="#tendencijos">Tendencijos</a></li>
<li><a href="#galerija">Galerija</a></li>
<li><a href="#zaidimai">Žaidimai</a></li>
<li><a href="#faktai">Faktai</a></li>
<li><a href="#kontaktai">Kontaktai</a></li>
</ul>
</nav>

<div class="hero">
<h1>Mados pasaulis</h1>
<p>Stilius, istorija, kūryba ir šiuolaikinės tendencijos vienoje modernioje svetainėje.</p>
</div>
</div>
</header>

<section id="apie">
<h2 class="title">Apie madą</h2>
<div class="grid">
<div class="card">Mada yra saviraiškos forma, kuri nuolat keičiasi.</div>
<div class="card">Kiekvienas žmogus turi savo unikalų stilių.</div>
<div class="card">Socialiniai tinklai stipriai veikia mados pasaulį.</div>
</div>
</section>

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
<p>Y2K stilius su ryškiomis spalvomis.</p>
</div>
<div class="card">
<img src="https://images.unsplash.com/photo-1496747611176-843222e1e57c">
<h3>2026</h3>
<p>Minimalizmas ir modernus komfortas.</p>
</div>
</div>
</section>

<section id="tendencijos">
<h2 class="title">Tendencijos</h2>
<div class="grid">
<div class="card">🖤 Juoda + smėlio spalvos</div>
<div class="card">👟 Sportinis stilius</div>
<div class="card">👜 Mažos rankinės</div>
<div class="card">✨ Minimalizmas</div>
</div>
</section>

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

<section id="zaidimai">
<h2 class="title">Žaidimai</h2>
<div class="grid">
<div class="card">
<p>Elegantiškiausia spalva?</p>
<button onclick="q1()">Atsakymas</button>
<p id="r1"></p>
</div>
<div class="card">
<p>Stiliaus generatorius</p>
<button onclick="q2()">Gauti</button>
<p id="r2"></p>
</div>
<div class="card">
<p>Outfit kūrimas</p>
<button onclick="q3()">Kurti</button>
<p id="r3"></p>
</div>
</div>
</section>

<section id="faktai">
<h2 class="title">Įdomūs faktai</h2>
<div class="grid">
<div class="card">Mada kartojasi kas 20–30 metų</div>
<div class="card">Juoda = elegancija</div>
<div class="card">Aksesuarai keičia įvaizdį</div>
<div class="card">Social media kuria trendus</div>
</div>
</section>

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
<p class="small">Sukurta su HTML + CSS + JavaScript</p>
</footer>

<script>
function q1(){document.getElementById("r1").innerText="Juoda";}
function q2(){let s=["Old Money","Streetwear","Y2K","Minimal"];document.getElementById("r2").innerText=s[Math.floor(Math.random()*s.length)];}
function q3(){document.getElementById("r3").innerText="Džinsai + švarkas + sportbačiai";}

document.getElementById("darkBtn").onclick=()=>{
document.body.classList.toggle("dark");}
</script>

</body>
</html>
