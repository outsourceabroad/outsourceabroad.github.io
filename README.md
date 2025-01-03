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
    <h2 data-lang data-lang-en="About Us" data-lang-fr="À Propos" data-lang-es="Sobre Nosotros">About Us</h2>
    <p data-lang data-lang-en="A team with real corporate work experience in Canada, France, Spain, Argentina, Switzerland, Chile, Colombia and other countries, we can provide world class accounting, financial and bookeeping services at competitive rates."
       data-lang-fr="Nous fournissons des services professionnels de premier ordre pour aider les individus et les entreprises à réussir à l'étranger. Notre expertise couvre plusieurs domaines, vous garantissant les meilleures solutions adaptées à vos besoins."
       data-lang-es="Ofrecemos servicios profesionales de primer nivel para ayudar a individuos y empresas a tener éxito en el extranjero. Nuestra experiencia abarca múltiples áreas, asegurando que obtenga las mejores soluciones adaptadas a sus necesidades.">
        We provide top-notch professional services to help individuals and businesses succeed abroad. Our expertise spans multiple domains, ensuring you get the best solutions tailored to your needs.
    </p>
</section>

<section id="services" class="section">
    <h2 data-lang data-lang-en="Our Services" data-lang-fr="Nos Services" data-lang-es="Nuestros Servicios">Our Services</h2>
    <div class="services">
        <div class="service-card">
            <h3 data-lang data-lang-en="Immigration Assistance" data-lang-fr="Assistance en Immigration" data-lang-es="Asistencia Migratoria">Immigration Assistance</h3>
            <p data-lang data-lang-en="We guide you through immigration processes with ease."
               data-lang-fr="Nous vous guidons dans les processus d'immigration en toute simplicité."
               data-lang-es="Le guiamos a través de los procesos de inmigración con facilidad.">
                We guide you through immigration processes with ease.
            </p>
        </div>
        <div class="service-card">
            <h3 data-lang data-lang-en="Business Consulting" data-lang-fr="Consultation en Affaires" data-lang-es="Consultoría Empresarial">Business Consulting</h3>
            <p data-lang data-lang-en="Expand your business overseas with our expert advice."
               data-lang-fr="Développez votre entreprise à l'étranger grâce à nos conseils d'experts."
               data-lang-es="Expanda su negocio en el extranjero con nuestro asesoramiento experto.">
                Expand your business overseas with our expert advice.
            </p>
        </div>
        <div class="service-card">
            <h3 data-lang data-lang-en="Translation Services" data-lang-fr="Services de Traduction" data-lang-es="Servicios de Traducción">Translation Services</h3>
            <p data-lang data-lang-en="We provide translation services between the following languages: English, Spanish, French, Italian and Portuguese"
               data-lang-fr="Surmontez les barrières linguistiques avec des traductions professionnelles."
               data-lang-es="Supere las barreras del idioma con traducciones profesionales.">
                Bridge language barriers with professional translations.
            </p>
        </div>
    </div>
</section>

<section id="contact" class="section">
    <h2 data-lang data-lang-en="Contact Us" data-lang-fr="Contactez-Nous" data-lang-es="Contáctenos">Contact Us</h2>
    <form class="contact-form" action="#" method="post">
        <label for="name" data-lang data-lang-en="Name:" data-lang-fr="Nom:" data-lang-es="Nombre:">Name:</label>
        <input type="text" id="name" name="name" required>

        <label for="email" data-lang data-lang-en="Email:" data-lang-fr="E-mail:" data-lang-es="Correo Electrónico:">Email:</label>
        <input type="email" id="email" name="email" required>

        <label for="message" data-lang data-lang-en="Message:" data-lang-fr="Message:" data-lang-es="Mensaje:">Message:</label>
        <textarea id="message" name="message" rows="5" required></textarea>

        <button type="submit" data-lang data-lang-en="Submit" data-lang-fr="Envoyer" data-lang-es="Enviar">Submit</button>
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
