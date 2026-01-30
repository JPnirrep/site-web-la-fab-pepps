---
description: Vérification visuelle du site KLEIA-UP sur GitHub Pages
---

# Workflow : Vérification visuelle du site

## Objectif
Pousser les modifications sur GitHub puis ouvrir le site déployé pour vérification visuelle, sans passer par un serveur localhost.

## Étapes

// turbo-all

1. Vérifier s'il y a des modifications à committer :
```powershell
git status
```

2. Si des modifications existent, les ajouter :
```powershell
git add .
```

3. Créer un commit avec un message descriptif :
```powershell
git commit -m "🔄 Update pour vérification visuelle"
```

4. Pousser les modifications sur GitHub :
```powershell
git push
```

5. Attendre quelques secondes pour que GitHub Pages se mette à jour (environ 30-60 secondes).

6. Ouvrir Chrome avec le site GitHub Pages :
```powershell
start chrome "https://jpnirrep.github.io/site-web-kleia-up/"
```

## Notes
- Les étapes 2-4 sont ignorées automatiquement s'il n'y a pas de modifications
- Le déploiement GitHub Pages peut prendre 30-60 secondes après un push
- Le site affiché est la version déployée sur GitHub Pages
- Répertoire de travail : `c:\Users\JP\Documents\GitHub\site-web-kleia-up\site-web-kleia-up`
