<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Meu Site Rosa</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial, sans-serif;
}

body{
    background:#ffd6e7;
    color:#5a0033;
}

header{
    background:#ff69b4;
    color:white;
    text-align:center;
    padding:30px;
}

nav{
    background:#ff85c1;
    display:flex;
    justify-content:center;
    gap:20px;
    padding:15px;
}

nav a{
    color:white;
    text-decoration:none;
    font-weight:bold;
}

nav a:hover{
    color:#5a0033;
}

section{
    background:white;
    width:80%;
    margin:20px auto;
    padding:20px;
    border-radius:15px;
    box-shadow:0 0 10px rgba(0,0,0,0.1);
}

button{
    background:#ff69b4;
    color:white;
    border:none;
    padding:10px 20px;
    border-radius:10px;
    cursor:pointer;
}

button:hover{
    background:#ff1493;
}

footer{
    text-align:center;
    padding:20px;
    background:#ff69b4;
    color:white;
    margin-top:20px;
}
</style>

</head>
<body>

<header>
    <h1>🌸 Meu Site Rosa 🌸</h1>
    <p>Bem-vindo ao meu primeiro site!</p>
</header>

<nav>
    <a href="#inicio">Início</a>
    <a href="#sobre">Sobre</a>
    <a href="#contato">Contato</a>
</nav>

<section id="inicio">
    <h2>🏠 Início</h2>
    <p>Este é um site simples criado em HTML, CSS e JavaScript em um único arquivo.</p>
</section>

<section id="sobre">
    <h2>💖 Sobre Mim</h2>
    <p>
        Aqui você pode colocar informações sobre você, seus estudos,
        seus projetos e seus objetivos.
    </p>
</section>

<section id="contato">
    <h2>📩 Contato</h2>
    <p>Clique no botão abaixo:</p>
    <br>
    <button onclick="mostrarMensagem()">
        Clique Aqui
    </button>
    <p id="mensagem"></p>
</section>

<footer>
    <p>© 2026 - Meu Site Rosa</p>
</footer>

<script>
function mostrarMensagem(){
    document.getElementById("mensagem").innerHTML =
    "🌷 Obrigado por visitar meu site! 🌷";
}
</script>

</body>
</html>
</html>
