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
        section {
            padding: 20px;
            text-align: center;
            color: #000;
        }
        iframe {
            border: none;
            width: 100%;
            height: 350px;
            border-radius: 8px;
        }
        footer {
            background-color: #002b5c;
            color: white;
            text-align: center;
            padding: 10px;
            margin-top: 20px;
        }
    </style>
</head>
<body>

    <header>
        <h1>Galeria Digital</h1>
        <p>Rua Padre Medeiros Nº56, Exu - PE</p>
    </header>

    <!-- Google Tradutor -->
    <div id="google_translate_element" style="text-align:center; margin: 10px;"></div>
    <script type="text/javascript">
        function googleTranslateElementInit() {
            new google.translate.TranslateElement(
                {pageLanguage: 'pt', includedLanguages: 'en,es,fr,it,de', layout: google.translate.TranslateElement.InlineLayout.SIMPLE},
                'google_translate_element'
            );
        }
    </script>
    <script type="text/javascript" src="//translate.google.com/translate_a/element.js?cb=googleTranslateElementInit"></script>

    <nav>
        <button onclick="abrirMenu()">Menu</button>
        <button onclick="abrirChat()">Chat</button>
        <button onclick="abrirAnuncios()">Anúncios</button>
    </nav>

    <section>
        <h2>Localização</h2>
        <!-- Google Maps -->
        <iframe 
            src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3877.6294720739726!2d-39.723!3d-7.514!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x7a0b5f4d!2sRua%20Padre%20Medeiros%2056%2C%20Exu%20-%20PE!5e0!3m2!1spt-BR!2sbr!4v0000000000000" 
            allowfullscreen="" loading="lazy">
        </iframe>
    </section>

    <section id="anuncios" style="display:none;">
        <h2>Página de Anúncios</h2>
        <p>Aqui você pode colocar imagens e descrições de anúncios.</p>
    </section>

    <footer>
        &copy; 2025 Galeria Digital - Todos os direitos reservados
    </footer>

    <script>
        function abrirMenu() {
            alert("Menu em construção...");
        }
        function abrirChat() {
            alert("Chat em breve disponível!");
        }
        function abrirAnuncios() {
            document.getElementById("anuncios").style.display = "block";
            window.scrollTo({ top: document.getElementById("anuncios").offsetTop, behavior: 'smooth' });
        }
    </script>

</body>
</html>
