<!DOCTYPE html>
<html lang="fr">
 <head>
<meta name="google-site-verification" content="y-J4skNwhLxwWnVo4ANV3_mxBMIEHdFqR8ZboUeY65k" />
  <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cianney SERVICE - Site Officiel</title>
    <style>
       .social-buttons {
    margin-top: 30px;
    text-align: center;
}

.social-btn {
    display: inline-block;
    padding: 12px 25px;
    margin: 8px;
    border-radius: 30px;
    color: white;
    text-decoration: none;
    font-weight: bold;
    transition: 0.3s;
}

.social-btn:hover {
    transform: scale(1.08);
}

.instagram { background: linear-gradient(45deg, #E1306C, #F77737); }
.tiktok { background: #000000; }
.whatsapp { background: #25D366; }
.email { background: #0055FF; }
 /* Reset et styles globaux */
        * { margin: 0; padding: 0; box-sizing: border-box; font-family: Arial, sans-serif; }
        body { line-height: 1.6; color: #333; }

        /* Container */
        .container { width: 90%; max-width: 1200px; margin: auto; }

        /* Header */
        header { background: #0055FF; color: #fff; padding: 20px 0; display: flex; align-items: center; justify-content: space-between; flex-wrap: wrap; }
        header h1 { display: flex; align-items: center; font-size: 1.8rem; }
        header h1 img { width: 50px; height: 50px; border-radius: 50%; margin-right: 10px; }
        nav ul { list-style: none; display: flex; flex-wrap: wrap; gap: 20px; }
        nav ul li a { color: #fff; text-decoration: none; font-weight: bold; }

        /* Hero */
        .hero { background: #E0E7FF; text-align: center; padding: 100px 20px; }
        .hero h2 { font-size: 2.5rem; margin-bottom: 20px; }
        .hero p { font-size: 1.2rem; margin-bottom: 30px; }
        .btn { background: #0055FF; color: #fff; padding: 12px 30px; text-decoration: none; border-radius: 5px; transition: 0.3s; display: inline-block; margin: 5px; }
        .btn:hover { background: #003BB5; }

        /* Services */
        .services { padding: 80px 20px; background: #f4f4f4; }
        .services h2 { text-align: center; margin-bottom: 50px; }
        .service-cards { display: flex; flex-wrap: wrap; gap: 20px; justify-content: center; }
        .card { background: #fff; padding: 30px; border-radius: 10px; flex: 1 1 250px; box-shadow: 0 4px 8px rgba(0,0,0,0.1); text-align: center; }
        .card h3 { margin-bottom: 15px; }

        /* About */
        .about { padding: 80px 20px; text-align: center; }
        .about img { width: 150px; height: 150px; border-radius: 50%; margin-bottom: 20px; }

        /* Contact */
        .contact { padding: 80px 20px; background: #E0E7FF; text-align: center; }
        .contact form { max-width: 500px; margin: auto; display: flex; flex-direction: column; gap: 15px; }
        .contact input, .contact textarea { padding: 10px; border-radius: 5px; border: 1px solid #ccc; width: 100%; }
        .contact-info { margin-top: 20px; font-weight: bold; }

        /* Footer */
        footer { background: #0055FF; color: #fff; text-align: center; padding: 20px 0; }

        /* Responsive */
        @media(max-width:768px){
            header { flex-direction: column; align-items: flex-start; }
            nav ul { flex-direction: column; gap: 10px; margin-top: 10px; }
            .hero { padding: 60px 20px; }
            .services { padding: 60px 20px; }
            .about { padding: 60px 20px; }
            .contact { padding: 60px 20px; }
        }
    </style>
</head>
<body>

    <!-- Header -->
    <header class="container">
        <h1>
            <img src="photo.jpg" alt="Cianney">
            Cianney SERVICE
        </h1>
        <nav>
            <ul>
                <li><a href="#hero">Accueil</a></li>
                <li><a href="#services">Services</a></li>
                <li><a href="#about">À propos</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <!-- Hero -->
    <section class="hero" id="hero">
        <h2>Des solutions professionnelles pour votre réussite</h2>
        <p>Nous vous accompagnons dans le développement et l’optimisation de vos services.</p>
        <!-- Boutons vers tes plateformes -->
        <div>
            <a href="https://www.instagram.com/cianney_officiel" target="_blank" class="btn">Instagram</a>
            <a href="https://www.tiktok.com/@cianney_officiel" target="_blank" class="btn">TikTok</a>
            <a href="https://wa.me/243848681325" target="_blank" class="btn">WhatsApp</a>
            <a href="mailto:cianney029@gmail.com" class="btn">Email</a>
        </div>
    </section>

    <!-- Services -->
    <section class="services container" id="services">
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
    </section>

    <!-- About -->
    <section class="about container" id="about">
        <h2>À propos de nous</h2>
        <img src="photo.jpg" alt="Cianney">
        <p>C-SERVICE est dédié à offrir des solutions de qualité pour aider nos clients à réussir dans leurs projets professionnels. Notre équipe est composée de professionnels expérimentés dans divers domaines.</p>
    </section>
    
    </form>
   <section class="contact" id="contact">
    <h2>Contactez-nous</h2>
    <form>
        <input type="text" placeholder="Votre nom" required>
        <input type="email" placeholder="Votre email" required>
        <textarea placeholder="Votre message" required></textarea>
        <button type="submit" class="btn">Envoyer</button>
    </form>

    <!-- Boutons réseaux -->
    <div class="social-buttons">
        <a href="https://www.instagram.com/cianney_officiel" target="_blank" class="social-btn instagram">Instagram</a>
        <a href="https://www.tiktok.com/@cianney_officiel" target="_blank" class="social-btn tiktok">TikTok</a>
        <a href="https://wa.me/243850406200?text=Bonjour%20je%20viens%20du%20site%20Cianney%20Service" target="_blank" class="social-btn whatsapp">WhatsApp</a>
        <a href="mailto:cianney029@gmail.com" class="social-btn email">Email</a>
    </div>

    <p class="contact-info">📍 Route Kansimba | 📞 +243 850406200 | ✉ cianney029@gmail.com</p>
</section>

    </section>
    <!-- Footer -->
    <footer>
        © 2026 Cianney SERVICE. Tous droits réservés.
    </footer>

</body>
</html>


