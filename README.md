# Planner Voile

Planificateur de route voile : outil web statique (HTML/CSS/JS, aucune étape de
build) basé sur [Leaflet](https://leafletjs.com/) pour préparer une sortie ou une
traversée à la voile.

## Fonctionnalités

- Placement de waypoints sur une carte interactive
- Étapes gérées dans un panneau latéral gauche (date/heure de départ par étape)
- Nommage automatique des étapes (lieu de départ - lieu d'arrivée) par géocodage inverse
- Calcul de distance, cap et estimation de temps/arrivée en fonction de la vitesse
- Annuler (Ctrl+Z) la dernière action, quel que soit son type
- Panneau bas redimensionnable (glisser la barre au-dessus) pour ajuster l'espace carte/tableau
- Couche vent (Open-Meteo) en grille (280 barbules météo) sur toute la zone visible, avec un curseur pour animer la prévision heure par heure de la date de l'étape active ; requêtes mises en cache pour éviter les limites de débit lors du zoom/pan
- Export de la route au format GPX (avec description par étape) pour un GPS ou une app de navigation
- Sauvegarde/chargement d'une session au format JSON

## Utiliser l'outil

Aucune installation requise : ouvrez simplement `index.html` dans un navigateur,
en local ou via l'URL GitHub Pages du dépôt.
