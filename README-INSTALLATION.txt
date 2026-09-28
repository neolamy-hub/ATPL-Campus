ATPL CAMPUS V6 — INSTALLATION PWA

1) Mettre tout le contenu de ce dossier sur un hébergement HTTPS statique.
   Exemples : GitHub Pages, Cloudflare Pages, Netlify ou Vercel.

2) Ouvrir ensuite l'adresse HTTPS de l'application sur le téléphone/tablette.

IPHONE / IPAD
- Ouvrir l'adresse dans Safari.
- Toucher Partager.
- Choisir « Sur l’écran d’accueil ».
- Valider « Ajouter ».

ANDROID
- Ouvrir l'adresse dans Chrome.
- Le bouton « Installer ATPL Campus » peut apparaître automatiquement.
- Sinon : menu ⋮ > Installer l'application / Ajouter à l'écran d'accueil.

HORS CONNEXION
- Ouvrir au moins une fois l'application avec Internet après mise en ligne.
- Le coeur de l'application et les cours sont ensuite mis en cache.
- Les fonctions nécessitant une API externe (traduction/questions publiques) peuvent rester limitées hors connexion.

IMPORTANT
- Un simple fichier index.html ouvert depuis l'application Fichiers ne permet pas un service worker/PWA complet.
- La PWA doit être servie via HTTPS (localhost est l'exception pour le développement).
