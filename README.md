# Portfolio — Med Maamoun MAROUANI (version 2ADIS : automatisation industrielle)

Site statique (HTML, CSS, JavaScript), sans étape de compilation.

## Contenu
- `index.html` : tout le site (styles et scripts inclus).
- `assets/images/` : photographies, captures, schémas EPLAN et nouvelle couverture `hero-industrial-automation.jpg`.
- `assets/videos/` : deux vidéos de démonstration.
- `assets/My_cv.pdf`, `assets/EPLAN_Electrical_Design_Portfolio.pdf`, `assets/SYSTELEM_Embossing_Post_EPLAN_Case_Study.pdf` : documents conservés tels quels.

## Tester en local
Ouvrir `index.html` dans un navigateur. Les polices (Google Fonts) demandent une connexion ; sans connexion, le site utilise des polices système.

## Publier sur GitHub Pages
1. Ouvrir le dépôt du portfolio (`my-portfolio`) sur GitHub.
2. Supprimer l'ancien contenu, puis y déposer `index.html` et le dossier `assets` de ce ZIP (glisser-déposer dans « Add file → Upload files », ou `git add . && git commit && git push`).
3. Dans **Settings → Pages**, vérifier : Source = « Deploy from a branch », branche `main`, dossier `/ (root)`.
4. Attendre 1 à 2 minutes : le site est publié sur https://mohamedmaamounmarouani-lgtm.github.io/my-portfolio/

## À vérifier après publication
- Les 3 PDF s'ouvrent et se téléchargent depuis la section « CV et documents techniques ».
- Les deux vidéos se lisent (elles ne se chargent qu'au clic).
- Si l'adresse du dépôt change, mettre à jour les liens `canonical`, `og:url` et `og:image` dans l'en-tête de `index.html`.
