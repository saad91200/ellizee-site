# ELLIZÉE — site officiel

Site statique : `index.html` + dossier `media/`.

- Vidéos et images : objet `MEDIA` et tableau `VISUALS` dans le script de `index.html`.
- Projets (textes des pages projet) : tableau `PROJECTS`.
- Emplacements à compléter : `[LOGO]`, `[BOOKING_URL]`, `[SOCIAL]`, `[OG_IMAGE]`.
- Formulaire de contact : envoyé au CRM d'ELLIZÉE (`CRM_ENDPOINT` dans le script de `index.html`) ; chaque message crée un prospect dans le CRM.
- Aucun prix n'est affiché sur le site : tout se fait sur devis.

Déploiement automatique à chaque push sur `main` (Netlify ou Vercel, sans build).
