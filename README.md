# Cure Quest

Appli de suivi de cure façon jeu vidéo : chaque jour de cure est un niveau à valider en prenant sa dose.

## Fonctionnalités

- Choix du pack Wake Up S&You : Énergie, Pur Form, Pur Form+, Pur Puissance, Pur Puissance+, Pur Form Intense+, Pur Puissance Intense+, ou une cure libre
- Le nombre de niveaux suit la durée du pack (30 ou 60 jours), avec un boss final le dernier jour
- Prises du matin, du midi et du soir selon les produits du pack, avec la dose de chaque produit et un rappel à l'heure choisie
- Doses reprises des fiches de la boutique Wake Up (novembre 2026) : Phycocyanine 10 ml, Vitamine C liposomale 5 ml avant le repas, Oméga 3 2 capsules au dîner, Curcu8-Q10 10 ml après le repas
- Une partie de morpion contre l'ordinateur débloquée à chaque niveau validé (victoire +30 XP, nul +10 XP)
- XP, rangs (Apprenti → Légende), série de jours d'affilée et trophées
- Rappel de recommande à 5 niveaux de la fin, puis bouton « Commander ma prochaine cure » à la fin de la cure
- Mode démo « jour suivant » pour faire des présentations

## Utilisation

Ouvrir `index.html` dans un navigateur. La progression est enregistrée dans le navigateur (localStorage).

## Limites du prototype

- Les rappels s'affichent seulement quand la page est ouverte : pour de vraies notifications push, il faut une version installable (PWA ou appli Lovable + Supabase).
- Le bouton de commande pointe vers la fiche du pack sur la boutique Wake Up ; on peut mettre son propre lien distributeur dans les réglages.
