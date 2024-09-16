<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Página Dividida</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        html, body {
            height: 100%;
            font-family: Arial, sans-serif;
            background-color: #121212; /* Fundo escuro */
            overflow: hidden; /* Remove scroll */
        }

        .container {
            display: flex;
            height: 100vh;
        }

        .left, .right {
            width: 50%;
            display: flex;
            justify-content: center;
            align-items: center;
        }

        .left {
            flex-direction: column;
        }

        .image {
            height: 50vh; /* 50% da altura da tela */
            width: 50vh;  /* Manter a imagem quadrada */
            background-color: #333; /* Cor de fundo para a imagem (placeholder) */
            display: flex;
            justify-content: center;
            align-items: center;
        }

        .image img {
            max-width: 100%;
            max-height: 100%;
        }

        h1 {
            color: white;
            margin-top: 20px;
            font-size: 2em;
            text-align: center;
        }
    </style>
</head>
<body>
    <div class="container">
        <!-- Lado esquerdo -->
        <div class="left">
            <div class="image">
                <img src="sua-imagem-aqui.jpg" alt="Imagem">
            </div>
            <h1>Título da Imagem</h1>
        </div>

        <!-- Lado direito (vazio ou personalizável) -->
        <div class="right">
            <!-- Você pode adicionar conteúdo aqui, se necessário -->
        </div>
    </div>
</body>
</html>
