# cservice
Site officiel C-SERVIC
<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>C-SERVICE | Solutions professionnelles</title>
    <link rel="stylesheet" href="style.css">
    <link rel="icon" href="favicon.png" type="image/png">
</head>
<body>
    <!-- Header -->
    <header>
        <div class="container">
            <h1>C-SERVICE</h1>
            <nav>
                <ul>
                    <li><a href="#home">Accueil</a></li>
                    <li><a href="#services">Services</a></li>
                    <li><a href="#about">À propos</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <!-- Hero Section -->
    <section id="home" class="hero">
        <div class="container">
            <h2>Des solutions professionnelles pour votre réussite</h2>
            <p>Nous vous accompagnons dans le développement et l’optimisation de vos services.</p>
            <a href="#contact" class="btn">Contactez-nous</a>
        </div>
    </section>

    <!-- Services Section -->
    <section id="services" class="services">
        <div class="container">
            <h2>Nos Services</h2>
            <div class="service-cards">
                <div class="card">
                    <h3>Service 1</h3>
                    <p>Optimisation et conseils pour améliorer votre activité.</p>
                </div>
                <div class="card">
                    <h3>Service 2</h3>
                    <p>Support technique et assistance pour vos projets professionnels.</p>
                </div>
                <div class="card">
                    <h3>Service 3</h3>
                    <p>Solutions personnalisées adaptées à vos besoins spécifiques.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="about">
        <div class="container">
            <h2>À propos de nous</h2>
            <p>C-SERVICE est dédié à offrir des solutions de qualité pour aider nos clients à réussir dans leurs projets professionnels. Notre équipe est composée de professionnels expérimentés dans divers domaines.</p>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="contact">
        <div class="container">
            <h2>Contactez-nous</h2>
            <form action="mailto:cianney029@gmail.com" method="post" enctype="text/plain">
                <input type="text" name="name" placeholder="Votre nom" required>
                <input type="email" name="email" placeholder="Votre email" required>
                <textarea name="message" rows="5" placeholder="Votre message" required></textarea>
                <button type="submit" class="btn">Envoyer</button>
            </form>
            <p class="contact-info">📍 Route Kansimba | 📞 +243 848681325 | ✉ cianney029@gmail.com</p>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <div class="container">
            <p>&copy; 2026 C-SERVICE. Tous droits réservés.</p>
        </div>
    </footer>
</body>
</html>
/* Reset et styles globaux */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Arial', sans-serif;
}

body {
    line-height: 1.6;
    color: #333;
}

/* Container */
.container {
    width: 90%;
    max-width: 1200px;
    margin: auto;
}

/* Header */
header {
    background: #0055FF;
    color: #fff;
    padding: 20px 0;
}
header h1 {
    display: inline-block;
    margin-left: 20px;
}
header nav ul {
    list-style: none;
    float: right;
    margin-right: 20px;
}
header nav ul li {
    display: inline-block;
    margin-left: 20px;
}
header nav ul li a {
    color: #fff;
    text-decoration: none;
    font-weight: bold;
}

/* Hero */
.hero {
    background: #E0E7FF;
    text-align: center;
    padding: 100px 20px;
}
.hero h2 {
    font-size: 2.5rem;
    margin-bottom: 20px;
}
.hero p {
    font-size: 1.2rem;
    margin-bottom: 30px;
}
.btn {
    background: #0055FF;
    color: #fff;
    padding: 12px 30px;
    text-decoration: none;
    border-radius: 5px;
    transition: 0.3s;
}
.btn:hover {
    background: #003BB5;
}

/* Services */
.services {
    padding: 80px 20px;
    background: #f4f4f4;
}
.services h2 {
    text-align: center;
    margin-bottom: 50px;
}
.service-cards {
    display: flex;
    flex-wrap: wrap;
    gap: 20px;
    justify-content: center;
}
.card {
    background: #fff;
    padding: 30px;
    border-radius: 10px;
    flex: 1 1 250px;
    box-shadow: 0 4px 8px rgba(0,0,0,0.1);
    text-align: center;
}
.card h3 {
    margin-bottom: 15px;
}

/* About */
.about {
    padding: 80px 20px;
    text-align: center;
}

/* Contact */
.contact {
    padding: 80px 20px;
    background: #E0E7FF;
    text-align: center;
}
.contact form {
    max-width: 500px;
    margin: auto;
    display: flex;
    flex-direction: column;
    gap: 15px;
}
.contact input, .contact textarea {
    padding: 10px;
    border-radius: 5px;
    border: 1px solid #ccc;
    width: 100%;
}
.contact-info {
    margin-top: 20px;
    font-weight: bold;
}

/* Footer */
footer {
    background: #0055FF;
    color: #fff;
    text-align: center;
    padding: 20px 0;
}
