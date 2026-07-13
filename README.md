# Landing Page Standalone

Dossier contenant tous les fichiers nécessaires pour afficher la landing page de Keeper.

## Fichiers inclus

- **index.html** — Landing page principale (copie de `keeper-landing-v11_1.html`)
  - 100 % auto-contenue : CSS et SVG inlines
  - Aucune dépendance externe (polices auto-hébergées en base64)

- **privacy.html** — Politique de confidentialité
  - Liée depuis index.html
  - Également 100 % autonome

## Fichiers optionnels

- **og-image.png** — Image pour le partage social (1200×630 px)
  - Référencée dans les meta OpenGraph/Twitter
  - À créer si vous voulez que la landing se partage avec une image

## Utilisation

1. Ouvre `index.html` dans un navigateur
2. La page marche complètement hors-ligne (0 requête réseau)
3. Tous les formulaires (Formspree) et liens fonctionnent normalement

## Notes

- Le formulaire utilise Formspree (API externe pour les emails)
- Toute la mise en page est en cqw (container query width) — responsive automatique
