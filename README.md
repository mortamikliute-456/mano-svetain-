<!DOCTYPE html>
<html lang="lt">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Mados pasaulis | 10/10 projektas</title>

<link href="https://fonts.googleapis.com/css2?family=Noto+Sans:wght@300;400;600;700&display=swap" rel="stylesheet">

<style>
*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:'Noto Sans',sans-serif;
scroll-behavior:smooth;
}

body{
background:#f7f3f6;
color:#1e1e1e;
line-height:1.6;
}

/* NAV */
nav{
position:fixed;
top:0;
left:0;
width:100%;
display:flex;
justify-content:space-between;
align-items:center;
padding:15px 40px;
background:rgba(0,0,0,0.5);
backdrop-filter:blur(10px);
z-index:999;
}

nav a{
color:white;
text-decoration:none;
margin:0 10px;
font-size:14px;
}

nav a:hover{
color:#ff4d88;
}

.logo{
color:white;
font-weight:700;
}

/* HERO */
header{
height:100vh;
background:
linear-gradient(rgba(0,0,0,0.55),rgba(0,0,0,0.55)),
url('https://images.unsplash.com/photo-1520975916090-3105956dac38?auto=format&fit=crop&w=1600&q=80') center/cover;
display:flex;
align-items:center;
justify-content:center;
text-align:center;
padding:20px;
}

.hero h1{
font-size:70px;
color:white;
animation:fade 1.2s ease;
}

.hero p{
color:white;
max-width:700px;
margin:auto;
margin-top:10px;
opacity:0.9;
}

@keyframes fade{
from{opacity:0;transform:translateY(20px);}
to{opacity:1;transform:translateY(0);}
}

/* SECTIONS */
section{
padding:100px 10%;
opacity:0;
transform:translateY(40px);
transition:1s;
}

section.show{
opacity:1;
transform:translateY(0);
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
}

/* INSTAGRAM STYLE GALERIJA */
.insta{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(200px,1fr));
gap:10px;
}

.insta img{
height:220px;
object-fit:cover;
border-radius:12px;
transition:0.3s;
}

.insta img:hover{
transform:scale(1.05);
}

/* QUIZ */
.quiz{
background:white;
padding:20px;
border-radius:15px;
}

button{
padding:10px 15px;
border:none;
background:#c2185b;
color:white;
border-radius:10px;
cursor:pointer;
margin-top:10px;
}

button:hover{
background:#880e4f;
}

/* FOOTER */
footer{
background:#111;
color:white;
padding:40px;
text-align:center;
}

/* SCORE */
.score{
font-size:20px;
font-weight:700;
color:#c2185b;
}

</style>
</head>

<body>

<nav>
<div class="logo">Mados pasaulis</div>
<div>
<a href="#apie">Apie</a>
<a href="#istorija">Istorija</a>
<a href="#galerija">Galerija</a>
<a href="#quiz">Quiz</a>
<a href="#kontaktai">Kontaktai</a>
</div>
</nav>

<header>
<div class="hero">
<h1>Mados pasaulis</h1>
<p>Mada – tai istorija, emocija ir saviraiška. Šioje svetainėje atrasi stilių, žaidimus, istoriją ir testus.</p>
</div>
</header>

<!-- APIE -->
<section id="apie">
<h2 class="title">Apie madą</h2>
<div class="grid">
<div class="card">Mada yra būdas išreikšti save be žodžių.</div>
<div class="card">Ji keičiasi kartu su kultūra ir technologijomis.</div>
<div class="card">Kiekvienas žmogus turi savo unikalų stilių.</div>
<div class="card">Socialiniai tinklai formuoja naujas tendencijas.</div>
</div>
</section>

<!-- ISTORIJA -->
<section id="istorija">
<h2 class="title">Mados istorija</h2>
<div class="grid">

<div class="card">
<img src="https://images.unsplash.com/photo-1487412720507-e7ab37603c6f">
<h3>1920-ieji</h3>
<p>Elegancijos era – ilgos suknelės ir klasikinis stilius.</p>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1512436991641-6745cdb1723f">
<h3>2000-ieji</h3>
<p>Ryškios spalvos, Y2K mada ir žemi džinsai.</p>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1496747611176-843222e1e57c">
<h3>2026</h3>
<p>Minimalizmas, oversize drabužiai ir komfortas.</p>
</div>

</div>
</section>

<!-- GALERIJA -->
<section id="galerija">
<h2 class="title">Instagram stiliaus galerija</h2>
<div class="insta">

<img src="https://images.unsplash.com/photo-1529139574466-a303027c1d8b">
<img src="https://images.unsplash.com/photo-1515886657613-9f3515b0c78f">
<img src="https://images.unsplash.com/photo-1495385794356-15371f348c31">
<img src="https://images.unsplash.com/photo-1509631179647-0177331693ae">
<img src="https://images.unsplash.com/photo-1483985988355-763728e1935b">
<img src="https://images.unsplash.com/photo-1524504388940-b1c1722653e1">

</div>
</section>

<!-- QUIZ -->
<section id="quiz">
<h2 class="title">Mados testas</h2>

<div class="quiz">
<p>Kokia spalva laikoma elegantiškiausia?</p>

<button onclick="check(1)">Juoda</button>
<button onclick="check(2)">Žalia</button>
<button onclick="check(3)">Geltona</button>

<p id="result" class="score"></p>
<p id="points"></p>
</div>
</section>

<!-- KONTAKTAI -->
<section id="kontaktai">
<h2 class="title">Kontaktai</h2>
<div class="card">
<p>📧 mada@gmail.com</p>
<p>📍 Lietuva</p>
<p>📷 Instagram: mados_pasaulis</p>
</div>
</section>

<footer>
<p>© 2026 Mados pasaulis | 10/10 projektas</p>
</footer>

<script>

// scroll animation
const sections=document.querySelectorAll("section");

window.addEventListener("scroll",()=>{
sections.forEach(sec=>{
let top=window.scrollY;
let offset=sec.offsetTop-500;
if(top>offset){
sec.classList.add("show");
}
});
});

let score=0;

function check(a){
if(a===1){
document.getElementById("result").innerText="Teisinga! 🎉";
score++;
}else{
document.getElementById("result").innerText="Neteisinga 😢";
}
document.getElementById("points").innerText="Taškai: "+score;
}

</script>

</body>
</html>
