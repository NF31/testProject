Structure finale du projet “Chocolatine Jump & Run”

group\_project/  
│  
├── index.html                 → Écran de démarrage (menu principal)  
├── game.html                  → Page du jeu  
│  
├── css/  
│   ├── style.css              → Style global, reset, couleurs, polices  
│   ├── menu.css               → Style de l’interface de démarrage  
│   ├── game.css               → Styles du jeu : obstacles, joueur, animations  
│   ├── animations.css         → Animations (jump, slide, salto, vagues, étoiles)  
│  
├── js/  
│   ├── main.js                → Boucle principale \+ initialisation du jeu  
│  
│   ├── player/  
│   │   ├── player.js          → Gestion position, saut, double saut, glissade, salto  
│   │   ├── animations.js      → Toutes les animations du joueur  
│   │   └── abilities.js       → Capacités spéciales (invincibilité, bonus étoiles)  
│  
│   ├── obstacles/  
│   │   ├── groundObstacles.js → Monuments / obstacles au sol  
│   │   ├── flyingObstacles.js → Ballons, avions, obstacles volants  
│   │   └── waves.js            → Vagues animées pour Quai de la Daurade  
│  
│   ├── levels/  
│   │   ├── levels.js          → Configuration globale des niveaux  
│   │   ├── level1.js          → Paramètres spécifiques niveau 1  
│   │   ├── level2.js  
│   │   └── level3.js  
│  
│   ├── ui/  
│   │   ├── menu.js            → Gestion de l’interface de démarrage  
│   │   ├── scoreboard.js      → Gestion du score, multiplicateurs, bonus  
│   │   └── endLevel.js        → Drapeau final \+ animation victoire  
│  
│   └── utils/  
│       ├── collision.js       → Détection des collisions  
│       ├── random.js          → Fonctions utilitaires (random, timers…)  
│       └── constants.js       → Paramètres globaux (vitesse, tailles, couleurs)  
│  
└── assets/  
    ├── images/                → Images du joueur, monuments, obstacles, décor  
    └── sounds/                → Effets sonores, musique

🧠 Rôle de chaque dossier

html → structure de la page et zones de jeu

css → styles et animations

js → logique du jeu organisée par modules

assets → images et sons pour un rendu immersif  
