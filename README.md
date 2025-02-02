<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Teste GitHub Pages</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            padding: 50px;
        }
        button {
            padding: 10px 20px;
            font-size: 16px;
            cursor: pointer;
        }
    </style>
</head>
<body>
    <h1>Meu primeiro site no GitHub Pages!</h1>
    <p>Clique no botão abaixo para mudar a cor de fundo.</p>
    <button onclick="mudarCor()">Mudar Cor</button>
    
    <script>
        function mudarCor() {
            const cores = ['#FF5733', '#33FF57', '#3357FF', '#F3FF33', '#FF33E3'];
            document.body.style.backgroundColor = cores[Math.floor(Math.random() * cores.length)];
        }
    </script>
</body>
</html>
