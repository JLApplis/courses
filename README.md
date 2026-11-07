# 🛒 Courses

**Liste de courses personnelle** : cases à cocher, suppression d'un geste, suggestions à partir des articles déjà achetés. Synchronisée entre le téléphone et l'ordinateur.

**[▶️ Ouvrir l'appli](https://jlapplis.github.io/courses/)**

![Licence](https://img.shields.io/badge/licence-GPL_v3-blue)

## Fonctionnement

- Connexion par e-mail et mot de passe (Firebase Authentication).
- Données stockées dans Firebase Firestore ; chaque compte ne voit que sa propre liste (voir `firestore.rules`).
- Fonctionne aussi sans réseau dans le magasin : les changements sont envoyés au retour de la connexion.
- Sur Android : Chrome ▸ ⋮ ▸ « Ajouter à l'écran d'accueil » pour l'ouvrir comme une appli.

## Licence

© 2026 Jluc — JLApplis. Distribué sous licence **GNU GPL v3** (voir `LICENSE.txt`).
