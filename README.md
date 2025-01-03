<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Professional Services Abroad</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #004080;
            color: white;
            padding: 20px;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #003366;
            padding: 10px 0;
        }
        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
        }
        nav a:hover {
            text-decoration: underline;
        }
        .language-selector {
            position: absolute;
            top: 10px;
            right: 10px;
        }
        .language-selector select {
            padding: 5px;
            font-size: 16px;
        }
        .section {
            padding: 20px;
            max-width: 1200px;
            margin: auto;
        }
        .services {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            justify-content: space-around;
        }
        .service-card {
            border: 1px solid #ccc;
            border-radius: 8px;
            width: 300px;
            text-align: center;
            padding: 15px;
            box-shadow: 2px 2px 10px rgba(0, 0, 0, 0.1);
        }
        .contact-form {
            display: flex;
            flex-direction: column;
            gap: 10px;
            max-width: 500px;
            margin: auto;
        }
        footer {
            background-color: #002244;
            color: white;
            text-align: center;
            padding: 10px 0;
            margin-top: 20px;
        }
    </style>
    <script>
        function changeLanguage(lang) {
            document.documentElement.lang = lang;
            const elements = document.querySelectorAll('[data-lang]');
            elements.forEach(el => {
                const text = el.getAttribute(`data-lang-${lang}`);
                if (text) {
                    el.textContent = text;
                }
            });
        }
    </script>
</head>
<body>

<div class="language-selector">
    <label for="language">Language: </label>
    <select id="language" onchange="changeLanguage(this.value)">
        <option value="en">English</option>
        <option value="fr">Français</option>
        <option value="es">Español</option>
    </select>
</div>

<header>
    <h1 data-lang data-lang-en="Professional Services Abroad" data-lang-fr="Services Professionnels à l'Étranger" data-lang-es="Servicios Profesionales en el Extranjero">Professional Services Abroad</h1>
    <p data-lang data-lang-en="Your gateway to opportunities and solutions worldwide" data-lang-fr="Votre passerelle vers des opportunités et des solutions dans le monde entier" data-lang-es="Su puerta de acceso a oportunidades y soluciones en todo el mundo">Your gateway to opportunities and solutions worldwide</p>
</header>

<nav>
    <a href="#about" data-lang data-lang-en="About Us" data-lang-fr="À Propos" data-lang-es="Sobre Nosotros">About Us</a>
    <a href="#services" data-lang data-lang-en="Services" data-lang-fr="Services" data-lang-es="Servicios">Services</a>
    <a href="#contact" data-lang data-lang-en="Contact" data-lang-fr="Contact" data-lang-es="Contacto">Contact</a>
</nav>

<section id="about" class="section">
    <h2 data-lang data-lang-en="About Us" data-lang-fr="À Propos" data-lang-es="Sobre Nosotros">À Propos</h2>
    <p data-lang data-lang-en="A team with real corporate work experience in Canada, France, Spain, Argentina, Switzerland, Chile, Colombia and other countries, we can provide world class accounting, financial and bookkeeping services at competitive rates. We can also help you with your documents on multiple languages, with original documentation needed from other countries or with other services to business planning to start operations in Argentina."
       data-lang-fr="Une équipe avec une véritable expérience professionnelle dans des entreprises au Canada, en France, en Espagne, en Argentine, en Suisse, au Chili, en Colombie et dans d'autres pays, nous offrons des services de comptabilité, financiers et de tenue de livres de classe mondiale à des tarifs compétitifs. Nous pouvons également vous aider avec vos documents dans plusieurs langues, avec la documentation originale nécessaire d'autres pays ou avec d'autres services pour planifier les affaires et démarrer des opérations en Argentine."
       data-lang-es="Un equipo con experiencia real en empresas en Canadá, Francia, España, Argentina, Suiza, Chile, Colombia y otros países, podemos ofrecer servicios de contabilidad, financieros y de gestión contable de clase mundial a tarifas competitivas. También podemos ayudarle con sus documentos en varios idiomas, con la documentación original necesaria de otros países o con otros servicios para planificar negocios y comenzar operaciones en Argentina.">
        Une équipe avec une véritable expérience professionnelle...
    </p>
