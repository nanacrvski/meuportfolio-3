<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Meu Perfil Y2K</title>

<style>

*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Verdana,sans-serif;
}

body{
    background:linear-gradient(135deg,#6f6dff,#a85cff,#d98cff);
    min-height:100vh;
    display:flex;
    justify-content:center;
    align-items:center;
    padding:30px;
}

.container{
    width:1000px;
    background:rgba(255,255,255,0.15);
    backdrop-filter:blur(10px);
    border:3px solid #d8c0ff;
    border-radius:25px;
    padding:20px;
    box-shadow:0 0 30px rgba(255,255,255,0.4);
}

.topbar{
    background:linear-gradient(to bottom,#caa8ff,#9f7cff);
    border-radius:20px;
    padding:10px;
    text-align:center;
    color:white;
    font-weight:bold;
    margin-bottom:20px;
}

.menu{
    display:flex;
    gap:15px;
    margin-bottom:20px;
}

.menu button{
    flex:1;
    border:none;
    padding:12px;
    border-radius:30px;
    background:linear-gradient(to bottom,#ffb1ff,#9b7cff);
    color:white;
    font-weight:bold;
    cursor:pointer;
}

.menu button:hover{
    transform:scale(1.05);
}

.content{
    display:grid;
    grid-template-columns:1fr 1fr;
    gap:20px;
}

.card{
    background:rgba(255,255,255,0.25);
    border:2px solid #d9c7ff;
    border-radius:20px;
    padding:15px;
}

.card h2{
    color:white;
    margin-bottom:10px;
}

.card p{
    color:white;
    line-height:1.5;
}

.gallery{
    display:grid;
    grid-template-columns:1fr 1fr;
    gap:10px;
}

.img{
    height:140px;
    border-radius:15px;
    background:linear-gradient(45deg,#ffd6ff,#a1d7ff);
    display:flex;
    justify-content:center;
    align-items:center;
    color:#6a00a8;
    font-weight:bold;
}

.big{
    margin-top:10px;
    height:180px;
}

.footer{
    margin-top:20px;
    text-align:center;
    color:white;
}

</style>
</head>
<body>

<div class="container">

    <div class="topbar">
        ✨ site by Anac ✨
    </div>

    <div class="menu">
        <button>🏠 Home</button>
        <button>🎀 Sobre</button>
        <button>📷 Galeria</button>
        <button>💌 Contato</button>
    </div>

    <div class="content">

        <div class="card">
            <h2>💜 Sobre Mim</h2>

            <p>
                Nome: Ana Clara
            </p>

            <br>

            <p>
                Estudante de pedagogia
            </p>

            <br>

            <div class="gallery">
                <div class="img">Imagem 1</div>
                <div class="img">Imagem 2</div>
            </div>

            <div class="img big">
                Imagem Destaque
            </div>
        </div>

        <div class="card">

            <h2>🌸 Perfil</h2>

          <div class="gallery">

    <div class="img-container">
        <img src="anime1.png" alt="Anime">
    </div>

    <div class="img-container">
        <img src="anime2.png" alt="Anime">
    </div>

</div>

<div class="img-container big">
    <img src="carro.png" alt="BMW">
</div>

    </div>

    <div class="footer">
        💖 Criado por Anac • 2026 💖
    </div>

</div>

</body>
</html>

</div>

</body>
</html>
