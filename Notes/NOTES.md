 <!-- NOTES -->

 <!-- 1. Quelle différence entre <section> et <div> ? Pourquoi as-tu utilisé l'une ou l'autre ? -->
J'ai compris que la balise <section> sert à représenter une partie importante d'une page qui peux être composé de plusieurs éléments et utile pour le robot google lors de la mise en ligne du site alors que la balise <div> sert un petit peu a mettre ce qu'on veux dedans sans structe défini.

 <!-- 2. Dans ton header, quelles propriétés flex as-tu utilisées, et que fait chacune ? -->
J'ai utilisé plusieurs propriétés Flexbox :
- display: flex; permet d'activer Flexbox.
- justify-content permet de positionner les éléments horizontalement.
- align-items permet d'aligner les éléments verticalement.
- flex-wrap: wrap; permet aux éléments de passer à la ligne quand il n'y a plus assez de place.
Ces propriétés m'ont aidé à placer correctement les carrés demandés dans les différents exercices.

 <!-- 3. Choisis une propriété CSS que tu as utilisée et qui t'était inconnue au départ : que fait-elle ? Que se passe-t-il si tu la retires ? -->
La propriété qui m'était inconnue était flex-wrap.
Avant cet exercice, je ne savais pas qu'on pouvait faire passer automatiquement les éléments à la ligne. Avec flex-wrap: wrap;, les carrés s'organisent sur plusieurs lignes lorsque l'espace manque.
Si je retire cette propriété, tous les carrés restent sur la même ligne et la mise en page ne correspond plus au résultat attendu.
Et aussi padding qui sert à ajouter de l'espace à l'intérieur d'un élément, entre son contenu et sa bordure. opposé de margin.

 <!-- 4. Où as-tu utilisé l'IA ? Cite un prompt que tu as envoyé et ce que tu en as retenu. -->
J'ai utilisé l'IA pour mieux comprendre certaines propriétés CSS que je ne connaissais pas. Ainsi que pour vérifier mon HTML et mon CSS quand quelque chose n'allais pas.
Par exemple, j'ai demandé :
"À quoi sert la commande flex-wrap dans le cadre de mon exercice ?" j'ai aussi transmit le CSS et HTML en amont en lui demandant de l'analyser et de m'expliquer étape par étape ce qui étais bon et ce qui ne l'étais pas et aussi ce qui pouvais être améliorer et pourquoi.
Grâce à cette explication, j'ai compris que cette propriété permet aux éléments d'un conteneur Flexbox de revenir automatiquement à la ligne. l'IA m'a aidé à réaliser plusieurs phase de l'exercice plus facilement.

 <!-- 5. Quel est le point le plus difficile que tu as rencontré, et comment l'as-tu résolu ? -->
La partie la plus difficile a été de comprendre comment positionner les "carrés" exactement comme demandé dans certains exercices, notamment lorsqu'il fallait en aligner plusieurs au centre, à gauche ou à droite dans un même conteneur.
Pour résoudre ce problème, j'ai fait plusieurs essais avec les propriétés Flexbox et j'ai utilisé l'IA pour comprendre le rôle de justify-content, align-items et flex-wrap. Une fois le fonctionnement compris, j'ai pu corriger mes exercices plus facilement.