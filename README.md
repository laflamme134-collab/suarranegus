index.html # suarranegus
Site officiel de SuaRra Negus — création de sites web professionnels, solutions digitales et services business.
<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <title>SuaRra Negus — Digital Power</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background: #0f172a;
            color: #e5e7eb;
        }

        header {
            text-align: center;
            padding: 40px 20px;
            background: linear-gradient(135deg, #020617, #1e293b);
        }

        header h1 {
            font-size: 32px;
            color: gold;
            margin-bottom: 10px;
        }

        header p {
            font-size: 16px;
            opacity: 0.9;
        }

        nav {
            background: #020617;
        }

        nav ul {
            list-style: none;
            margin: 0;
            padding: 10px;
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
        }

        nav ul li {
            margin: 10px 15px;
        }

        nav ul li a {
            color: #e5e7eb;
            text-decoration: none;
            font-weight: bold;
        }

        nav ul li a:hover {
            color: gold;
        }

        main {
            padding: 20px;
            max-width: 900px;
            margin: auto;
        }

        section {
            background: #020617;
            padding: 25px;
            margin-bottom: 25px;
            border-radius: 12px;
            box-shadow: 0 10px 25px rgba(0,0,0,0.4);
        }

        h2 {
            color: gold;
            margin-bottom: 10px;
        }

        ul li {
            margin: 8px 0;
        }

        .btn {
            display: block;
            padding: 15px;
            margin-top: 15px;
            background: gold;
            color: #020617;
            text-align: center;
            border-radius: 10px;
            font-weight: bold;
            text-decoration: none;
        }

        .btn:hover {
            background: #facc15;
        }

        form input, form textarea {
            width: 100%;
            padding: 12px;
            margin-top: 10px;
            border-radius: 8px;
            border: none;
        }

        form button {
            width: 100%;
            padding: 14px;
            margin-top: 15px;
            background: #16a34a;
            color: white;
            border: none;
            border-radius: 8px;
            font-size: 16px;
            font-weight: bold;
        }

        footer {
            text-align: center;
            padding: 20px;
            background: #020617;
            font-size: 14px;
        }

        @media (max-width: 600px) {
            header h1 {
                font-size: 24px;
            }
        }
    </style>
</head>

<body>

<header>
    <h1>SuaRra Negus</h1>
    <p>Digital Power • Royal Vision</p>
</header>

<nav>
    <ul>
        <li><a href="#accueil">Accueil</a></li>
        <li><a href="#services">Services</a></li>
        <li><a href="#boutique">Boutique</a></li>
        <li><a href="#contact">Contact</a></li>
    </ul>
</nav>

<main>

<section id="accueil">
    <h2>Bienvenue</h2>
    <p>
        SuaRra Negus est une marque digitale spécialisée dans la création
        de sites web professionnels, modernes et rentables pour entreprises
        et particuliers.
    </p>
</section>

<section id="services">
    <h2>Nos services</h2>
    <ul>
        <li>Création de sites web professionnels</li>
        <li>Design moderne & responsive (Android / PC)</li>
        <li>Intégration WhatsApp & paiement mobile</li>
        <li>Accompagnement business digital</li>
    </ul>
</section>

<section id="boutique">
    <h2>Offres & Paiement</h2>

    <p><strong>Site Business Professionnel</strong></p>
    <p>Prix : 75 000 FCFA</p>

    <a class="btn"
       href="https://wa.me/22607690322?text=Bonjour%20je%20veux%20commander%20un%20site%20business%20SuaRra%20Negus"
       target="_blank">
       💬 Commander via WhatsApp
    </a>

    <a class="btn"
       style="background:#16a34a;color:white"
       href="https://wa.me/22605050607?text=Bonjour%20je%20veux%20payer%20par%20Mobile%20Money"
       target="_blank">
       💳 Payer par Mobile Money
    </a>
</section>

<section id="contact">
    <h2>Contact</h2>

    <form onsubmit="envoyerMessage(); return false;">
        <input type="text" placeholder="Votre nom" required>
        <input type="email" placeholder="Votre email" required>
        <textarea rows="5" placeholder="Votre message" required></textarea>
        <button type="submit">Envoyer</button>
    </form>
</section>

</main>

<footer>
    © 2026 SuaRra Negus — Tous droits réservés
</footer>

<script>
    function envoyerMessage() {
        alert("Merci ! Votre message a bien été envoyé 🚀");
    }
</script>

</body>
</html>![Uploading 1765040886531.jpg…]()
