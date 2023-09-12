<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="css/styles.css">
    <title>Minha Autoavaliação 🌃</title>
    <style>
        body {
            background-color: #4a4a91; /* Amarelo-ouro */
            font-family: "Arial", sans-serif;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #f7fa43; /* Azul-celeste */
            color: #b6a6ff; /* Amarelo-dourado */
            text-align: center;
            padding: 30px;
            border-radius: 50%;
            position: relative;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.2); /* Sombra sutil */
        }

        header::before {
            content: "🌟🌟🌟"; /* Estrelas como elemento decorativo */
            font-size: 40px;
            position: absolute;
            top: -55px;
            left: 50%;
            transform: translateX(-50%);
        }

        main {
            max-width: 800px;
            margin: 20px auto;
            padding: 20px;
            background-color: #FFF4F7; /* Rosa claro */
            border-radius: 15px; /* Bordas arredondadas */
            box-shadow: 0 5px 10px rgba(0, 0, 0, 0.1); /* Sombra sutil */
        }

        h1 {
            font-size: 36px;
            text-align: center;
            text-transform: uppercase;
            color: #FFD700; /* Amarelo-dourado */
            margin-bottom: 20px;
        }

        a {
            font-size: 16px; /* Tamanho de fonte aumentado */
            color: #0074E4; /* Azul-celeste para links */
            text-decoration: underline; /* Sublinhado para links */
        }

        section {
            margin-top: 20px;
            padding: 20px;
            background-color: #FFF4F7; /* Rosa claro */
            border-radius: 15px; /* Bordas arredondadas */
            box-shadow: 0 5px 10px rgba(0, 0, 0, 0.1); /* Sombra sutil */
            position: relative;
        }

        /* Exemplo de pincelada como elemento decorativo */
        section::after {
            content: "";
            background-image: url('seu-caminho-para-uma-imagem-de-pincelada.jpg');
            background-size: cover;
            opacity: 0.1;
            top: 0;
            left: 0;
            bottom: 0;
            right: 0;
            position: absolute;
            z-index: -1;
            border-radius: 15px;
        }

        img {
            max-width: 100%;
            height: auto;
            display: block;
            margin: 0 auto;
            max-height: 200px;
            border-radius: 10px;
        }

        .icon {
            font-size: 24px;
            margin-right: 10px;
        }

        .footer-info {
            background-color: #FFD700; /* Amarelo-dourado */
            padding: 20px;
            text-align: center;
        }

        .footer-info a {
            color: #0074E4; /* Azul-celeste para links no rodapé */
            text-decoration: underline; /* Sublinhado para links no rodapé */
        }
    </style>
</head>
<body>
    <header>
        <h1>Minha Autoavaliação🌌</h1>
    </header>
    <main>
        <section>
            <h2><span class="icon">✨</span> Autoavaliação✨</h2>
            <p>Eu sou Ana Clara Nadaletti e esta é minha autoavaliação do terceiro trimestre.</p>
            <img src="https://i.pinimg.com/564x/68/03/5b/68035b7d6a969fa0cb9362b6ddca8349.jpg" alt="Imagem da Lana Del Rey" />
        </section>
    </main>
    <div class="footer-info">
        <p>&copy; 2023 <a href="#">Ana Clara Nadaletti Cervinski</a> 🌟</p>
        <p>Contato: ana.nadaletticervinski@gmail.com</p>
        <p>Telefone: (54) 9655-6799</p>
    </div>
</body>
</html>