</section>

<section id="services" class="section">
    <h2 data-lang data-lang-en="Our Services" data-lang-fr="Nos Services" data-lang-es="Nuestros Servicios">Nos Services</h2>
    <div class="services">
        <div class="service-card">
            <h3 data-lang data-lang-en="Citizenship Assistance" data-lang-fr="Assistance à la Citoyenneté" data-lang-es="Asistencia Ciudadana">Assistance à la Citoyenneté</h3>
            <p data-lang data-lang-en="We can help you obtain the original documentation of your ancestor immigrant from Spain, Italy or France."
               data-lang-fr="Nous pouvons vous aider à obtenir la documentation originale de votre ancêtre immigrant d'Espagne, d'Italie ou de France."
               data-lang-es="Podemos ayudarle a obtener la documentación original de su ancestro inmigrante de España, Italia o Francia.">
                Nous pouvons vous aider à obtenir...
            </p>
        </div>
        <div class="service-card">
            <h3 data-lang data-lang-en="Business Consulting" data-lang-fr="Consultation en Affaires" data-lang-es="Consultoría Empresarial">Consultation en Affaires</h3>
            <p data-lang data-lang-en="Expand your business overseas with our expert advice."
               data-lang-fr="Développez votre entreprise à l'étranger grâce à nos conseils d'experts."
               data-lang-es="Expanda su negocio en el extranjero con nuestro asesoramiento experto.">
                Développez votre entreprise à l'étranger...
            </p>
        </div>
        <div class="service-card">
            <h3 data-lang data-lang-en="Translation Services" data-lang-fr="Services de Traduction" data-lang-es="Servicios de Traducción">Services de Traduction</h3>
            <p data-lang data-lang-en="We provide translation services between the following languages: English, Spanish, French, Italian and Portuguese."
               data-lang-fr="Nous fournissons des services de traduction entre les langues suivantes : anglais, espagnol, français, italien et portugais."
               data-lang-es="Ofrecemos servicios de traducción entre los siguientes idiomas: inglés, español, francés, italiano y portugués.">
                Nous fournissons des services de traduction...
            </p>
        </div>
    </div>
</section>

<section id="contact" class="section">
    <h2 data-lang data-lang-en="Contact Us" data-lang-fr="Contactez-Nous" data-lang-es="Contáctenos">Contactez-Nous</h2>
    <form class="contact-form" action="#" method="post">
        <label for="name" data-lang data-lang-en="Name:" data-lang-fr="Nom:" data-lang-es="Nombre:">Nom:</label>
        <input type="text" id="name" name="name" required>

        <label for="email" data-lang data-lang-en="Email:" data-lang-fr="E-mail:" data-lang-es="Correo Electrónico:">E-mail:</label>
        <input type="email" id="email" name="email" required>

        <label for="message" data-lang data-lang-en="Message:" data-lang-fr="Message:" data-lang-es="Mensaje:">Message:</label>
        <textarea id="message" name="message" rows="5" required></textarea>

        <button type="submit" data-lang data-lang-en="Submit" data-lang-fr="Envoyer" data-lang-es="Enviar">Envoyer</button>
    </form>
</section>

<footer>
    <p data-lang data-lang-en="&copy; 2024 Professional Services Abroad. All rights reserved."
       data-lang-fr="&copy; 2024 Services Professionnels à l'Étranger. Tous droits réservés."
       data-lang-es="&copy; 2024 Servicios Profesionales en el Extranjero. Todos los derechos reservados.">
        &copy; 2024 Professional Services Abroad. All rights reserved.
    </p>
</footer>

</body>
</html>
