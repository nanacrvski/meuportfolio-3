<!DOCTYPE html>
<html lang="pt-BR">

<head>

<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Cyber Anime World ✦</title>

<link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@400;700&family=Fredoka:wght@400;700&display=swap" rel="stylesheet">


<style>


*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:'Fredoka',sans-serif;
}


body{

min-height:100vh;

background:

linear-gradient(
135deg,
#59d9ff,
#9b8cff,
#ff7ddc,
#ffe3fa
);

background-size:400% 400%;

animation:bg 12s infinite;

overflow-x:hidden;

color:white;

}



@keyframes bg{

0%{
background-position:0% 50%;
}

50%{
background-position:100% 50%;
}

100%{
background-position:0% 50%;
}

}




/* EFEITOS */


body:before{

content:"";

position:fixed;

inset:0;

background:

radial-gradient(circle,#fff8,transparent 20%);

pointer-events:none;

}




.main{


width:95%;

max-width:1500px;

margin:30px auto;


background:

rgba(255,255,255,.20);


backdrop-filter:blur(20px);


border:

3px solid #ffffff70;


border-radius:35px;


box-shadow:

0 0 50px #ff7beaaa;


overflow:hidden;


}





/* TOPO */


header{


height:90px;

display:flex;

align-items:center;

justify-content:space-between;

padding:20px 40px;


background:#ffffff30;


}




.logo{


font-family:Orbitron;

font-size:35px;


text-shadow:

0 0 15px white;


}




.menu a{


text-decoration:none;

color:white;

margin:10px;

padding:10px 20px;


border-radius:30px;


background:#ffffff35;


}



.menu a:hover{


background:#ff8fe5;


box-shadow:0 0 20px white;


}







/* PAINEL PRINCIPAL */


.content{


display:grid;


grid-template-columns:

100px 1fr 350px;


gap:20px;


padding:25px;


}





/* MENU LATERAL */


.side{


display:flex;

flex-direction:column;

gap:15px;


}



.side div{


height:70px;

border-radius:20px;


background:#ffffff40;


display:flex;

align-items:center;

justify-content:center;


font-size:30px;


border:2px solid white;


}




/* AREA CENTRAL */


.screen{


background:#ffffff25;


border-radius:30px;


padding:25px;


border:

2px solid #ffffff80;


}




.banner{


height:300px;


border-radius:25px;


background:


linear-gradient(

135deg,

#7ee8ff,

#ff9be8

);


display:flex;


align-items:center;


justify-content:center;


font-size:55px;


font-family:Orbitron;


text-align:center;


box-shadow:

0 0 30px white;


}




.search{


margin:20px 0;


padding:15px;


border-radius:20px;


background:white;


color:#9d75ff;


font-weight:bold;


}




.cards{


display:grid;


grid-template-columns:

repeat(2,1fr);


gap:20px;


}





.card{


padding:20px;


border-radius:25px;


background:#ffffff35;


border:2px solid #ffffff70;


}



.card h2{


font-family:Orbitron;


color:white;


}




/* PERSONAGEM */


.character{


background:#ffffff30;


border-radius:30px;


padding:25px;


text-align:center;


}



.avatar{


height:240px;


border-radius:25px;


background:

linear-gradient(

135deg,

#8eeaff,

#ffb6e8

);


display:flex;


align-items:center;


justify-content:center;


font-size:100px;


border:3px solid white;


box-shadow:

0 0 30px white;


}



.character h1{


margin-top:20px;


font-family:Orbitron;


}





.stats{


margin-top:20px;


background:#ffffff30;


padding:15px;


border-radius:20px;


}





.music{


margin-top:20px;


padding:20px;


border-radius:25px;


background:#ff7edb66;


}



.bar{


height:10px;


background:white;


border-radius:20px;


animation:music 4s infinite;


}



@keyframes music{


50%{

width:100%;

}

}




/* RODAPE */


footer{


text-align:center;

padding:25px;


background:#ffffff25;


font-size:18px;


}




@media(max-width:900px){


.content{

grid-template-columns:1fr;

}


.cards{

grid-template-columns:1fr;

}


.menu{

display:none;

}


}



</style>


</head>



<body>


<div class="main">



<header>


<div class="logo">

✦ NEON WORLD

</div>



<div class="menu">

<a href="#">Home</a>

<a href="#">Perfil</a>

<a href="#">Galeria</a>

<a href="#">Links</a>

</div>



</header>





<div class="content">



<div class="side">


<div>♡</div>

<div>音</div>

<div>★</div>

<div>☁</div>

<div>✦</div>


</div>







<div class="screen">



<div class="banner">


HATSUNE<br>
CYBER SPACE


</div>



<div class="search">

🔍 EDIT BY YOUR NAME

</div>



<div class="cards">


<div class="card">

<h2>

PROFILE

</h2>

<p>

🌸 Nome: Ana<br>
🎧 Música: Anime Pop<br>
🎮 Gamer Mode ON

</p>


</div>




<div class="card">


<h2>

COLOR PALETTE

</h2>


<p>

💙 Azul Neon<br>
💗 Rosa Pastel<br>
💜 Roxo Cyber

</p>


</div>



</div>




</div>







<div class="character">


<div class="avatar">

🌸

</div>



<h1>

ANIME GIRL

</h1>


<p>

Cyber Idol • Gamer • Dreamer

</p>




<div class="stats">

⭐ Level 99

<br><br>

💎 Magic Power

<br><br>

🎵 Music Player

</div>



<div class="music">


▶ NOW PLAYING


<br><br>


<div class="bar"></div>


</div>



</div>



</div>





<footer>

💗 Made with love • Anime Cyber Dream ✨

</footer>



</div>



</body>

</html>
