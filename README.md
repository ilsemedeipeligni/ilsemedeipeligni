<!DOCTYPE html>
<html lang="it">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Azienda Agricola - Aglio Rosso di Sulmona</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f9f9f9;
        }
        header {
            background-color: #4CAF50;
            color: white;
            padding: 1rem;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #333;
        }
        nav a {
            color: white;
            padding: 14px 20px;
            text-decoration: none;
            text-align: center;
        }
        nav a:hover {
            background-color: #ddd;
            color: black;
        }
        .container {
            padding: 2rem;
            max-width: 800px;
            margin: auto;
        }
        .product {
            display: flex;
            flex-direction: column;
            align-items: center;
            margin: 2rem 0;
        }
        .product img {
            max-width: 100%;
            height: auto;
            border-radius: 8px;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 1rem 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>

<header>
    <h1>Azienda Agricola - Aglio Rosso di Sulmona</h1>
</header>

<nav>
    <a href="#chi-siamo">Chi Siamo</a>
    <a href="#prodotti">Prodotti</a>
    <a href="#contatti">Contatti</a>
</nav>

<div class="container">
    <section id="chi-siamo">
        <h2>Chi Siamo</h2>
        <p>Benvenuti nella nostra azienda agricola, specializzata nella coltivazione dell'aglio rosso di Sulmona, un prodotto tipico e pregiato della nostra regione. La nostra missione è offrire prodotti di alta qualità coltivati con passione e rispetto per la tradizione.</p>
    </section>

    <section id="prodotti">
        <h2>Prodotti</h2>
        <div class="product">
            <h3>Aglio Rosso di Sulmona</h3>
            <img src="immagini/aglio-rosso-sulmona.jpg" alt="Aglio Rosso di Sulmona">
            <p>Il nostro aglio rosso di Sulmona è conosciuto per il suo sapore unico e le sue proprietà benefiche. Coltivato con metodi tradizionali, è un ingrediente essenziale per molte ricette.</p>
        </div>
        <div class="product">
            <h3>Prodotti Tipici</h3>
            <img src="immagini/prodotti-tipici.jpg" alt="Prodotti Tipici">
            <p>Oltre all'aglio rosso, offriamo una selezione di prodotti tipici locali, inclusi conserve, oli e vini, tutti realizzati con ingredienti genuini e secondo le tradizioni del territorio.</p>
        </div>
    </section>

    <section id="contatti">
        <h2>Contatti</h2>
        <p>Per maggiori informazioni sui nostri prodotti o per effettuare un ordine, non esitate a contattarci:</p>
        <p>Email: info@aziendaagricola.com</p>
        <p>Telefono: +39 012 345 6789</p>
        <p>Indirizzo: Via delle Campagne, 123, 67039 Sulmona AQ, Italia</p>
    </section>
</div>

<footer>
    <p>&copy; 2024 Azienda Agricola - Aglio Rosso di Sulmona. Tutti i diritti riservati.</p>
</footer>

</body>
</html>
