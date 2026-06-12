<3
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Cyber Pink Profile</title>

<link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@400;600&display=swap" rel="stylesheet">

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
}

body{
font-family:'Orbitron',sans-serif;
background:linear-gradient(135deg,#070018,#21003d,#4b0082);
background-attachment:fixed;
min-height:100vh;
padding:30px;
color:white;
}

.container{
max-width:1300px;
margin:auto;
background:rgba(255,255,255,0.05);
backdrop-filter:blur(12px);
border:2px solid rgba(255,0,255,0.3);
border-radius:30px;
overflow:hidden;
box-shadow:0 0 50px #ff00ff55;
}

.topbar{
height:90px;
background:linear-gradient(90deg,#ff00aa,#7b2dff);
display:flex;
justify-content:center;
align-items:center;
font-size:2rem;
font-weight:bold;
letter-spacing:3px;
text-shadow:0 0 15px white;
}

.menu{
display:flex;
justify-content:center;
gap:20px;
padding:20px;
background:#120020;
}

.menu a{
text-decoration:none;
color:white;
padding:12px 25px;
border-radius:30px;
background:linear-gradient(90deg,#ff00aa,#7b2dff);
transition:.3s;
}

.menu a:hover{
transform:translateY(-3px);
box-shadow:0 0 20px #ff00ff;
}

.hero{
height:350px;
background:url('anime2.png') center center;
background-size:cover;
position:relative;
}

.hero::before{
content:'';
position:absolute;
inset:0;
background:rgba(0,0,0,.4);
}

.hero-text{
position:absolute;
left:50%;
top:50%;
transform:translate(-50%,-50%);
text-align:center;
z-index:2;
}

.hero-text h1{
font-size:4rem;
text-shadow:0 0 25px #ff00ff;
}

.hero-text p{
margin-top:10px;
font-size:1.2rem;
}

.content{
padding:30px;
display:grid;
grid-template-columns:1fr 1fr;
gap:25px;
}

.card{
background:rgba(255,255,255,.05);
border:1px solid rgba(255,0,255,.3);
border-radius:20px;
padding:20px;
box-shadow:0 0 15px rgba(255,0,255,.3);
}

.card h2{
margin-bottom:15px;
color:#ff7cff;
}

.profile-img{
width:100%;
height:400px;
object-fit:cover;
border-radius:15px;
border:2px solid #ff4dff;
}

.gallery{
display:grid;
grid-template-columns:1fr 1fr;
gap:15px;
margin-top:20px;
}

.gallery img{
width:100%;
height:250px;
object-fit:cover;
border-radius:15px;
border:2px solid #ff4dff;
transition:.4s;
}

.gallery img:hover{
transform:scale(1.04);
box-shadow:0 0 20px #ff00ff;
}

.car-section{
margin:30px;
}

.car-section img{
width:100%;
height:500px;
object-fit:cover;
border-radius:20px;
border:3px solid #ff00ff;
box-shadow:0 0 30px #ff00ff;
}

.skills{
display:flex;
flex-wrap:wrap;
gap:10px;
margin-top:15px;
}

.skill{
padding:10px 20px;
border-radius:20px;
background:linear-gradient(90deg,#ff00aa,#7b2dff);
}

.social{
display:flex;
justify-content:center;
gap:20px;
padding:30px;
}

.social a{
width:60px;
height:60px;
display:flex;
align-items:center;
justify-content:center;
border-radius:50%;
background:linear-gradient(90deg,#ff00aa,#7b2dff);
font-size:1.5rem;
text-decoration:none;
color:white;
}

.footer{
text-align:center;
padding:25px;
background:#0d0018;
}

@media(max-width:900px){

.content{
grid-template-columns:1fr;
}

.hero-text h1{
font-size:2.5rem;
}

}

</style>
</head>

<body>

<div class="container">

<div class="topbar">
CYBER PINK PROFILE
</div>

<div class="menu">
<a href="#">Home</a>
<a href="#">Sobre</a>
<a href="#">Projetos</a>
<a href="#">Contato</a>
</div>

<div class="hero">

<div class="hero-text">
<h1>DIEUDO</h1>
<p>Programação • Engenharia • Cyberpunk</p>
</div>

</div>

<div class="content">

<div class="card">

<h2>Sobre Mim</h2>

<img src="anime1.png" class="profile-img">

<br><br>

<p>
Bem-vindo ao meu espaço digital.
Sou estudante de Engenharia Ambiental,
apaixonado por tecnologia, programação,
inteligência artificial e design cyberpunk.
</p>

<div class="skills">

<div class="skill">Python</div>
<div class="skill">HTML</div>
<div class="skill">CSS</div>
<div class="skill">JavaScript</div>
<div class="skill">GitHub</div>

</div>

</div>

<div class="card">

<h2>Galeria</h2>

<div class="gallery">

<img src="anime1.png">
<img src="anime2.png">
<img src="anime2.png">
<img src="anime1.png">

</div>

</div>

</div>

<div class="car-section">

<h2 style="text-align:center;margin-bottom:20px;color:#ff7cff;">
Meu Carro dos Sonhos
</h2>

<img src="carro.png">

</div>

<div class="social">

<a href="#">📷</a>
<a href="#">🎮</a>
<a href="#">🎵</a>
<a href="#">💻</a>

</div>

<div class="footer">
© 2026 | CYBER PINK PROFILE
</div>

</div>

</body>
</html>
