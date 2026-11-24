# Cure Quest

Appli de suivi de cure façon jeu vidéo : chaque jour de cure est un niveau à valider en prenant sa dose.

## Fonctionnalités

- Carte de niveaux (21 jours par défaut, réglable de 3 à 120), avec un boss final le dernier jour
- Une ou plusieurs prises par jour, avec un rappel à l'heure de chaque prise
- XP, rangs (Apprenti → Légende), série de jours d'affilée et trophées
- Rappel de recommande à 5 niveaux de la fin, puis bouton « Commander ma prochaine cure » à la fin de la cure
- Mode démo « jour suivant » pour faire des présentations

## Utilisation

Ouvrir `index.html` dans un navigateur. La progression est enregistrée dans le navigateur (localStorage).

## Limites du prototype

- Les rappels s'affichent seulement quand la page est ouverte : pour de vraies notifications push, il faut une version installable (PWA ou appli Lovable + Supabase).
- Le bouton « Commander ma prochaine cure » doit encore être relié à un lien de commande.
