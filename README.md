<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="css/styles.css">
    <title>Minha Autoavaliação</title>
    <style>
        body {
            background-color: #FFC0CB; /* Rosa claro */
            font-family: Calibri, Century Gothic, sans-serif;
        }
        
        header {
            background-color: #F08080; /* Rosa claro */
            color: MediumVioletRed;
            text-align: center;
            padding: 30px;
            border-bottom-left-radius: 50%;
            border-bottom-right-radius: 50%;
            position: relative;
        }

        header::before {
            content: "\2665"; /* Código HTML para o símbolo de coração */
            font-size: 60px;
            position: absolute;
            top: -20px;
            left: 50%;
            transform: translateX(-50%);
        }
        
        main {
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
            background-color: HotPink;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        
        h1 {
            font-size: 28px;
            text-align: center;
            text-transform: uppercase;
        }
        
        section {
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Minha Autoavaliação</h1>
    </header>
    <main>
        <section>
            <h2>Autoavaliação</h2>
            <p>Eu sou Ana Clara Nadaletti e esta é minha autoavaliação...</p>
        </section>
    </main>
    <footer>
        <p>&copy; 2023 [Ana Clara Nadaletti Cervinski] &hearts;</p> <!-- Adicionei um coração no rodapé -->
    </footer>
</body>
</html>


