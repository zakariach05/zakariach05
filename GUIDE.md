# 🚀 Guide d'installation — Profil GitHub Terminal Style

## Étape 1 : Créer le repo
1. Crée un nouveau repo public nommé **exactement** comme ton pseudo GitHub : `zakariach05`
2. Initialise-le avec un README.md

## Étape 2 : Copier les fichiers
Copie le contenu de `README.md` fourni dans ton README.

## Étape 3 : Activer les Workflows
1. Va dans l'onglet **Actions** de ton repo
2. Clique sur **"I understand my workflows, go ahead and enable them"**
3. Les workflows vont se lancer automatiquement

## Étape 4 : Générer le GIF ASCII (l'animation clé de la vidéo)

### Méthode A — En ligne (simple)
Va sur https://ezgif.com/maker-ascii ou https://www.asciiart.eu/image-to-ascii
- Upload ta photo de profil
- Télécharge le GIF
- Renomme-le `ascii-avatar.gif`
- Upload dans ton repo (dossier `assets/`)
- Remplace dans le README :
```markdown
<img src="assets/ascii-avatar.gif" width="250" />
```

### Méthode B — Terminal style complet (comme la vidéo)
Utilise l'outil Python :
```bash
pip install github-readme-terminal
github-readme-terminal --username zakariach05 --theme tokyonight --output assets/terminal.gif
```

### Méthode C — Neofetch dynamique (pas de GIF à gérer)
Ajoute simplement cette URL dans ton README :
```markdown
<img src="https://neofetch-profile.vercel.app/api?username=zakariach05&theme=github-dark" />
```

## Étape 5 : Personnaliser
- Modifie les liens LinkedIn/Portfolio dans les badges
- Ajuste les couleurs (thème radical avec rouge/jaune comme tu as déjà)
- Ajoute tes vrais repos dans la section Projects

## 🎨 Résultat attendu
Ton profil ressemblera à ça :
- En-tête avec bannière ondulée
- Terminal ASCII animé à gauche + infos neofetch à droite
- Graphique de contributions en temps réel
- Snake animation qui mange tes contributions
- Stats GitHub stylisées

## ⚠️ Important
- Le repo **DOIT** s'appeler exactement `zakariach05` pour apparaître sur ton profil
- Les GitHub Actions nécessitent un token — il est créé automatiquement (`GITHUB_TOKEN`)
- Le snake met ~2 minutes à se générer la première fois
