Sommaire 

📑 Sommaire du projet “Chocolatine Jump & Run – 2026”  
1️⃣ Présentation du projet

Objectif : créer un jeu de type Jump & Run en JavaScript

Thème : Toulouse et ses monuments

Technologies : HTML, CSS, JavaScript

Inspirations : Super Mario Bros., Flappy Bird, Google Dinosaur

2️⃣ Monuments utilisés

Place du Capitole

Stadium de Toulouse

Stade Toulousain

Île du Ramier

Airbus

Quai de la Daurade

Cité de l’Espace

3️⃣ Extensions et mécaniques avancées

Obstacles volants (ballons de rugby, Beluga Airbus)

Glissade avec skate

Double saut

Salto acrobatique

Vagues dynamiques (Quai de la Daurade)

Étoiles et ciel animé (Cité de l’Espace)

Bonus : invincibilité, multiplicateurs de points

Drapeau de fin de niveau avec animation victoire

4️⃣ Interface de démarrage

Sélection du joueur

Chocolatine classique, chocolat blanc, dorée

Sélection de la difficulté

Facile / Moyen / Difficile

Choix des niveaux (carte interactive, style Mario)

Différents modes de jeu

Classique, Endless, Chrono, Bonus

Choix des villes (extension possible)

Gestion en HTML / CSS / JS

Sauvegarde des choix via localStorage

5️⃣ Structure complète du projet

group\_project/  
│  
├── index.html                 → Écran de démarrage  
├── game.html                  → Page du jeu  
│  
├── css/  
│   ├── style.css                
│   ├── menu.css                 
│   ├── game.css                
│   └── animations.css           
│  
├── js/  
│   ├── main.js                  
│   ├── player/  
│   │   ├── player.js            
│   │   ├── animations.js        
│   │   └── abilities.js         
│   ├── obstacles/  
│   │   ├── groundObstacles.js   
│   │   ├── flyingObstacles.js   
│   │   └── waves.js              
│   ├── levels/  
│   │   ├── levels.js            
│   │   ├── level1.js            
│   │   ├── level2.js  
│   │   └── level3.js  
│   ├── ui/  
│   │   ├── menu.js              
│   │   ├── scoreboard.js        
│   │   └── endLevel.js          
│   └── utils/  
│       ├── collision.js         
│       ├── random.js            
│       └── constants.js         
│  
└── assets/  
    ├── images/                  
    └── sounds/                

Découpage modulaire pour les fichiers \> 300 lignes

Modules indépendants par type : joueur, obstacles, niveaux, UI, utilitaires

6️⃣ LocalStorage

Sauvegarde des choix du joueur (personnage, difficulté, niveau)

Sauvegarde des scores et bonus

Déblocage des niveaux

Paramètres globaux du jeu (mode, multiplicateur)

À ne pas utiliser pour la boucle du jeu ou animations temps réel

7️⃣ Déroulement d’une partie

Choix du joueur, niveau et difficulté

Lancement du jeu

La chocolatine court automatiquement

Gestion obstacles (saut, double saut, glissade)

Collecte bonus et étoiles

Atteinte du drapeau → animation de victoire

Déblocage du niveau suivant

Mise à jour du score et sauvegarde dans localStorage

8️⃣ Points forts pour l’évaluation

Code modulaire et lisible → 60 %

Présentation claire et interactive → 40 %

Gameplay dynamique et créatif

Réutilisation et extensibilité

Immersion dans Toulouse et design original  
