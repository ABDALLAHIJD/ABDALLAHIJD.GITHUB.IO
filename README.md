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

.container {
max-width: 800px;
margin: 20px auto;
padding: 20px;
background-color: #fff;
border-radius: 10px;
box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

.question {
margin-bottom: 20px;
border: 2px solid #3498db; /* Bordure bleue */
padding: 10px;
border-radius: 5px;
}

.answer {
display: none;
}

.logo {
position: absolute;
top: 20px;
left: 20px;
width: 150px;
height: auto;
}

.background-image {
position: fixed;
bottom: 0;
right: 0;
width: 50%;
opacity: 0.7;
}

.book, .pen {
position: fixed;
bottom: 20px;
right: 20px;
width: 100px;
height: auto;
opacity: 0.5;
}
</style>
</head>
<body>
<img class="logo" src="votre_logo.png" alt="Abdallahi Ahmed Logo">
<img class="background-image" src="votre_image_de_fond.jpg" alt="Thème coloré">
<img class="book" src="livre.png" alt="Livre">
<img class="pen" src="stylo.png" alt="Stylo">

<div class="container">
<header>
<h1>QCM de Médecine</h1>
</header>

```
<main>
    <section id="anatomie">
        <h2>Anatomie</h2>
        <div class="qcm">
            <h3>QCM Anatomie</h3>
            <ol>
                <li class="question">
                    <p>Quel est le plus grand os du corps humain ?</p>
                    <button onclick="showAnswer('answer1')">Répondre</button>
                    <ul>
                        <li><input type="radio" name="anatomie_q1" value="a"> Fémur</li>
                        <li><input type="radio" name="anatomie_q1" value="b"> Tibia</li>
                        <li><input type="radio" name="anatomie_q1" value="c"> Humerus</li>
                    </ul>
                    <p class="answer" id="answer1">Réponse correcte : Fémur</p>
                </li>
                <li class="question">
                    <p>Quel organe du corps humain est responsable de la production des globules rouges ?</p>
                    <button onclick="showAnswer('answer2')">Répondre</button>
                    <ul>
                        <li><input type="radio" name="anatomie_q2" value="a"> Foie</li>
                        <li><input type="radio" name="anatomie_q2" value="b"> Rein</li>
                        <li><input type="radio" name="anatomie_q2" value="c"> Moelle osseuse</li>
                    </ul>
                    <p class="answer" id="answer2">Réponse correcte : Moelle osseuse</p>
                </li>
            </ol>
        </div>
    </section>
    <section id="physiologie">
        <h2>Physiologie</h2>
        <div class="qcm">
            <h3>QCM Physiologie</h3>
            <ol>
                <li class="question">
                    <p>Quel est le principal gaz respiratoire impliqué dans la respiration humaine ?</p>
                    <button onclick="showAnswer('answer3')">Répondre</button>
                    <ul>
                        <li><input type="radio" name="physiologie_q1" value="a"> Oxygène</li>
                        <li><input type="radio" name="physiologie_q1" value="b"> Dioxyde de carbone</li>
                        <li><input type="radio" name="physiologie_q1" value="c"> Azote</li>
                    </ul>
                    <p class="answer" id="answer3">Réponse correcte : Oxygène</p>
                </li>
                <li class="question">
                    <p>Quel est le rôle principal des reins dans le corps humain ?</p>
                    <button onclick="showAnswer('answer4')">Répondre</button>
                    <ul>
                        <li><input type="radio" name="physiologie_q2" value="a"> Contrôle de la température corporelle</li>
                        <li><input type="radio" name="physiologie_q2" value="b"> Élimination des déchets du sang</li>
                        <li><input type="radio" name="physiologie_q2" value="c"> Production d'hormones</li>
                    </ul>
                    <p class="answer" id="answer4">Réponse correcte : Élimination des déchets du sang</p>
                </li>
            </ol>
        </div>
    </section>
    <!-- Ajoutez d'autres modules avec des QCM ici -->

    <!-- Huit cas cliniques de sémiologie -->
    <section id="semiologie">
        <h2>Sémiologie</h2>
        <div class="cas-cliniques">
            <h3>Cas cliniques de Sémiologie</h3>
            <ol>
                <li class="question">
                    <p>Un patient se présente avec une fièvre élevée, une toux sévère et une respiration sifflante. Quel est le diagnostic probable ?</p>
                    <button onclick="showAnswer('answer5')">Répondre</button>
                    <ul>
                        <li><input type="radio" name="semio_q1" value="a"> Pneumonie</li>
                        <li><input type="radio" name="semio_q1" value="b"> Bronchite</li>
                        <li

```

<!-- Huit cas cliniques de sémiologie -->
<section id="semiologie">
<h2>Sémiologie</h2>
<div class="cas-cliniques">
<h3>Cas cliniques de Sémiologie</h3>
<ol>
<li class="question">
<p>Un patient se présente avec une fièvre élevée, une toux sévère et une respiration sifflante. Quel est le diagnostic probable ?</p>
<button onclick="showAnswer('answer5')">Répondre</button>
<ul>
<li><input type="radio" name="semio_q1" value="a"> Pneumonie</li>
<li><input type="radio" name="semio_q1" value="b"> Bronchite</li>
<li><input type="radio" name="semio_q1" value="c"> Asthme</li>
</ul>
<p class="answer" id="answer5">Réponse correcte : Asthme</p>
</li>
<li class="question">
<p>Une patiente présente une vision floue, des maux de tête sévères et une pression intraoculaire élevée. Quelle est la pathologie probable ?</p>
<button onclick="showAnswer('answer6')">Répondre</button>
<ul>
<li><input type="radio" name="semio_q2" value="a"> Cataracte</li>
<li><input type="radio" name="semio_q2" value="b"> Glaucome</li>
<li><input type="radio" name="semio_q2" value="c"> Rétinopathie diabétique</li>
</ul>
<p class="answer" id="answer6">Réponse correcte : Glaucome</p>
</li>
<li class="question">
<p>Un patient se plaint de douleurs thoraciques intenses, irradiant vers le bras gauche, associées à la transpiration et à l'essoufflement. Quel diagnostic est le plus probable ?</p>
<button onclick="showAnswer('answer7')">Répondre</button>
<ul>
<li><input type="radio" name="semio_q3" value="a"> Angine de poitrine</li>
<li><input type="radio" name="semio_q3" value="b"> Infarctus du myocarde</li>
<li><input type="radio" name="semio_q3" value="c"> Péricardite</li>
</ul>
<p class="answer" id="answer7">Réponse correcte : Infarctus du myocarde</p>
</li>
<li class="question">
<p>Un patient présente une douleur abdominale sévère, une sensibilité à la palpation dans le quadrant inférieur droit et une fièvre. Quel est le diagnostic probable ?</p>
<button onclick="showAnswer('answer8')">Répondre</button>
<ul>
<li><input type="radio" name="semio_q4" value="a"> Appendicite</li>
<li><input type="radio" name="semio_q4" value="b"> Colique néphrétique</li>
<li><input type="radio" name="semio_q4" value="c"> Diverticulite</li>
</ul>
<p class="answer" id="answer8">Réponse correcte : Appendicite</p>
</li>
<!-- Ajoutez d'autres cas cliniques ici -->
</ol>
</div>
</section>
</main>

<footer>
<p>Copyright © 2024 QCM de Médecine. Tous droits réservés.</p>
</footer>
