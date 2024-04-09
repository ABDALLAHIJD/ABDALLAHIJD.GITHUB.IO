<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>QCM de Médecine</title>
<style>
/* Style du corps de la page */
body {
font-family: 'Roboto', sans-serif; /* Utilisation d'une police moderne */
background-color: #f5f5f5; /* Fond gris clair */
margin: 0; /* Supprimer les marges par défaut */
padding: 0; /* Supprimer les remplissages par défaut */
}

```
    /* Style du logo */
    .logo {
        position: absolute;
        top: 20px;
        left: 20px;
        width: 150px; /* Ajustement de la taille du logo */
        height: auto;
    }

    /* Style des cases des chapitres */
    .chapter-box {
        background-color: #2ecc71; /* Vert vif */
        color: #fff; /* Texte blanc */
        padding: 20px;
        margin-bottom: 20px;
        border-radius: 10px; /* Coins arrondis */
        box-shadow: 0 0 10px rgba(0, 0, 0, 0.1); /* Ombre légère */
    }

    /* Style des images de fond */
    .background-image {
        position: fixed;
        bottom: 0;
        right: 0;
        width: 50%; /* Ajustement de la taille de l'image de fond */
        opacity: 0.7; /* Opacité pour un effet de fond */
    }

    /* Style des livres et des stylos */
    .book, .pen {
        position: fixed;
        bottom: 20px;
        right: 20px;
        width: 100px; /* Ajustement de la taille des images de livres et de stylos */
        height: auto;
        opacity: 0.5; /* Opacité pour un effet de fond */
    }
</style>

```

</head>
<body>

```
<header>
    <h1>QCM de Médecine</h1>
</header>

<main>
    <!-- Contenu principal de votre site web ira ici -->
    <section id="anatomie">
        <h2>Anatomie</h2>
        <div class="qcm">
            <h3>QCM Anatomie</h3>
            <ol>
                <li>
                    <p>Quel est le plus grand os du corps humain ?</p>
                    <ul>
                        <li><input type="radio" name="anatomie_q1" value="a"> Fémur</li>
                        <li><input type="radio" name="anatomie_q1" value="b"> Tibia</li>
                        <li><input type="radio" name="anatomie_q1" value="c"> Humerus</li>
                    </ul>
                    <p>Réponse correcte : Fémur</p>
                </li>
                <li>
                    <p>Quel organe du corps humain est responsable de la production des globules rouges ?</p>
                    <ul>
                        <li><input type="radio" name="anatomie_q2" value="a"> Foie</li>
                        <li><input type="radio" name="anatomie_q2" value="b"> Rein</li>
                        <li><input type="radio" name="anatomie_q2" value="c"> Moelle osseuse</li>
                    </ul>
                    <p>Réponse correcte : Moelle osseuse</p>
                </li>
            </ol>
        </div>
    </section>
    <section id="physiologie">
        <h2>Physiologie</h2>
        <div class="qcm">
            <h3>QCM Physiologie</h3>
            <ol>
                <li>
                    <p>Quel est le principal gaz respiratoire impliqué dans la respiration humaine ?</p>
                    <ul>
                        <li><input type="radio" name="physiologie_q1" value="a"> Oxygène</li>
                        <li><input type="radio" name="physiologie_q1" value="b"> Dioxyde de carbone</li>
                        <li><input type="radio" name="physiologie_q1" value="c"> Azote</li>
                    </ul>
                    <p>Réponse correcte : Oxygène</p>
                </li>
                <li>
                    <p>Quel est le rôle principal des reins dans le corps humain ?</p>
                    <ul>
                        <li><input type="radio" name="physiologie_q2" value="a"> Contrôle de la température corporelle</li>
                        <li><input type="radio" name="physiologie_q2" value="b"> Élimination des déchets du sang</li>
                        <li><input type="radio" name="physiologie_q2" value="c"> Production d'hormones</li>
                    </ul>
                    <p>Réponse correcte : Élimination des déchets du sang</p>
                </li>
            </ol>
        </div>
    </section>
    <!-- Ajoutez d'autres modules avec des QCM ici -->
</main>

<footer>
    <p>Copyright © 2024 QCM de Médecine. Tous droits réservés.</p>
</footer>

```

</body>
</html>
