<!DOCTYPE html>
<html lang="pt-br">

<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Rainbow Vista</title>

<style>

@import url('https://fonts.googleapis.com/css2?family=Quicksand:wght@400;600;700&display=swap');

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:'Quicksand',sans-serif;
}

body{

background:linear-gradient(
-45deg,
#ff0000,
#ff8800,
#ffee00,
#00ff55,
#00c8ff,
#0066ff,
#7b00ff,
#ff0095);

background-size:600% 600%;

animation:rainbow 20s ease infinite;

height:100vh;

display:flex;
justify-content:center;
align-items:center;

overflow:hidden;

}

@keyframes rainbow{

0%{background-position:0% 50%;}
50%{background-position:100% 50%;}
100%{background-position:0% 50%;}

}

.window{

width:1050px;
height:650px;

background:rgba(255,255,255,.35);

backdrop-filter:blur(18px);

border-radius:20px;

border:2px solid rgba(255,255,255,.6);

box-shadow:

0 20px 60px rgba(0,0,0,.35),

inset 0 0 30px rgba(255,255,255,.3);

overflow:hidden;

}

.topbar{

height:60px;

display:flex;
align-items:center;

padding:15px;

background:linear-gradient(
90deg,
rgba(255,0,100,.6),
rgba(255,150,0,.6),
rgba(255,255,0,.6),
rgba(0,255,180,.6),
rgba(0,180,255,.6),
rgba(120,0,255,.6)
);

}

.circle{

width:18px;
height:18px;
border-radius:50%;
margin-right:10px;

box-shadow:0 0 12px white;

}

.red{background:#ff5f57;}
.yellow{background:#ffbd2f;}
.green{background:#28ca42;}

.search{

margin-left:20px;
flex:1;

height:35px;

border:none;

border-radius:20px;

padding-left:20px;

font-size:15px;

outline:none;

background:rgba(255,255,255,.7);

}

.content{

display:flex;

height:530px;

}

.sidebar{

width:260px;

background:rgba(255,255,255,.25);

padding:20px;

text-align:center;

}

.avatar{

width:170px;
height:170px;

margin:auto;

border-radius:20px;

background:linear-gradient(
45deg,
red,
orange,
yellow,
lime,
cyan,
blue,
violet);

display:flex;
justify-content:center;
align-items:center;

font-size:90px;

color:white;

box-shadow:0 0 30px rgba(255,255,255,.6);

}

.sidebar h2{

margin-top:20px;

font-size:28px;

color:white;

}

.sidebar p{

margin-top:10px;

color:white;

}

.menu{

margin-top:30px;

display:flex;
flex-direction:column;
gap:15px;

}

.menu button{

height:48px;

border:none;

border-radius:15px;

font-size:16px;

font-weight:bold;

cursor:pointer;

color:white;

background:linear-gradient(
90deg,
red,
orange,
yellow,
lime,
cyan,
blue,
violet);

background-size:300%;

animation:rainbow 8s linear infinite;

box-shadow:0 10px 25px rgba(0,0,0,.2);

transition:.3s;

}

.menu button:hover{

transform:scale(1.05);

}

.main{

flex:1;

padding:25px;

overflow:auto;

}

.banner{

height:190px;

border-radius:20px;

background:linear-gradient(
120deg,
rgba(255,0,0,.8),
rgba(255,255,0,.8),
rgba(0,255,255,.8),
rgba(0,0,255,.8),
rgba(255,0,255,.8)
);

display:flex;
justify-content:center;
align-items:center;

font-size:50px;

color:white;

font-weight:bold;

box-shadow:0 10px 25px rgba(0,0,0,.25);

}

.cards{

margin-top:25px;

display:grid;

grid-template-columns:repeat(3,1fr);

gap:20px;

}

.card{

background:rgba(255,255,255,.45);

border-radius:20px;

padding:20px;

box-shadow:0 8px 20px rgba(0,0,0,.2);

transition:.4s;

}

.card:hover{

transform:translateY(-8px);

}

.card h3{

margin-bottom:10px;

background:linear-gradient(
90deg,
red,
orange,
yellow,
green,
cyan,
blue,
violet);

-webkit-background-clip:text;

-webkit-text-fill-color:transparent;

font-size:22px;

}

.card p{

line-height:1.7;

color:#333;

}

.footer{

height:60px;

display:flex;

justify-content:space-between;

align-items:center;

padding:15px;

background:rgba(255,255,255,.25);

}

.footer button{

width:180px;
height:40px;

border:none;

border-radius:12px;

cursor:pointer;

font-size:16px;

color:white;

font-weight:bold;

background:linear-gradient(
90deg,
red,
orange,
yellow,
green,
cyan,
blue,
violet);

box-shadow:0 8px 20px rgba(0,0,0,.2);

}

.icons{

font-size:24px;

color:white;

display:flex;

gap:15px;

}

</style>

</head>

<body>

<div class="window">

<div class="topbar">

<div class="circle red"></div>
<div class="circle yellow"></div>
<div class="circle green"></div>

<input class="search" placeholder="Pesquisar...">

</div>

<div class="content">

<div class="sidebar">

<div class="avatar">☺</div>

<h2>Rainbow User</h2>

<p>Website estilo Vista</p>

<div class="menu">

<button>Home</button>

<button>Galeria</button>

<button>Projetos</button>

<button>Contato</button>

</div>

</div>

<div class="main">

<div class="banner">

🌈 Rainbow Vista

</div>

<div class="cards">

<div class="card">

<h3>Sobre</h3>

<p>
.
</p>

</div>

<div class="card">

<h3>Galeria</h3>

<p>
Você pode colocar imagens,
GIFs,
ícones,
ou qualquer conteúdo aqui.
</p>

</div>

<div class="card">

<h3>Novidades</h3>

<p>
Todos os elementos utilizam
gradientes animados
e brilhos suaves.
</p>

</div>

</div>

</div>

</div>

<div class="footer">

<button>Entrar</button>

<div class="icons">

🌈 ⭐ 💙 🎨

</div>

</div>

</div>

</body>
</html>
