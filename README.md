!DOCTYPE html>
<html lang="nl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>Huis Vervangings Centrale</title>
</head>
<body>
    <header>
        <h1>Huis Vervangings Centrale</h1>
        <nav>
            <ul>
                <li><a href="#diensten">Diensten</a></li>
                <li><a href="#contact">Contact</a></li>
                <li><a href="#over">Over ons</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section id="diensten">
            <h2>Onze Diensten</h2>
            <p>Wij bieden vervangingen voor alle soorten huishoudelijke apparaten.</p>
        </section>
        <section id="over">
            <h2>Over Ons</h2>
            <p>Wij zijn gespecialiseerd in het vervangen van defecte apparaten en zorgen voor een snelle service.</p>
        </section>
        <section id="contact">
            <h2>Contact</h2>
            <p>Neem contact met ons op via info@hvc.nl of bel ons op 0123-456789.</p>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 Huis Vervangings Centrale. Alle rechten voorbehouden.</p>
    </footer>
</body>
</html>
CSS (styles.css)
css
Code kopiëren
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

header {
    background-color: #4CAF50;
    color: white;
    padding: 20px;
    text-align: center;
}

nav ul {
    list-style-type: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 15px;
}

nav a {
    color: white;
    text-decoration: none;
}

main {
    padding: 20px;
}

section {
    margin: 20px 0;
}

footer {
    text-align: center;
