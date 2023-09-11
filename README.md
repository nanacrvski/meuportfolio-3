Olá!
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="css/styles.css">
    <title>Minha Autoavaliação💞</title>
    <style>
        body {
            background-color: #FFC0CB; /* Rosa claro */
            font-family: Calibri, Century Gothic, sans-serif;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
        }
        
        header {
            background-color: #F08080; /* Rosa claro */
            color: MediumVioletRed;
            text-align: center;
            padding: 30px;
            border-bottom-left-radius: 50%;
            border-bottom-right-radius: 50%;
            position: relative;
            box-shadow: 0px 10px 20px rgba(0, 0, 0, 0.2);
        }

        header::before {
            content: "❣️"; 
            font-size: 40px;
            position: absolute;
            top: -55px;
            left: 50%;
            transform: translateX(-50%);
        }

        /* Adicione decorações nos cantos */
        header::before,
        footer::before,
        footer::after {
            content: "";
            position: absolute;
            width: 50px;
            height: 50px;
            background-color: #F08080; /* Rosa claro */
            border-radius: 50%;
            opacity: 0.7;
        }

        header::before {
            top: -25px;
            left: -25px;
        }

        footer::before {
            bottom: -25px;
            left: -25px;
        }

        footer::after {
            bottom: -25px;
            right: -25px;
        }
        
        main {
            max-width: 800px;
            padding: 30px;
            background-color: Plum;
            border-radius: 20px;
            box-shadow: 0px 10px 20px rgba(0, 0, 0, 0.2);
        }
        
        h1 {
            font-size: 36px;
            text-align: center;
            text-transform: uppercase;
            color: #800080; /* Cor púrpura */
            margin-bottom: 20px;
        }

        /* Estilize o link <a> para torná-lo menor */
        a {
            font-size: 15px; /* Defina o tamanho de fonte desejado */
            text-decoration: none;
            color: #FF69B4; /* Cor rosa mais escura */
        }

        section {
            margin-top: 30px;
        }

        h2 {
            font-size: 24px;
            text-align: center;
            text-transform: uppercase;
            color: #800080; /* Cor púrpura */
        }

        p {
            font-size: 18px;
            text-align: justify;
            color: #4B0082; /* Cor índigo */
            padding: 10px;
            border: 2px dashed #800080; /* Cor púrpura */
            border-radius: 10px;
            box-shadow: 0px 4px 8px rgba(128, 0, 128, 0.2);
        }

        footer {
            text-align: center;
            margin-top: 30px;
            background-color: #800080; /* Cor púrpura */
            padding: 10px;
            border-radius: 10px;
            box-shadow: 0px 4px 8px rgba(128, 0, 128, 0.2);
        }

        footer a {
            font-weight: bold;
            color: #FF69B4; /* Cor rosa mais escura */
        }

        footer a:hover {
            text-decoration: underline;
        }

        /* Adicione uma imagem */
        .imagem {
            display: block;
            margin: 20px auto;
            max-width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <h1>Minha Autoavaliação</h1>
    </header>
    <main>
        <!-- Adicione uma imagem de exemplo -->
        <img src="caminho_para_sua_imagem.jpg" alt="Minha Imagem" class="imagem">
        <section>
            <h2>💗Autoavaliação💗</h2>
            <p>Eu sou Ana Clara Nadaletti e esta é minha autoavaliação...</p>
        </section>
    </main>
    <footer>
        <p>&copy; 2023 <a href="https://youtu.be/d_3WNv4wfEY?si=AYGRCgLlQAs87p9U">Assista ao vídeo "Salvatore"</a> 🌟</p>
    </footer>
</body>
</html>
