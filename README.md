<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meu blog tech</title>

    <style>
        * {
            box-sizing: border-box;
        }

        body {
            margin: 0;
            background: #ffffff;
            font-family: Georgia, "Times New Roman", serif;
            color: #222;
        }

        .container {
            width: 100%;
            max-width: 500px;
            margin: 10px auto 0;
            border-top: 6px solid #dce0e5;
            border-bottom: 6px solid #dce0e5;
            min-height: 560px;
        }

        /* Cabeçalho */
        header {
            background: #1e446d;
            height: 87px;
            color: white;
            text-align: center;
            padding-top: 22px;
        }

        header h1 {
            margin: 0;
            font-size: 20px;
            font-weight: bold;
        }

        header p {
            margin-top: 12px;
            font-size: 9px;
        }

        /* Posts */
        main {
            padding: 16px 25px 10px;
        }

        .post {
            position: relative;
            padding-left: 39px;
            margin-bottom: 12px;
        }

        .icone {
            position: absolute;
            left: 0;
            top: 0;
            width: 32px;
            height: 32px;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 28px;
        }

        .post h2 {
            margin: 2px 0 8px;
            color: #244b70;
            font-size: 15px;
            line-height: 1.1;
        }

        .autor {
            margin: 0 0 8px;
            font-size: 10px;
            font-weight: bold;
        }

        .texto {
            margin: 0 0 8px;
            font-family: Georgia, "Times New Roman", serif;
            font-size: 9px;
            line-height: 1.25;
        }

        .fonte {
            margin: 0 0 8px;
            font-size: 9px;
        }

        /* Reações */
        .reacoes {
            display: flex;
            gap: 3px;
        }

        .reacao {
            border: 1px solid #c9c9c9;
            border-radius: 2px;
            background: #f8f8f8;
            height: 15px;
            min-width: 27px;
            padding: 0 4px;
            font-family: Arial, sans-serif;
            font-size: 8px;
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 2px;
        }

        /* Ícones */
        .icone1 {
            color: #4a9dcc;
        }

        .icone2 {
            font-size: 27px;
        }

        .icone3 {
            font-size: 30px;
        }

        .icone4 {
            font-size: 27px;
        }
    </style>
</head>

<body>

<div class="container">

    <header>
        <h1>Meu blog tech</h1>
        <p>Vou compartilhar conhecimentos sobre tecnologia e programação</p>
    </header>

    <main>

        <!-- Post 1 -->
        <article class="post">
            <div class="icone icone1">👨‍💻</div>

            <h2>Meu primeiro post</h2>

            <p class="autor">Por: Ana julia</p>

            <p class="texto">
                Boas-vindas ao meu novo blog! Aqui vou compartilhar dicas de
                programação e curiosidades da área de tecnologia.
            </p>

            <div class="reacoes">
                <span class="reacao">💗 0</span>
                <span class="reacao">👍 0</span>
            </div>
        </article>


        <!-- Post 2 -->
        <article class="post">
            <div class="icone icone2">🌎</div>

            <h2>A quantidade de dados no mundo é surreal</h2>

            <p class="autor">Por: Ana julia</p>

            <p class="texto">
                Estima-se que 90% de todos os dados existentes no mundo hoje
                foram gerados apenas nos últimos dois anos. Vivemos em uma
                verdadeira explosão de informação que não para de acelerar.
            </p>

            <p class="fonte">Fonte: Jornal Opção</p>

            <div class="reacoes">
                <span class="reacao">💗 0</span>
                <span class="reacao">👍 0</span>
            </div>
        </article>


        <!-- Post 3 -->
        <article class="post">
            <div class="icone icone3">📦</div>

            <h2>O primeiro mouse não era de plástico</h2>

            <p class="autor">Por: Ana julia</p>

            <p class="texto">
                Antes do design ergonômico e das luzes RGB, o primeiro mouse do
                mundo foi construído em madeira! Criado por Douglas Engelbart
                em 1964, ele tinha o formato de uma caixa quadrada e apenas
                um botão.
            </p>

            <p class="fonte">Fonte: TecMundo</p>

            <div class="reacoes">
                <span class="reacao">💗 0</span>
                <span class="reacao">👍 0</span>
            </div>
        </article>


        <!-- Post 4 -->
        <article class="post">
            <div class="icone icone4">👄</div>

            <h2>Por que o Bluetooth se chama assim?</h2>

            <p class="autor">Por: Ana julia</p>

            <p class="texto">
                O nome é uma homenagem ao rei viking Harald Blatand Gormsson,
                que unificou tribos da Escandinávia. Seu apelido era Harald
                "Bluetooth" porque seus dentes eram tão podres que tinham uma
                coloração azul escura.
            </p>

            <p class="fonte">Fonte: TechTudo</p>

            <div class="reacoes">
                <span class="reacao">💗 0</span>
                <span class="reacao">👍 0</span>
            </div>
        </article>

    </main>

</div>

</body>
</html>
