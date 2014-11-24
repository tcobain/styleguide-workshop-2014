WORKSHOP WS48 ERACOM – Styleguide web
=====================================

## Intervenants
- Marc Friederich – Software designer et fondateur / Antistatique.net
- Yann Gouffon – Frontend developer / Antistatique.net
- Toni Fisler – Frontend developer / Antistatique.net

## À propos du workshop
- Classe : CM421 (cm421@eracom.ch)
- Salle : 509
- Maitre principal : Gregorio Soumas, salle 415 gregorio.soumas@eracom.ch
- Doyenne : Michaela Varin, salle 415 – michaela.varin@eracom.ch – 021 316 01 13
- Évaluation : Chaque étudiant est noté individuellement sur son travail par les intervenants.

## Buts du workshop
- Comprendre les avantages des styleguides web dynamiques
- Connaitre les processus de projet comprenant la mise en place d'un styleguide
- Appréhender les outils frontend dans les projets à large échelle
- Apprendre à travailler à plusieurs sur les mêmes fichiers
- Maitriser les notions de modularité du design web (Atomic design)
- Savoir estimer les besoins en ressources, expérimenter, mesurer et adapter.

## Moyen
- Mettre en pratique dans un travail collaboratif la mise en place d'un styleguide
- Décliner les éléments du styleguide dans les vues d'une application web

## Pré-requis
- Maitriser son environnemnt de travail
- Maitriser les langages HTML/CSS
- Connaissance de Bootstrap 3

## Participants
| Prénom, Nom | Groupe |
| ------------ |:-----:|
| Maya Beeler | A |
| Tanaquil Berger | A |
| Benjamin Régis | A |
| Laura Gardel | B |
| Alexine Bruttin | B |
| Raphaël Carruzzo | B |
| Julian Zimmermann | B |
| Eva Hugi | C |
| Joana DaRocha | C |
| Kilian Zucconi | C |
| Chloé Jelk | D |
| Taylor Diggelmann | D |
| Lauren Thiel | D |
| Emmanuelle Kohli | E |
| Gawen Michaudet | E |
| Yohan Nieto | E |

## Groupes et sujet
| Groupe | Organisation | Documents Corporate |
| ------ | ------------ | ------------------- |
| A | [Handicap International]{http://www.handicap-international.ch/fr/} | http://www.handicap-international.org.uk/Resources/Handicap%20International/PDF%20Documents/HI%20Associations/RA2013-FED-en.PDF |
| B | [Human Rights Watch]{http://www.hrw.org/} | http://www.hrw.org/annual-report |
| C | [World Organisation Against Torture]{http://www.omct.org/} | |
| D | [Médecins Sans Frontières]{http://www.msf.ch/} |  |
| E | [UNICEF]{http://www.unicef.org/} | http://www.unicef.org/iran/Brand_Tool_Kit.pdf |

## Projet
Réalisation d'un styleguide web selon le process enseigné (Hologram, Bootstrap, Gulp, Holostrap, Cortana, twig). Le styleguide doit être mis en ligne sur une gh-pages Github.

## Donnée
- Création d'un styleguide web dynamique (généré automatiquement à partir du code CSS) pour une ONG
- Adaptation de l'identité de marque au médias digitaux (web, mobile)
- Décliner tous les éléments/composants de bootstrap à l'identité de l'organisation
- Réaliser 4 pages d'exemples [Homepage, Faire un don, Nos actions, Multimédia] contenant sur chaque page [Header, sélection de langue, menu, champ de recherche, footer]

## Attentes et critères d'évaluation
L'évaluation est basée sur les critères ci-après. Une note est attribué pour le groupe, une autre de manière indivicuelle, la moyenne est la note finale.

### Note globale du groupe (1/2)
| Notion évaluée | % |
| ------------ | -----:|
| Concept Atomic Design – Compréhention et mise en pratique du concept, découpage des éléments du styleguide en Atomes, molécules, ogranismes, templates, pages | 15% |
| Styleguide en ligne – Mise en ligne du styleguide sur une gh-pages | 10% |
| Découpage et qualité du SASS/CSS – no-Nesting, utilisation des mixins, noms des classes et variables | 10% |
| Création des pages d'exemple – Démonstration de l'utilisation des éléments graphique pour réaliser les composants | 10% |
| Structure du styleguide – Division et structure des chapitres et catégories | 5% |
| Concept de design et documentation – Qualité des pages de présentation des principes de design et d'intéraction | 10%
| Cohésion, collaboration – Répartition des tâches et collaboration du groupe | 15% |
| Aspect visuel du résultat – Respect de la charte graphique et de l'identité de marque | 10% |
| Ergonomie et utilisabilité – Respect des concepts et bonnes pratiques en terme de UX design | 10% |
| Respect des délais – Respect du planning délivré en phase 1 | 5% |

### Critères d'évaluation personnelle (1/2)
| Notion évaluée | % |
| ------------ | -----:|
| Utilisation de GIT – Nombre et contenu des commits dans le projet | 10% |
| Maitrise de l'atomic design – Dans les contenu commité | 10% |
| Exercice théorique – Résultat des réponses au QCM | 50% |
| Implication – Investissement dans le projet de groupe | 30% |

## Théorie (Sujets abordés)

### Modular first
- On atomic design : http://bradfrost.com/blog/post/atomic-web-design/
- Slides : http://yago.github.io/talks/topics/modular-first.html#/

### Large scale frontend project
- From Harry Roberts : https://www.youtube.com/watch?v=ldx4ZFxMEeo&feature=youtu.be et les slides https://speakerdeck.com/csswizardry/normalising-designs-for-better-quality-css et http://vimeo.com/67544231 et les slides https://speakerdeck.com/csswizardry/architecting-scalable-css
- BRM concept http://bem.info/
- SMACSS https://smacss.com/
- Résumé : http://clubmate.fi/oocss-acss-bem-smacss-what-are-they-what-should-i-use/ et http://mattstauffer.co/blog/organizing-css-oocss-smacss-and-bem
- CSS Frameworks – just type https://www.google.ch/search?q=css+framework trendy http://codegeekz.com/css-frameworks-2014/

### DRY concept
- http://en.wikipedia.org/wiki/Don%27t_repeat_yourself

### Technical dept concept
- Résumé et définitions http://stackoverflow.com/questions/1258775/what-is-technical-debt
- Further reading : https://medium.com/@joaomilho/festina-lente-e29070811b84

### Don't fear your terminal
- http://www.ee.surrey.ac.uk/Teaching/Unix/index.html
- http://lifehacker.com/5633909/who-needs-a-mouse-learn-to-use-the-command-line-for-almost-anything
- http://mally.stanford.edu/~sr/computing/basic-unix.html
- http://blog.teamtreehouse.com/introduction-to-the-mac-os-x-command-line
- "fun" and OSX oriented http://computers.tutsplus.com/tutorials/10-terminal-commands-that-every-mac-user-should-know--mac-4825

### GIT is your friend
- https://try.github.io/levels/1/challenges/1
- http://rogerdudler.github.io/git-guide/
- http://danielkummer.github.io/git-flow-cheatsheet/

### Bootstrap
- http://getbootstrap.com

### NPM
- https://www.npmjs.org/

### Gulp
- http://gulpjs.com/

### Yeoman
- http://yeoman.io/

### Bower
- http://bower.io/

### Hologram
- http://trulia.github.io/hologram/

### Cortana
- https://github.com/Yago/Cortana

### Holostrap
- https://github.com/Yago/Holostrap
