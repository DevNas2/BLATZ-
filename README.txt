BLATZ MOBILE — VERSION PWA

CONTENU
- index.html : application mobile et logique Supabase
- manifest.webmanifest : déclaration installable PWA
- sw.js : cache de base pour la coque de l'application
- icon.svg : icône de l'application

INSTALLATION / MISE EN LIGNE
1. Remplace les fichiers de ton dépôt GitHub Pages par ceux de ce dossier.
2. Garde les quatre fichiers à la racine du site.
3. Active GitHub Pages si ce n'est pas déjà fait.
4. Ouvre l'adresse HTTPS du site sur Android avec Chrome.
5. Menu ⋮ > Installer l'application / Ajouter à l'écran d'accueil.

IMPORTANT
- Supabase utilise la même URL, la même clé publique et la table `groups` du site d'origine.
- Le formulaire insère les colonnes name, category, link, description, image et clicks.
- Vérifie dans Supabase que les règles RLS autorisent les insertions publiques nécessaires.
- Les favoris et l'historique sont stockés localement sur l'appareil.
- Les publicités Adsterra ne sont pas intégrées dans cette première version mobile. Les emplacements publicitaires sont réservés dans l'interface.
- Une PWA doit être servie en HTTPS (ou localhost) pour l'installation et le service worker.
