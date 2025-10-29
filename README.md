# 📘 Mon Projet Git

## 🧩 Description
Ce projet est un exemple pour apprendre et pratiquer les commandes Git de base :  
configuration, branches, push/pull, merge et résolution de conflits.

## ⚙️ Commandes Git principales
```bash
# Initialiser un dépôt local
git init

# Configurer l'utilisateur
git config --global user.name "Ton Nom"
git config --global user.email "ton.email@example.com"

# Ajouter un dépôt distant
git remote add origin https://github.com/utilisateur/mon-projet.git

# Créer une branche
git branch feature-xyz

# Se déplacer sur une branche
git checkout feature-xyz

# Fusionner une branche
git merge feature-xyz

# Envoyer les modifications
git push -u origin main

# Récupérer les mises à jour de l’équipe
git pull
