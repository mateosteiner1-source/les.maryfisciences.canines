# Les Maryfisciences Canines — site web

Site vitrine statique prêt à être envoyé sur GitHub et déployé sur Vercel.

## Contenu
- Accueil / présentation
- Éducation canine
- Accompagnement comportemental
- Socialisation et vie quotidienne
- Conseils personnalisés
- Galerie avec les photos fournies
- Formulaire de contact par messagerie
- Design responsive mobile / tablette / ordinateur
- Logo et favicon intégrés

## Modifier les coordonnées
Ouvrir `config.js` et renseigner :
- `email`
- `phone`
- `location`
- `instagram`
- `facebook`

Le formulaire utilise l'adresse `email` pour ouvrir le logiciel de messagerie du visiteur.

## GitHub
1. Créer un nouveau dépôt GitHub.
2. Décompresser le ZIP.
3. Envoyer tous les fichiers du dossier à la racine du dépôt.
4. Aucun `npm install` n'est nécessaire.

## Vercel
1. Se connecter à Vercel.
2. `Add New Project` → importer le dépôt GitHub.
3. Framework : laisser la détection automatique ou choisir `Other` / site statique.
4. Build Command : aucune.
5. Output Directory : `.` (racine).
6. Déployer.

Le site ne dépend d'aucune base de données ni serveur.

## Pages juridiques ajoutées
- `mentions-legales.html`
- `politique-confidentialite.html`
- `cgv.html`
- `cgu.html`
- `politique-cookies.html`

Les pages contiennent des emplacements « À compléter » lorsque les informations juridiques exactes n'étaient pas disponibles. Elles doivent être vérifiées et complétées avant publication définitive.
