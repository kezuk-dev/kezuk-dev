<head>
    <meta charset="UTF-8">
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            color: #333;
            margin: 0;
            padding: 0;
        }

        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
        }

        header {
            background: #333;
            color: #fff;
            padding-top: 30px;
            min-height: 70px;
            border-bottom: #77d9ff 3px solid;
        }

        header a {
            color: #fff;
            text-decoration: none;
            text-transform: uppercase;
            font-size: 16px;
        }

        header ul {
            padding: 0;
            list-style: none;
            display: flex;
            justify-content: space-around;
        }

        header li {
            display: inline;
        }

        .main-info {
            padding: 30px;
            background: #fff;
            margin: 20px 0;
            box-shadow: 0px 0px 15px rgba(0, 0, 0, 0.1);
        }

        .main-info h1 {
            margin-top: 0;
        }

        .social-links {
            display: flex;
            justify-content: space-between;
            margin-top: 20px;
        }

        .social-links div {
            flex: 1;
            padding: 10px;
            text-align: center;
            background: #f9f9f9;
            margin: 5px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }

        .social-links div a {
            text-decoration: none;
            color: #333;
        }

        .github-stats {
            display: flex;
            justify-content: space-between;
            margin-top: 20px;
        }

        .github-stats img {
            max-width: 100%;
            border-radius: 5px;
        }
    </style>
</head>
<body>

    <header>
        <div class="container">
            <ul>
                <li><a href="#">Accueil</a></li>
                <li><a href="#about">À propos de moi</a></li>
                <li><a href="#stats">Statistiques GitHub</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </div>
    </header>

    <div class="container">
        <div class="main-info">
            <h1>Bienvenue sur mon profil GitHub!</h1>
            <p>Je suis Kezuk, un développeur de 21 ans passionné par le développement en Lua, Java, HTML, CSS, React, et JavaScript.</p>
        </div>

        <div id="stats" class="github-stats">
            <div>
                <h2>Nombre de vues de mon profil:</h2>
                <img src="https://komarev.com/ghpvc/?username=kezuk&color=blue" alt="Compteur de vues">
            </div>
            <div>
                <h2>Langages les plus utilisés:</h2>
                <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=kezuk&layout=compact&theme=tokyonight" alt="Langages les plus utilisés">
            </div>
        </div>

        <div id="about" class="main-info">
            <h2>À propos de moi</h2>
            <p>Je suis un développeur passionné qui aime apprendre et travailler avec différentes technologies. Voici quelques langages dans lesquels j'ai de l'expérience:</p>
            <ul>
                <li>Lua</li>
                <li>Java</li>
                <li>HTML & CSS</li>
                <li>React</li>
                <li>JavaScript</li>
            </ul>
        </div>

        <div id="contact" class="main-info">
            <h2>Contact</h2>
            <div class="social-links">
                <div>
                    <p><strong>Discord:</strong></p>
                    <p><a href="#">kezukdev</a></p>
                </div>
                <div>
                    <p><strong>Email:</strong></p>
                    <p><a href="mailto:contact@kezuk.quest">contact@kezuk.quest</a></p>
                </div>
            </div>
        </div>
    </div>
</body>
