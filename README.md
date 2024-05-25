<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ma Page Personnelle</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333; /* Couleur du texte principal */
        }
        header {
            background-color: #3498db;
            color: white;
            text-align: center;
            margin-bottom: 20px; /* Ajout de marge en bas du header */
            position: relative; /* Position relative pour positionner le texte */
        }
        .banner {
            width: 100%;
            max-height: 300px; /* Taille maximale de la bannière */
            object-fit: cover; /* Ajustement de l'image pour remplir le cadre */
        }
        .header-content {
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            width: 100%;
            padding: 0 20px; /* Ajout de padding aux côtés */
            box-sizing: border-box; /* Box-sizing pour inclure le padding dans la largeur */
        }
        nav {
            background-color: #2c3e50;
            color: white;
            display: flex;
            justify-content: center;
            padding: 0.5em 0;
            margin-bottom: 20px; /* Ajout de marge en bas de la nav */
        }
        nav a {
            color: white;
            margin: 0 1em;
            text-decoration: none;
        }
        .container {
            max-width: 800px;
            margin: 2em auto;
            padding: 1em;
            background-color: white;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .profile-image {
            display: block;
            margin: 0 auto 1em;
            border-radius: 50%;
            width: 150px; /* Taille réduite de l'image */
            height: 150px; /* Taille réduite de l'image */
            object-fit: cover; /* Ajustement de l'image pour remplir le cadre */
        }
        .content {
            text-align: justify; /* Alignement justifié du texte */
            line-height: 1.6; /* Espacement entre les lignes */
            padding: 0 1em; /* Ajout de padding aux côtés */
        }
        .content h2 {
            color: #3498db; /* Couleur des titres */
            margin-top: 1em; /* Marge en haut du titre */
        }
        .content p {
            margin-bottom: 1em; /* Marge en bas de chaque paragraphe */
        }
        .contact-form {
            margin-top: 2em;
        }
        .contact-form input, .contact-form textarea {
            width: calc(100% - 2em);
            padding: 0.5em;
            margin-bottom: 1em;
            border: 1px solid #ddd;
            border-radius: 5px;
        }
        .contact-form button {
            background-color: #3498db;
            color: white;
            padding: 0.5em 2em;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        footer {
            background-color: #2c3e50;
            color: white;
            text-align: center;
            padding: 1em 0;
            margin-top: 2em;
        }
        /* Style ajouté pour les images libres sur internet concernant l'environnement */
        .environment-images {
            display: flex;
            justify-content: space-between;
            margin-top: 2em;
        }
        .environment-image {
            width: calc(33.33% - 10px);
            border-radius: 5px;
            overflow: hidden;
        }
        .environment-image img {
            width: 100%;
            height: auto;
            border-radius: 5px;
            object-fit: cover;
        }
    </style>
</head>
<body>
    <header>
        <img src="https://image.noelshack.com/fichiers/2024/21/6/1716651378-age.jpg" alt="Bannière" class="banner">
        <div class="header-content">
            <h1 style="font-size: 2em;">La Terre, notre unique maison, protégeons-la avec passion et engagement.</h1>
            <p>Portfolio d'Olamidé Israel V. DANSOU. Part 1</p>
        </div>
    </header>
    
    <nav>
        <a href="#about">À propos</a>
        <a href="#contact">Contact</a>
    </nav>
    <div class="container">
        <img src="C:\Users\HP\Documents\pze\1707329587174.jpg" alt="Photo de profil" class="profile-image">
        <div class="content">
            <h2>Mon Parcours</h2>
            <p>Bonjour ! Je suis Olamidé Israel V. DANSOU, un étudiant en deuxième année dans la filière Génie de l'Environnement à l'Ecole Polytechnique d'Abomey Calavi (EPAC) de l'Université d'Abomey Calavi (UAC) au Bénin. Passionné par les enjeux environnementaux contemporains, mon parcours académique me permet d'explorer les aspects techniques, scientifiques et sociaux liés à la préservation de notre écosystème. À travers des projets de recherche, des expériences pratiques sur le terrain et une formation pointue, je m'engage à contribuer activement à des solutions durables pour notre planète.</p>
            
            <h2>Mes Études</h2>
            <p>L’ingénierie environnementale est la branche de l'ingénierie qui étudie les problèmes de la planète de forme scientifique et intégrée, considérant ses dimensions scientifiques: chimiques, physiques, écologiques, biologiques, géologiques, sociales, économiques et technologiques, avec l'objectif de promouvoir un développement durable. Mes études approfondies dans ce domaine m'ont permis de développer une compréhension holistique des défis environnementaux auxquels notre société est confrontée.</p>
            
            <h2>Mes Compétences</h2>
            <p>Durant mes études, j'ai travaillé dans diverses disciplines qui m'ont permis d'acquérir des connaissances et compétences solides en gestion environnementale, traitement des eaux, gestion des déchets, etc. Ma capacité à analyser les problèmes environnementaux de manière critique et à proposer des solutions novatrices est renforcée par mon expérience pratique et mes compétences techniques acquises au fil de mon parcours académique.</p>
            
            <h2>Mes Passions</h2>
            <p>Je suis passionné par la protection de l'environnement et je m'efforce d'utiliser mes compétences pour contribuer à des solutions durables. Mon engagement envers la durabilité et la préservation de notre planète se reflète dans mes actions, que ce soit par ma participation à des projets communautaires, des initiatives de sensibilisation ou des recherches visant à améliorer les pratiques environnementales.</p>
            
            <h2>Mes Intérêts Personnels</h2>
            <p>En dehors de mes études, j'ai développé un intérêt profond pour la lecture, qui m'aide à enrichir mes connaissances et à comprendre les enjeux mondiaux actuels. Le basketball est également une passion qui me permet de rester actif et équilibré. De plus, je trouve un immense plaisir à participer à des activités de bénévolat, car cela me donne l'opportunité de contribuer positivement à ma communauté et d'apporter des changements concrets.</p>
            
            <h2>La Filière Génie de l'Environnement</h2>
            <p>La filière Génie de l'Environnement à l'Ecole Polytechnique d'Abomey Calavi (EPAC) de l'Université d'Abomey Calavi offre une formation de pointe pour ceux qui sont passionnés par la protection de notre planète. En étudiant des domaines essentiels tels que la gestion des déchets, le traitement des eaux et la conservation des ressources naturelles, les étudiants sont équipés pour relever les défis environnementaux actuels et futurs. Rejoindre cette filière, c'est s'engager à faire une différence durable et positive dans le monde, tout en développant des compétences techniques et scientifiques précieuses.</p>
            
            <div class="environment-images">
                <div class="environment-image">
                    <img src="https://image.noelshack.com/fichiers/2024/21/6/1716651137-b1.jpeg" alt="Environnement 1">
                </div>
                <div class="environment-image">
                    <img src="https://image.noelshack.com/fichiers/2024/21/6/1716650993-b2.jpg" alt="Environnement 2">
                </div>
                <div class="environment-image">
                    <img src="https://image.noelshack.com/fichiers/2024/21/6/1716651012-b3.jpg" alt="Environnement 3">
                </div>
            </div>
        </div>
        <div class="contact-form">
            <h2>Contactez-moi</h2>
            <form action="https://formspree.io/f/xleqkpyz" method="POST">
                <input type="text" name="name" placeholder="Votre nom" required>
                <input type="email" name="_replyto" placeholder="Votre email" required>
                <textarea name="message" rows="5" placeholder="Votre message" required></textarea>
                <button type="submit">Envoyer</button>
            </form>
        </div>
    </div>
    <footer>
        <p>© 2024 Ma Page Personnelle | Tous droits réservés</p>
    </footer>
</body>
</html>
