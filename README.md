<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Galeria Digital</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            background-color: #e6f0ff; /* Azul claro */
            color: #fff;
        }
        header {
            background-color: #002b5c; /* Azul escuro */
            padding: 15px;
            text-align: center;
        }
        header h1 {
            margin: 0;
            font-size: 2em;
        }
        header p {
            margin: 5px 0 0;
            font-size: 1em;
        }
        nav {
            text-align: center;
            margin-top: 20px;
        }
        nav button {
            background-color: #004080; /* Azul médio */
            border: none;
            color: white;
            padding: 12px 20px;
            margin: 5px;
            border-radius: 5px;
            cursor: pointer;
            font-size: 1em;
            transition: background-color 0.3s;
        }
        nav button:hover {
            background-color: #0059b3; /* Azul mais claro no hover */
        }
    </style>
</head>
<body>

    <header>
        <h1>Galeria Digital</h1>
        <p>Rua Padre Medeiros Nº56, Exu - PE</p>
    </header>

    <nav>
        <button onclick="abrirMenu()">Menu</button>
        <button onclick="abrirChat()">Chat</button>
    </nav>

    <script>
        function abrirMenu() {
            alert("Menu em construção...");
        }
        function abrirChat() {
            alert("Chat em breve disponível!");
        }
    </script>

</body>
</html>
