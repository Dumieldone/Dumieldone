- 👋 Hi, I’m @Dumieldone
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
Dumieldone/Dumieldone is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cuisine Afro et du Monde</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #fff7f0;
            color: #333;
        }

        header {
            background-color: #ff914d;
            color: white;
            text-align: center;
            padding: 1.5em 0;
        }

        header h1 {
            margin: 0;
            font-size: 2.5em;
        }

        header p {
            margin: 0.5em 0 0;
        }

        .container {
            padding: 2em;
            max-width: 1200px;
            margin: 0 auto;
        }

        section {
            margin-bottom: 3em;
        }

        section h2 {
            color: #ff914d;
            border-bottom: 2px solid #ff914d;
            display: inline-block;
            margin-bottom: 1em;
        }

        .recette {
            margin-bottom: 2em;
        }

        .recette img {
            max-width: 100%;
            height: auto;
            border-radius: 10px;
        }

        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 1em;
        }

        .gallery img {
            width: 100%;
            height: auto;
            border-radius: 10px;
        }

        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 1em 0;
        }

        footer a {
            color: #ff914d;
            text-decoration: none;
        }

        footer a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <header>
        <h1>Cuisine Afro et du Monde</h1>
        <p>Découvrez la richesse des saveurs dans toute leur simplicité</p>
    </header>

    <div class="container">
        <!-- Section Introduction -->
        <section id="introduction">
            <h2>Bienvenue</h2>
            <p>La cuisine est un voyage. Ici, nous explorons des plats africains et du monde entier, simples à réaliser mais riches en goût. Laissez-vous inspirer et savourez chaque moment !</p>
        </section>

        <!-- Section Recettes -->
        <section id="recettes">
            <h2>Recettes Simples</h2>

            <div class="recette">
                <h3>Yassa au Poulet</h3>
                <img src="https://via.placeholder.com/600x400" alt="Yassa au Poulet">
                <p><strong>Ingrédients :</strong> Poulet, oignons, citron, moutarde, huile, sel, poivre.</p>
                <p><strong>Étapes :</strong> Marinez le poulet, faites-le dorer, puis mijotez avec des oignons et du citron pour un goût irrésistible.</p>
            </div>

            <div class="recette">
                <h3>Riz Jollof</h3>
                <img src="https://via.placeholder.com/600x400" alt="Riz Jollof">
                <p><strong>Ingrédients :</strong> Riz, tomates, poivrons, oignons, épices, huile.</p>
                <p><strong>Étapes :</strong> Préparez une sauce tomate épicée, incorporez le riz et laissez cuire jusqu'à absorption complète.</p>
            </div>
        </section>

        <!-- Section Galerie -->
        <section id="galerie">
            <h2>Galerie des Plats</h2>
            <div class="gallery">
                <img src="https://via.placeholder.com/200" alt="Plat 1">
                <img src="https://via.placeholder.com/200" alt="Plat 2">
                <img src="https://via.placeholder.com/200" alt="Plat 3">
                <img src="https://via.placeholder.com/200" alt="Plat 4">
            </div>
        </section>
    </div>

    <footer>
        <p>Suivez-moi sur <a href="#">Instagram</a> ou <a href="#">YouTube</a> pour plus de recettes !</p>
    </footer>
</body>
</html>
