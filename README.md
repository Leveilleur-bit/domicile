# Domicile — Carnet d'entretien
## Installation sur GitHub Pages

### Etape 1 — Creer un compte GitHub
Allez sur https://github.com et creez un compte gratuit si vous n'en avez pas.

### Etape 2 — Creer un depot
1. Cliquez sur "New repository" (bouton vert)
2. Nommez-le `domicile` (ou ce que vous voulez)
3. Cochez "Public"
4. Cliquez "Create repository"

### Etape 3 — Uploader les fichiers
Dans votre nouveau depot, cliquez "uploading an existing file" et glissez-deposez ces 3 fichiers :
- `index.html`
- `manifest.json`
- `sw.js`

> Note : les icones icon-192.png et icon-512.png sont optionnelles.
> Sans elles, l'app fonctionnera mais sans icone personnalisee.

### Etape 4 — Activer GitHub Pages
1. Allez dans "Settings" de votre depot
2. Dans le menu gauche, cliquez "Pages"
3. Sous "Source", selectionnez "Deploy from a branch"
4. Choisissez la branche "main" et le dossier "/ (root)"
5. Cliquez "Save"

### Etape 5 — Acceder a votre app
Apres 1-2 minutes, votre app sera disponible a l'adresse :
`https://VOTRE-NOM.github.io/domicile/`

### Etape 6 — Installer sur votre telephone
**Android (Chrome) :**
1. Ouvrez l'URL dans Chrome
2. Menu (3 points) > "Ajouter a l'ecran d'accueil"
3. L'icone apparait sur votre ecran d'accueil

**iPhone (Safari) :**
1. Ouvrez l'URL dans Safari
2. Bouton Partager > "Sur l'ecran d'accueil"
3. L'icone apparait sur votre ecran d'accueil

---

## Mise a jour de l'app
Pour mettre a jour, re-uploadez simplement le fichier `index.html` modifie dans votre depot GitHub.
Les visiteurs verront la nouvelle version au prochain chargement.

## Donnees
Les donnees restent dans le navigateur (localStorage).
Utilisez le bouton "Exporter" dans l'app pour sauvegarder vos donnees en JSON.
