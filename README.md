<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Grupo da Família</title>
    <style>
        body {
            font-family: 'Comic Sans MS', cursive;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        header {
            background-color: #f8f8f8;
            text-align: center;
            padding: 20px 0;
        }
        main {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
            padding: 20px;
        }
        section {
            background-color: #fff;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            width: 300px;
            text-align: center;
        }
        h1 {
            color: #333;
        }
        h2 {
            color: #666;
            transition: color 0.3s ease; /* Adicionando transição de cor */
            cursor: pointer; /* Adicionando cursor de ponteiro */
        }
        h2:hover {
            color: #f00; /* Alterando a cor ao passar o mouse */
        }
        p {
            color: #888;
        }
        img {
            max-width: 100%;
            border-radius: 5px;
            margin-top: 10px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Grupo da Família</h1>
    </header>
    <main>
        <section>
            <h2>João Vitor</h2>
            <p>Youtuber apaixonado por Sonic e fundador do Grupo da Família.</p>
            <img src="c:\Users\COMPUTADOR22\Downloads\IMG-20230217-WA0219.jpg" alt="João Vitor">
        </section>
        <section>
            <h2>Roberto</h2>
            <p>Marombeiro que secretamente é um produtor de substâncias ilícitas.</p>
            <img src="c:\Users\COMPUTADOR22\Downloads\IMG-20231007-WA0185.jpg" alt="Roberto">
        </section>
        <section>
            <h2>Luiz Eduardo</h2>
            <p>Playboy morador dos EUA e aficionado por malhar.</p>
            <img src="c:\Users\COMPUTADOR22\Downloads\IMG-20231206-WA0117.jpg" alt="Luiz Eduardo">
        </section>
        <section>
            <h2 id="monteiro">Monteiro</h2> <!-- Adicionando ID para a seção de Monteiro -->
            <p>Estagiário que adora leite.</p>
            <img src="c:\Users\COMPUTADOR22\Downloads\IMG-20231105-WA0020.jpg" alt="Monteiro">
        </section>
        <section>
            <h2>Manuela</h2>
            <p>Patricinha em busca constante do One Piece.</p>
            <img src="c:\Users\COMPUTADOR22\Downloads\IMG-20230804-WA0258.jpg" alt="Manuela">
        </section>
        <section>
            <h2>Matheus</h2>
            <p>Italiano mafioso e travesso.</p>
            <img src="c:\Users\COMPUTADOR22\Downloads\IMG-20230617-WA0081.jpg" alt="Matheus">
        </section>
    </main>
    <audio autoplay loop>
        <source src="https://www.youtube.com/watch?v=63SMENrtLlk&pp=ygUpYm9tIGRpYSBwcmluY2VzYSBwb3IgZmF2b3Igc2VudGUgbmEgZ2xvY2s%3D" type="audio/mpeg">
        Seu navegador não suporta a reprodução de áudio.
    </audio>

    <!-- Script JavaScript -->
    <script>
        // Adicionando um evento de clique ao nome "Monteiro" para redirecionar para outra página
        document.getElementById("monteiro").addEventListener("click", function() {
            window.location.href = "outra_pagina.html"; // Substitua "outra_pagina.html" pelo URL da outra página
        });
    </script>
</body>
</html>
