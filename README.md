# abc-notation-artifacts

Liste de petits outils pour aider à travailler un instrument ou à éditer ses partitions. 

## Chord change trainer
👉 [chord-change.html](chord-change.html) 

**Entrainement au changement d'accords pour ukulélé ou guitare. On voit le prochain accord pour se préparer, et on entend le métronome.**

Paramètres: 
* choix de l'instrument (défaut ukulélé)
* choix de la catégorie / Niveau des questions (Défaut Avancé et Intermédiaire)
* vitesse du tempo (défaut 80 bpm, mesure de 4 temps)
* Défilement aléatoire ou dans l'ordre (défaut aléatoire)
* durée de l'exercice (défaut boucle infinie)
* Mode Jour / Nuit

L'outil n'identifie pas si l'accord est bien joué ou non. 

Librairies utilisé: 
* pianosnake uke chord
* bootstrap

Code créé par IA (Gemini, je crois), et prompté par moi 😉
Licence: CC BY-NC 4.0

## Ear chord trainer
👉 [chord-ear-trainer.html](chord-ear-trainer.html)

**Entrainement à la reconnaissance d'accord. L'accord est joué sur deux mesure. La réponse est affichée avec les notes sur la portée, le nom des notes et le schéma d'accord pour ukulélé ou guitare. L'audio continue durant deux mesures pour bien assosier la réponse au son.**

Paramètres:
* choix de l'instrument pour le schéma d'accord
* catégorie / Niveau des questions
* durée des mesures pour la question et pour la réponse
* choix du tempo (défaut 100 bpm sur des mesures à 4 temps)
* afficher / Masquer le nom des notes
* durée de l'exercice (défaut: boucle infinie)
* Mode Jour / Nuit

Librairies utilisées: 
* pianosnake uke chord
* abcjs Paul Rosen
* bootstrap

Code créé par IA (Gemini), et prompté par moi 😉

Licence: CC BY-NC 4.0


## Grid creation
👉 [abc-grid.html](abc-grid.html)

**Création rapide d'un accompagnement à partir d'une liste ecrite d'accord (sous forme de grille écrite en texte). On tape la série d'accords et on obtient les accords sous forme de partition et d'audio. Possibilité de jouer en boucle.**

Paramètres:
* Différents mode de jeux de l'accompagnement
  * Boom chick (défaut)
  * Tango
  * Arpèges
* Mesure à 4 temps / 3 temps
* Mode Jour / Nuit


À faire:
* [ ] Autoriser les mesures composées de plusieurs accords.
* [ ] Autoriser les schémas personnalisés de rythme de l'accompagnement
* [ ] Tester le mode "chordgrid" pour afficher la grille
* [ ] Exporter l'abc transposé

Librairies utilisées: 
* abcjs Paul Rosen
* bootstrap

Code créé par IA (Gemini, je crois), et prompté par moi 😉

Licence: CC BY-NC 4.0


##  Abc editor player
👉 [abc-editor-player.html](abc-editor-player.html)

**Première version d'un éditeur abc notation. Visualisation de la partition et création de l'audio. Plus de paramètres sont disponibles en cliquant sur les "⁝" à la fin de la barre du player, notamment pour la transposition.**

Fonctionnalités:
* Visualisation de la partition
* Jeu de l'Audio
* Chargement / Export d'une bibliothèque de morceaux
* Renommer un morceau de la bibliothèque
* Transposition
* Augmentation du swing
* Jouer / Taire les accords d'accompagnement
* Jouer / Taire la mélodie
* Activer le métronome (rythme, nombre de mesures)
* Mode Jour / Nuit

À faire: 
* [ ] Ajouter les tablatures avec l'accordement
* [ ] Export en midi
* [ ] Amélioration de l'éditeur (propositions contextualisées)

Librairies utilisées: 
* abcjs Paul Rosen
* bootstrap

Code créé par IA (Gemini), et prompté par moi 😉

Licence: CC BY-NC 4.0

# Code source

Le code de ces outils est disponible sur Github:

 [https://github.com/fxpar/abc-notation-artifacts](https://github.com/fxpar/abc-notation-artifacts)

# Licence

 Shield: [![CC BY-NC 4.0][cc-by-nc-shield]][cc-by-nc]

This work is licensed under a
[Creative Commons Attribution-NonCommercial 4.0 International License][cc-by-nc].

[![CC BY-NC 4.0][cc-by-nc-image]][cc-by-nc]

[cc-by-nc]: https://creativecommons.org/licenses/by-nc/4.0/
[cc-by-nc-image]: https://licensebuttons.net/l/by-nc/4.0/88x31.png
[cc-by-nc-shield]: https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg