<!DOCTYPE html>
<html lang="es">

<head>

<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Club Sportivo Trinidense</title>

<link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700;900&display=swap" rel="stylesheet">

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
}

body{

font-family:'Montserrat', sans-serif;

background:#04152d;

color:white;

overflow-x:hidden;

}

/* PORTADA */

.hero{

height:100vh;

background:

linear-gradient(
rgba(0,0,0,0.65),
rgba(0,0,0,0.75)
),

url('https://images.unsplash.com/photo-1508098682722-e99c643e7485?q=80&w=1800');

background-size:cover;
background-position:center;

display:flex;
justify-content:center;
align-items:center;

text-align:center;

padding:20px;

}

.hero-contenido{

max-width:1000px;

animation:aparecer 2s ease;

}

.logo{

width:220px;

margin-bottom:35px;

filter:drop-shadow(0 0 25px rgba(255,215,0,0.7));

}

.hero h1{

font-size:110px;

font-weight:900;

line-height:0.95;

text-transform:uppercase;

background:linear-gradient(
90deg,
#0057ff,
#ffd700
);

-webkit-background-clip:text;
-webkit-text-fill-color:transparent;

letter-spacing:5px;

text-shadow:
0 0 30px rgba(255,215,0,0.25);

margin-bottom:30px;

}

.hero p{

font-size:28px;

line-height:1.6;

max-width:850px;

margin:auto;

}

/* MENU */

nav{

background:#001733;

padding:22px;

position:sticky;
top:0;

z-index:999;

text-align:center;

box-shadow:0 0 15px rgba(0,0,0,0.4);

}

nav a{

color:#ffd700;

text-decoration:none;

margin:20px;

font-size:19px;

font-weight:700;

transition:0.3s;

}

nav a:hover{

color:white;

}

/* SECCIONES */

section{

padding:120px 10%;

}

h2{

font-size:60px;

margin-bottom:40px;

color:#ffd700;

text-align:center;

}

.card{

background:#0b2244;

padding:45px;

border-radius:25px;

line-height:1.9;

font-size:20px;

box-shadow:0 0 25px rgba(0,0,0,0.3);

}

/* GALERIA */

.galeria{

display:flex;

flex-wrap:wrap;

gap:25px;

justify-content:center;

margin-top:40px;

}

.galeria img{

width:350px;

height:230px;

object-fit:cover;

border-radius:25px;

transition:0.4s;

box-shadow:0 0 20px rgba(0,0,0,0.4);

}

.galeria img:hover{

transform:scale(1.05);

}

/* FOOTER */

footer{

background:#001226;

padding:40px;

text-align:center;

font-size:18px;

color:#aaa;

}

/* ANIMACION */

@keyframes aparecer{

from{

opacity:0;
transform:translateY(40px);

}

to{

opacity:1;
transform:translateY(0);

}

}

/* CELULAR */

@media(max-width:768px){

.hero h1{

font-size:55px;

}

.hero p{

font-size:18px;

}

.logo{

width:140px;

}

nav a{

display:block;
margin:12px 0;

}

h2{

font-size:38px;

}

}

</style>

</head>

<body>

<!-- PORTADA -->

<header class="hero">

<div class="hero-contenido">

<img
src="https://upload.wikimedia.org/wikipedia/en/5/5f/Sportivo_Trinidense_logo.png"
class="logo">

<h1>

Club Sportivo
Trinidense

</h1>

<p>

Pasión, identidad y orgullo del barrio Santísima Trinidad.
Una institución histórica del fútbol paraguayo que representa
la fuerza, tradición y sentimiento de su gente.

</p>

</div>

</header>

<!-- MENU -->

<nav>

<a href="#historia">Historia</a>

<a href="#galeria">Galería</a>

<a href="#barrio">Barrio</a>

<a href="#cancha">Día de cancha</a>

</nav>

<!-- HISTORIA -->

<section id="historia">

<h2>Historia del Club</h2>

<div class="card">

El Club Sportivo Trinidense es una de las instituciones
más representativas del barrio Santísima Trinidad de Asunción.

A lo largo de los años, el club construyó una identidad basada
en la pasión futbolera, el esfuerzo y el compromiso de su hinchada,
convirtiéndose en un símbolo deportivo y social para generaciones
de seguidores.

</div>

</section>

<!-- GALERIA -->

<section id="galeria">

<h2>Galería Trinidense</h2>

<div class="galeria">

<img src="https://images.unsplash.com/photo-1574629810360-7efbbe195018?q=80&w=1200">

<img src="https://images.unsplash.com/photo-1517927033932-b3d18e61fb3a?q=80&w=1200">

<img src="https://images.unsplash.com/photo-1508098682722-e99c643e7485?q=80&w=1200">

</div>

</section>

<!-- BARRIO -->

<section id="barrio">

<h2>Santísima Trinidad</h2>

<div class="card">

El barrio Santísima Trinidad representa una parte fundamental
de la identidad del club. Sus calles, su gente y el ambiente
futbolero convierten cada partido en una verdadera fiesta deportiva.

</div>

</section>

<!-- DIA DE CANCHA -->

<section id="cancha">

<h2>Día de Cancha</h2>

<div class="card">

Cada jornada deportiva transforma el estadio y el barrio
en un punto de encuentro para miles de hinchas que viven
el fútbol con intensidad, emoción y orgullo azul y oro.

</div>

</section>

<footer>

Club Sportivo Trinidense © 2026

</footer>

</body>
</html>
