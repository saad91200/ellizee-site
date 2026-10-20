# ELLIZÉE — site officiel

Site statique : `index.html` + dossier `media/`.

- Vidéos et images : objet `MEDIA` et tableau `VISUALS` dans le script de `index.html`.
- Projets (textes des pages projet) : tableau `PROJECTS`.
- Emplacements à compléter : `[LOGO]`, `[BOOKING_URL]`, `[SOCIAL]`, `[OG_IMAGE]`.
- Formulaire de contact : envoyé au CRM d'ELLIZÉE Studio (`CRM_ENDPOINT` dans le script de `index.html`) ; chaque message crée un prospect « À contacter ».

Déploiement automatique à chaque push sur `main` (Netlify ou Vercel, sans build).
