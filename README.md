<!DOCTYPE html>
<html lang="pt-br">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Hello Kitty Kawaii Game</title>

<link href="https://fonts.googleapis.com/css2?family=Fredoka:wght@400;600&display=swap" rel="stylesheet">

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:'Fredoka',sans-serif;
}

body{

background:linear-gradient(180deg,#ffd8ec,#ffc2df,#fff0f7);
overflow:hidden;
height:100vh;
display:flex;
justify-content:center;
align-items:center;
}

.container{

width:900px;
height:600px;

background:white;
border-radius:35px;
border:8px solid #ff9cc8;
box-shadow:0 0 35px #ffb8d9;

text-align:center;
padding:20px;

position:relative;

}

h1{

font-size:45px;
color:#ff4b95;
margin-bottom:10px;

}

p{

font-size:20px;
color:#ff74af;

}

#game{

margin:auto;
margin-top:20px;

width:760px;
height:350px;

background:#fff5fa;

border-radius:25px;

border:4px dashed #ffb6d6;

position:relative;

overflow:hidden;

}

#kitty{

position:absolute;

font-size:65px;

cursor:pointer;

transition:.2s;

user-select:none;

}

#kitty:hover{

transform:scale(1.15);

}

.info{

margin-top:20px;

display:flex;

justify-content:center;

gap:60px;

font-size:25px;

color:#ff4b95;

font-weight:bold;

}

button{

margin-top:20px;

padding:15px 35px;

font-size:20px;

border:none;

border-radius:30px;

background:#ff65aa;

color:white;

cursor:pointer;

transition:.3s;

}

button:hover{

transform:scale(1.08);

background:#ff4a98;

}

.falling{

position:absolute;

animation:fall linear infinite;

}

@keyframes fall{

0%{
transform:translateY(-120px);
}

100%{
transform:translateY(120vh);
}

}

</style>

</head>

<body>

<div class="container">

<h1>🎀 Hello Kitty 🎀</h1>

<p>Clique na Hello Kitty antes que ela fuja!</p>

<div id="game">

<div id="kitty">🐱🎀</div>

</div>

<div class="info">

<div>Pontos:
<span id="score">0</span>
</div>

<div>Tempo:
<span id="time">30</span>
</div>

</div>

<button onclick="startGame()">
Começar
</button>

</div>

<script>

const kitty=document.getElementById("kitty");

const game=document.getElementById("game");

const scoreText=document.getElementById("score");

const timeText=document.getElementById("time");

let score=0;

let time=30;

let playing=false;

let move;

let timer;

function randomPosition(){

let x=Math.random()*(game.clientWidth-80);

let y=Math.random()*(game.clientHeight-80);

kitty.style.left=x+"px";

kitty.style.top=y+"px";

}

kitty.onclick=function(){

if(!playing)return;

score++;

scoreText.innerHTML=score;

randomPosition();

}

function startGame(){

clearInterval(move);

clearInterval(timer);

score=0;

time=30;

playing=true;

scoreText.innerHTML=0;

timeText.innerHTML=30;

randomPosition();

move=setInterval(randomPosition,700);

timer=setInterval(function(){

time--;

timeText.innerHTML=time;

if(time<=0){

playing=false;

clearInterval(move);

clearInterval(timer);

alert("🎉 Você fez "+score+" pontos! 💖");

}

},1000);

}

for(let i=0;i<40;i++){

let heart=document.createElement("div");

heart.className="falling";

heart.innerHTML=Math.random()>0.5?"💖":"🌸";

heart.style.left=Math.random()*100+"vw";

heart.style.fontSize=(20+Math.random()*20)+"px";

heart.style.animationDuration=(5+Math.random()*5)+"s";

heart.style.animationDelay=Math.random()*5+"s";

document.body.appendChild(heart);

}

</script>

</body>
</html>
