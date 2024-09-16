<head>
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
            display: flex;
            justify-content: center;
            align-items: center;
        }

        .image img {
            max-width: 100%;
            max-height: 100%;
            border-radius: 5px; /* Borda arredondada (opcional) */
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
                <!-- Imagem vinda de um link -->
                <img src="https://oldschool.runescape.wiki/images/thumb/V_sigil_detail.png/1200px-V_sigil_detail.png?3a2b6" alt="Imagem de exemplo">
            </div>
            <h1>Vitra Asura/h1>
        </div>

        <!-- Lado direito (vazio ou personalizável) -->
        <div class="right">
            <!-- Conteúdo opcional -->
        </div>
    </div>
</body>
