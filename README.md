<div align="center">⚡ BOOSTLY

🎮 Understand your PC. Estimate your FPS. Play smarter.

L'outil open source pour analyser son matériel, estimer ses performances en jeu et mieux comprendre son PC.

""Open Source" (https://img.shields.io/badge/Open%20Source-Yes-8A2BE2?style=for-the-badge)" (LICENSE)
""Platform" (https://img.shields.io/badge/Platform-Web-00BFFF?style=for-the-badge)" (#-compatibilité)
""Status" (https://img.shields.io/badge/Status-In%20Development-orange?style=for-the-badge)" (#-feuille-de-route)
""Languages" (https://img.shields.io/badge/Language-HTML%20%7C%20CSS%20%7C%20JavaScript-blue?style=for-the-badge)" (#-technologies)

Gratuit • Open source • Sans installation • Accessible depuis ton navigateur

---

</div>🌌 Présentation

Boostly est un projet open source qui vise à rendre l'analyse des performances informatiques accessible à tous.

Son objectif : permettre à chacun de mieux connaître son matériel, de tester les performances graphiques de son navigateur et d'obtenir des estimations de FPS pour ses jeux préférés.

Que tu utilises un PC gaming, un ordinateur portable ou un appareil Android, Boostly ambitionne de proposer une interface simple, moderne et adaptée à ton appareil.

«🚧 Le projet est en développement. Les fonctionnalités présentées ci-dessous constituent les objectifs du projet et ne sont pas nécessairement toutes disponibles.»

✨ Fonctionnalités

🖥️ Analyse du matériel

Obtiens les informations que ton navigateur permet de récupérer sur ton appareil.

- 🔍 Informations sur le processeur, lorsque disponibles.
- 🎨 Informations graphiques via WebGL, lorsque disponibles.
- 🧠 Informations relatives à la mémoire.
- 📱 Détection du type d'appareil et de certaines capacités du navigateur.
- 🖥️ Informations sur l'écran et la résolution.
- ❓ Possibilité de renseigner manuellement les composants non détectés.

Les navigateurs limitent l'accès à certaines informations matérielles. La détection exacte du processeur, du GPU et de la RAM n'est donc pas garantie.

🎮 Calculateur de FPS

Découvre une estimation des performances possibles dans différents jeux.

Fonctionnalités prévues :

- 🎯 Catalogue de jeux vidéo.
- ⚙️ Sélection du processeur et de la carte graphique.
- 🖥️ Choix de la résolution : 1080p, 1440p et 4K.
- 🎨 Choix des paramètres graphiques.
- 🌈 Prise en compte des technologies graphiques pertinentes selon le jeu.
- 📊 Estimation des FPS moyens et, lorsque les données le permettent, des performances minimales.
- 📈 Indication de la fiabilité des estimations.

Notre objectif : proposer des estimations utiles et transparentes, fondées sur des données de performances identifiables.

Les résultats dépendront de la qualité des données disponibles et ne constitueront jamais une garantie des performances réelles.

🧪 Benchmark graphique

Teste les performances graphiques de ton navigateur grâce à une scène 3D interactive.

Le benchmark pourra mesurer :

- Les FPS moyens pendant le test.
- La stabilité de la fréquence d'affichage.
- Les variations de fluidité.
- Un score de performances dans les conditions du test.

⚠️ Ce benchmark mesure les performances de la scène testée dans le navigateur. Il ne remplace pas un benchmark natif d'un jeu.

⚡ Conseils d'optimisation

Boostly proposera des recommandations pour aider à comprendre les problèmes de performances :

- Identifier les causes possibles des ralentissements.
- Comprendre l'utilisation des ressources.
- Découvrir des moyens sûrs de libérer de l'espace.
- Apprendre à ajuster les paramètres graphiques.
- Trouver les réglages adaptés à son matériel.

Boostly privilégiera les recommandations explicables et les actions que l'utilisateur peut contrôler.

🌍 Un projet multiplateforme

L'objectif est de rendre Boostly accessible depuis :

- 🪟 Windows
- 🐧 Linux
- 🤖 Android
- 🍎 macOS
- 🌐 Tout navigateur compatible

Aucune application native ne sera nécessaire pour les fonctionnalités réalisables directement dans le navigateur.

🛡️ Confidentialité et sécurité

La confiance des utilisateurs est essentielle.

Boostly vise à respecter les principes suivants :

- 🔒 Pas de droits administrateur nécessaires pour les fonctions web.
- 🧹 Aucune suppression automatique de fichiers système.
- ⚙️ Aucune modification silencieuse des paramètres de l'appareil.
- 🔍 Des résultats accompagnés d'explications.
- 📊 Une distinction claire entre données mesurées et estimations.
- 🌐 Un fonctionnement privilégiant les technologies du navigateur.
- 🔐 Une collecte minimale des données personnelles.

Les informations collectées et les éventuels échanges avec des services externes devront être documentés dans le projet.

🛠️ Technologies

Boostly est conçu autour des technologies du Web.

Technologie| Utilisation
HTML5| Structure de l'interface
CSS3| Design, animations et adaptation aux écrans
JavaScript| Logique et fonctionnalités
WebGL| Informations graphiques accessibles et rendu 3D
Web APIs| Accès aux capacités autorisées par le navigateur
GitHub| Hébergement du code source et contributions
GitHub Pages| Hébergement du site, si cette solution est retenue

Des bibliothèques supplémentaires pourront être ajoutées selon les besoins du projet.

🚀 Installation et utilisation

Boostly pourra être utilisé directement en ligne lorsque le site sera publié.

Pour récupérer le code source :

git clone https://github.com/TON-PSEUDO/Boostly.git
cd Boostly

Remplace "TON-PSEUDO" par ton nom d'utilisateur GitHub et adapte le nom du dépôt si nécessaire.

Pour une première version utilisant uniquement HTML, CSS et JavaScript, il suffira d'ouvrir le fichier "index.html" dans un navigateur compatible.

Pour certaines fonctionnalités, notamment les modules utilisant des API du navigateur, un serveur local pourra être nécessaire.

📁 Organisation du projet

Exemple d'organisation possible :

Boostly/
├── index.html
├── README.md
├── LICENSE
├── assets/
│   ├── icons/
│   └── images/
├── css/
│   └── style.css
├── js/
│   ├── app.js
│   ├── hardware.js
│   ├── fps-calculator.js
│   └── benchmark.js
└── data/
    ├── games.json
    └── benchmarks.json

Cette structure pourra évoluer selon l'architecture réellement utilisée.

🗺️ Feuille de route

Phase 1 — Fondations

- [ ] Créer l'interface principale.
- [ ] Concevoir un thème gaming moderne.
- [ ] Adapter le site aux mobiles, tablettes et ordinateurs.
- [ ] Mettre en place la navigation.

Phase 2 — Analyse matérielle

- [ ] Récupérer les informations accessibles dans le navigateur.
- [ ] Afficher les informations indisponibles clairement.
- [ ] Permettre la sélection manuelle des composants.
- [ ] Créer un tableau de bord matériel.

Phase 3 — FPS Calculator

- [ ] Créer le catalogue de jeux.
- [ ] Ajouter les paramètres graphiques.
- [ ] Intégrer une base de données de benchmarks documentée.
- [ ] Calculer des estimations de FPS.
- [ ] Indiquer la fiabilité des résultats.

Phase 4 — Benchmark

- [ ] Créer une scène 3D.
- [ ] Mesurer les FPS pendant le test.
- [ ] Afficher les résultats.
- [ ] Documenter les limites des mesures.

Phase 5 — Optimisation

- [ ] Ajouter des conseils personnalisés.
- [ ] Développer des outils de diagnostic.
- [ ] Vérifier la sécurité des recommandations.
- [ ] Améliorer l'expérience utilisateur.

Phase 6 — Publication

- [ ] Publier le site.
- [ ] Documenter l'installation et l'utilisation.
- [ ] Tester sur plusieurs navigateurs.
- [ ] Accueillir les premières contributions.

🤝 Contribuer au projet

Boostly est conçu pour pouvoir évoluer grâce aux contributions de la communauté.

Tu peux contribuer en :

- 🐛 Signalant un bug.
- 💡 Proposant une nouvelle fonctionnalité.
- 🎮 Ajoutant des données de benchmarks fiables.
- 🎨 Améliorant l'interface.
- 📝 Corrigeant la documentation.
- 💻 Participant au développement.

Avant de publier des données de benchmarks, veille à vérifier leur origine, leurs conditions de mesure et leur licence.

📜 Licence

La licence du projet sera indiquée dans le fichier "LICENSE".

Une licence open source adaptée, comme la MIT, pourra être envisagée si tu souhaites autoriser largement la réutilisation et la modification du code.

Les licences des bibliothèques, images et bases de données externes devront également être respectées.

🎯 Notre objectif

Créer un outil gratuit, accessible et transparent qui aide les joueurs à comprendre leur matériel et à mieux évaluer les performances de leurs jeux.

Pas de promesses magiques. Pas de faux benchmarks. Des informations compréhensibles et des estimations honnêtes.

---

<div align="center">⚡ BOOSTLY — Know your hardware. Understand your performance.

Made with ❤️ by the open-source community.

</div>
