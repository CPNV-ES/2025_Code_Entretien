# Test Technique - Entretien Développeur 2025

## 🧠 Projet : MindMap CLI

Bienvenue dans ce test technique. Le but de cet exercice est d’évaluer ta capacité à modéliser un problème, structurer ton code, interagir via une interface en ligne de commande et persister des données de manière simple mais robuste.

---

## 🌟 Objectif

Tu dois développer un outil **en ligne de commande (CLI)** permettant de créer, gérer et sauvegarder des **cartes mentales** (mindmaps). Une carte mentale est une structure arborescente contenant des idées (nœuds) pouvant elles-mêmes contenir des sous-idées.

---

## ✅ Fonctionnalités minimales

- [ ] **Créer une nouvelle carte** avec un titre racine
- [ ] **Ajouter un nœud** à un autre nœud (idée fille) max. 3 niveaux titre compris.
- [ ] **Lister** une carte sous forme d’arborescence en CLI
- [ ] **Supprimer** un nœud et tous ses enfants
- [ ] **Sauvegarder/charger** une carte depuis un fichier (JSON ou YAML)
- [ ] **Rechercher** un nœud par nom et afficher son chemin

---

## 🧪 Fonctionnalités bonus (non obligatoires)

- ajoutes 2 ou 3 autres fonctionnalités qui te semble pertinentes.

---

## 🧰 Contraintes techniques

- Tu peux utiliser le langage de ton choix : **Python**, **Java**, **Rust**, **Go**, **Node.js**, etc.
- Le projet doit être **exécutable en ligne de commande** sans interface graphique
- Toute dépendance doit être installable via un gestionnaire de paquets (`pip`, `npm`, etc.)
- Inclure un fichier `README.md` clair, avec instructions pour :
  - Installer le projet
  - Lancer l’application
  - Utiliser les commandes principales

---

## 📁 Structure attendue (exemple)

```
mindmap-cli/
├── main.py
├── mindmap/
│   ├── models.py
│   ├── manager.py
│   └── storage.py
├── data/
│   └── ma_carte.json
└── README.md
```

Tu peux structurer autrement si tu le préfères, du moment que c’est clair.

---

## 📝 Consignes

- Tu as **4 à 8 heures** maximum pour réaliser ce projet.
- Pousse ton projet sur un dépôt **GitHub public** et envoie-nous le lien.
- Le code doit être propre, structuré et lisible. Les commentaires et les tests sont un plus appréciés.
- Ton README doit contenir un exemple d’utilisation (copier/coller de l'affichage CLI).

---

## 🏁 Bonne chance !
