# 🚀 GitHub Actions — Python CI

![Python](https://img.shields.io/badge/Python-3.12-3776AB?logo=python&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-CI-2088FF?logo=githubactions&logoColor=white)
![Pytest](https://img.shields.io/badge/Pytest-Tests-0A9EDC?logo=pytest&logoColor=white)

## 📌 Description

Ce projet est un mini-laboratoire DevOps permettant de découvrir la **CI (Continuous Integration)** avec **GitHub Actions**.

L'objectif est de mettre en place une automatisation simple permettant de tester automatiquement une application Python à chaque modification du projet.

À chaque `push` sur la branche `main`, GitHub Actions :

1. récupère le projet ;
2. démarre un environnement Ubuntu ;
3. installe Python 3.12 ;
4. installe les dépendances ;
5. exécute automatiquement les tests avec `pytest`.

---

## 🎯 Objectif du projet

Comprendre les bases d'une pipeline CI/CD et apprendre à automatiser les tests d'une application Python avec GitHub Actions.

```text
Développeur
     │
     │ git push
     ▼
   GitHub
     │
     ▼
GitHub Actions
     │
     ▼
Ubuntu Runner
     │
     ├── Installer Python
     │
     ├── Installer les dépendances
     │
     └── Lancer les tests
              │
        ┌─────┴─────┐
        ▼           ▼
       ✅            ❌
     Success       Failed






💻 Installation locale
1. Cloner le projet
git clone https://github.com/cis-debug/github-actions-python-ci.git
2. Entrer dans le projet
cd github-actions-python-ci
3. Installer les dépendances
python3 -m pip install -r requirements.txt
4. Lancer les tests
python3 -m pytest
5. Lancer l'application
python3 app.py

Résultat attendu :

================================
      PYTHON CI/CD PROJECT
================================

2 + 3 = 5
4 × 5 = 20
Is 10 even? True



🧠 Compétences développées
Git
GitHub
GitHub Actions
CI — Continuous Integration
Python
pytest
YAML
automatisation des tests
workflows CI/CD
Linux / Ubuntu
gestion des erreurs dans une pipeline


Cette automatisation permet de détecter rapidement les erreurs avant de poursuivre vers les étapes suivantes d'un processus CI/CD.


👩🏾‍💻 Auteur

Cisse Ndeye

Ingénieure DevOps / Systèmes & Réseaux / Cybersécurité
Data & Programmation

GitHub : https://github.com/cis-debug


⭐ Projet réalisé dans le cadre de ma pratique DevOps : Linux, Python, Docker, Git, GitHub Actions et automatisation.
