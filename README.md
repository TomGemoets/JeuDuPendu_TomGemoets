# JeuDuPendu_TomGemoets
# Jeu du Pendu en Python

Ce projet est une implémentation simple du célèbre **jeu du pendu** en Python. Le joueur doit deviner un mot lettre par lettre avant d’épuiser ses essais.

---

## Fonctionnement

- Le joueur choisit d'utiliser un fichier de mots personnalisé ou le fichier par défaut `mots_pendu.txt`.
- Un mot est choisi aléatoirement dans la liste.
- Le mot est affiché sous forme de tirets `_ _ _` pour cacher les lettres.
- Le joueur entre une lettre à chaque tour :
  - Si la lettre est correcte, elle remplace les tirets.
  - Sinon, il perd une vie.
- À la dernière vie, le joueur peut proposer le mot entier pour gagner.
- À la fin, il peut rejouer ou quitter.

---

## Fichiers attendus

- `pendu.py` (le script principal)
- `mots_pendu.txt` (fichier de mots par défaut, un mot par ligne)

Tu peux aussi utiliser ton propre fichier `.txt` contenant une liste de mots (un mot par ligne).

---

## Lancer le jeu

Assure-toi d’avoir Python installé (version 3.6 ou supérieure), puis exécute :

```bash
python pendu.py
