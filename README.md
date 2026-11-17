# Mes repas — Celine & Manu

Planificateur de repas en batch cooking (site statique, PWA) avec deux profils :
**Celine** (perte de poids, environ 1400–1450 kcal et 50 g de glucides par jour, sans œuf, gluten ni protéines de lait) et **Manu** (sportif, SaintéLyon le 28/11/2026).

- Site en ligne : https://repas-celine.netlify.app
- Un seul fichier `index.html` (JavaScript intégré), `sw.js` (cache hors ligne), `manifest.webmanifest` et les icônes.
- Les données (repas cochés, réglages, recettes modifiées) restent dans le navigateur de chaque personne (localStorage), séparées par profil.
- Pour tester en local : ouvrir `index.html`, ou lancer `python3 -m http.server`.
