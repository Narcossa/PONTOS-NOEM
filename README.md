# NOEM — Site statique (GitHub Pages)

Projet minimal prêt à publier pour **NOEM**.

## Déploiement rapide (GitHub Pages)
1. Créez un repo `noem` sur votre compte GitHub.
2. Uploadez tous les fichiers de ce dossier à la racine du repo.
3. Allez dans **Settings → Pages** et sélectionnez **Deploy from a branch** puis `main` / `/root`.
4. L’URL sera : `https://&lt;votre-utilisateur&gt;.github.io/noem/`.
5. Modifiez `index.html` et `pages/*` avec vos contenus, et `assets/css/styles.css` pour le style.
6. (Optionnel) Si vous utilisez un domaine perso, ajoutez un fichier `CNAME` avec votre domaine.

## Structure
- `index.html` — Accueil
- `pages/services.html`, `pages/realisations.html`, `pages/equipe.html`, `pages/contact.html`
- `pages/mentions-legales.html`, `pages/espace-clients.html`, `pages/espace-collaborateurs.html`
- `assets/css/styles.css`, `assets/js/script.js`, `assets/img/` (favicon + placeholders)
- `404.html` (obligatoire pour GitHub Pages), `robots.txt`, `sitemap.xml`

## Astuces
- Pour les formulaires, GitHub Pages étant statique, utilisez : Netlify Forms, Formspree, Jotform (recommandé pour NOEM).
- Remplacez `site_url` dans les meta (og:*) si vous changez l’URL.
- Les images d’exemple sont des placeholders — remplacez par vos photos.

Bon build ✌️
