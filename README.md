# Habitudes 🌸

Petite web-app minimaliste (couleurs pastel) pour suivre ses bonnes habitudes sur iPhone.

- **À faire** : trois blocs — *Aujourd'hui*, *Cette semaine*, *Ce mois-ci*.
- Récurrences libres : « X fois tous les N jours / semaines / mois »
  (ex. 2×/jour, 2×/semaine, 1× tous les 2 mois, 1× tous les 3 mois…).
- Une tâche cochée reste cochée jusqu'au début de son prochain cycle
  (minuit, lundi, 1er du mois, ou tous les N mois à partir de la date de début choisie).
- **Jauge du mois** (« 10 sur 15 ») en haut de la page et dans le bilan, avec un repère pour le jour actuel.
- **Bilan du mois** : ce qui a été fait pendant le mois en cours (remis à zéro chaque mois, pas d'historique).
- Bouton en haut à droite : ajouter / modifier / supprimer les habitudes, sauvegarde et restauration (fichier JSON).
- Fonctionne hors-ligne, données stockées sur le téléphone.

## Installer sur iPhone

1. Sur GitHub : **Settings → Pages → Build and deployment** : Source « Deploy from a branch »,
   choisir la branche (ex. `main`) et le dossier `/ (root)`, puis **Save**.
2. Ouvrir l'URL donnée (`https://clairegrbd-cmyk.github.io/Tracker-2/`) dans **Safari** sur l'iPhone.
3. Bouton **Partager** → **Sur l'écran d'accueil**. L'app s'ouvre ensuite en plein écran comme une vraie app.

Aucune dépendance, aucun build : tout est dans `index.html`.
