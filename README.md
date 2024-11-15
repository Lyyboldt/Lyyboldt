<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SAL-Beauty – Luxus für Ihr Leben</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <!-- Header -->
    <header class="header">
        <div class="container">
            <h1 class="logo">SAL-Beauty</h1>
            <nav class="nav">
                <a href="#about">Über Uns</a>
                <a href="#shop">Shop</a>
                <a href="#contact">Kontakt</a>
            </nav>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="hero">
        <h2>Luxuriöse Kosmetik seit 1975</h2>
        <p>Erleben Sie die Schönheit von Qualität.</p>
        <a href="#shop" class="btn">Zum Shop</a>
    </section>

    <!-- Über Uns -->
    <section id="about" class="about">
        <div class="container">
            <h2>Über Uns</h2>
            <p>SAL-Beauty wurde 1975 in New York gegründet und hat seit 1999 einen zweiten Standort in Hamburg. Unsere Geschäftsführerinnen, Aileen Gocht, Shamaila Amjad und Lydia Boldt, setzen auf erstklassige Produkte und herausragenden Service.</p>
        </div>
    </section>

    <!-- Shop -->
    <section id="shop" class="shop">
        <div class="container">
            <h2>Unser Shop</h2>
            <p>Entdecken Sie unsere exklusiven Produkte.</p>
            <!-- Produktbeispiele -->
            <div class="products">
                <div class="product-card">
                    <img src="placeholder.jpg" alt="Produkt 1">
                    <h3>Produkt 1</h3>
                    <p>Beschreibung des Produkts.</p>
                    <a href="#" class="btn">Jetzt kaufen</a>
                </div>
                <div class="product-card">
                    <img src="placeholder.jpg" alt="Produkt 2">
                    <h3>Produkt 2</h3>
                    <p>Beschreibung des Produkts.</p>
                    <a href="#" class="btn">Jetzt kaufen</a>
                </div>
            </div>
        </div>
    </section>

    <!-- Kontakt -->
    <section id="contact" class="contact">
        <div class="container">
            <h2>Kontakt</h2>
            <p>Wir sind für Sie da. Schreiben Sie uns!</p>
            <form>
                <input type="text" placeholder="Ihr Name" required>
                <input type="email" placeholder="Ihre E-Mail" required>
                <textarea placeholder="Ihre Nachricht" required></textarea>
                <button type="submit" class="btn">Senden</button>
            </form>
        </div>
    </section>

    <!-- Footer -->
    <footer class="footer">
        <div class="container">
            <p>&copy; 2024 SAL-Beauty. Alle Rechte vorbehalten.</p>
        </div>
    </footer>
</body>
</html>
/* Allgemeine Stile */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    color: #fff;
    background-color: #121212;
}

.container {
    width: 90%;
    max-width: 1200px;
    margin: 0 auto;
}

.header {
    background-color: #800000; /* Bordeauxrot */
    padding: 1rem 0;
}

.logo {
    font-size: 1.5rem;
    font-weight: bold;
}

.nav a {
    margin: 0 1rem;
    color: #fff;
    text-decoration: none;
}

.hero {
    text-align: center;
    padding: 5rem 1rem;
    background-color: #4b0000;
}

.hero .btn {
    display: inline-block;
    padding: 0.8rem 2rem;
    background-color: #b30000;
    color: #fff;
    text-decoration: none;
    border-radius: 5px;
    font-size: 1.2rem;
}

.about, .shop, .contact {
    padding: 3rem 0;
    background-color: #333;
    text-align: center;
}

.product-card {
    display: inline-block;
    margin: 1rem;
    padding: 1rem;
    background-color: #4b0000;
    border-radius: 8px;
}

.contact form input, .contact form textarea {
    width: 100%;
    margin: 0.5rem 0;
    padding: 0.8rem;
    border: none;
    border-radius: 5px;
}

.contact form .btn {
    background-color: #b30000;
    border: none;
    cursor: pointer;
}

.footer {
    text-align: center;
    padding: 1rem 0;
    background-color: #800000;
}
