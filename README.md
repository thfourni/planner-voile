# Planner Voile

Planificateur de route voile : outil web statique (HTML/CSS/JS, aucune étape de
build) basé sur [Leaflet](https://leafletjs.com/) pour préparer une sortie ou une
traversée à la voile.

## Fonctionnalités

- Placement de waypoints sur une carte interactive
- Organisation de la route en étapes (date/heure de départ par étape)
- Nommage automatique des étapes (lieu de départ - lieu d'arrivée) par géocodage inverse
- Calcul de distance, cap et estimation de temps/arrivée en fonction de la vitesse
- Couche vent (Open-Meteo) à la date/heure de départ de l'étape active
- Export de la route au format GPX (avec description par étape) pour un GPS ou une app de navigation
- Sauvegarde/chargement d'une session au format JSON

## Utiliser l'outil

Aucune installation requise : ouvrez simplement `index.html` dans un navigateur,
en local ou via l'URL GitHub Pages du dépôt.
