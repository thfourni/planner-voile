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
- Couche vent (Open-Meteo) en grille (280 barbules météo) sur la zone visible, avec un curseur pour animer la prévision heure par heure de la date de l'étape active ; chargement à la demande (bouton) au pan/zoom + cache persistant (`localStorage`, 45 min) pour éviter les 429
- Export de la route au format GPX (avec description par étape) pour un GPS ou une app de navigation
- Sauvegarde/chargement d'une session au format JSON
- Lien de partage : encode tout le voyage dans l'URL (`#data=...`, jamais envoyé au serveur), copié en un clic ; ouvrir le lien recharge le voyage complet (étapes, dates, vitesse) et recadre la carte dessus

## Utiliser l'outil

Aucune installation requise : ouvrez simplement `index.html` dans un navigateur,
en local ou via l'URL GitHub Pages du dépôt.
