# 🎮 Minesweeper Game - 3 Versions

Un projet complet du jeu classique Minesweeper avec trois implémentations différentes, incluant une version avec Agent IA.

## 📋 Table des matières

- [Aperçu](#aperçu)
- [Les 3 Versions](#les-3-versions)
- [Installation](#installation)
- [Utilisation](#utilisation)
- [Structure du Projet](#structure-du-projet)
- [Caractéristiques](#caractéristiques)
- [Technologies](#technologies)
- [Licence](#licence)

## 🎯 Aperçu

Ce projet propose trois implémentations du jeu Minesweeper :

1. **Version Basique** : Interface console simple et directe
2. **Version Intermédiaire** : Interface web interactive avec graphiques
3. **Version avec Agent IA** : Agent intelligent capable de jouer automatiquement

Parfait pour apprendre les algorithmes de jeu, l'IA, et les interfaces utilisateur !

## 🎮 Les 3 Versions

### Version 1️⃣ : Basique (Console)

- Interface texte simple
- Jeu jouable en ligne de commande
- Idéale pour comprendre la logique du jeu
- **Dossier** : `version-basique/`

**Fonctionnalités :**
- Plateau de jeu configurable
- Nombre de mines ajustable
- Système de révélation des cases
- Détection des victoires/défaites

### Version 2️⃣ : Intermédiaire (Web UI)

- Interface web interactive et conviviale
- Graphiques et animations
- Gestion des difficultés (facile, moyen, difficile)
- **Dossier** : `version-intermediaire/`

**Fonctionnalités :**
- Plateau visuel avec des boutons cliquables
- Compteur de mines
- Minuteur de jeu
- Statistiques de jeu
- Réinitialisation du jeu

### Version 3️⃣ : Agent IA

- Agent IA capable de jouer automatiquement
- Algorithmes de résolution intelligents
- Mode spectateur pour observer l'IA
- **Dossier** : `version-ia/`

**Fonctionnalités :**
- Algorithme de révélation intelligente
- Analyse logique des cases
- Mode apprentissage
- Statistiques de performance de l'IA

## 📦 Installation

### Prérequis

- Node.js (v14+) ou Python (v3.8+) selon la version
- npm ou yarn (pour les versions JavaScript)

### Clone du dépôt

```bash
git clone https://github.com/hairiesolaimana-stack/minesweeper-game.git
cd minesweeper-game
```

### Installation des dépendances

**Pour les versions JavaScript/Web :**
```bash
cd version-basique
npm install
```

**Pour les versions Python :**
```bash
cd version-basique
pip install -r requirements.txt
```

## 🚀 Utilisation

### Version Basique

```bash
cd version-basique
npm start
# ou
python main.py
```

### Version Intermédiaire

```bash
cd version-intermediaire
npm start
# L'application s'ouvrira à http://localhost:3000
```

### Version avec Agent IA

```bash
cd version-ia
npm start
# Sélectionnez le mode (manuel, IA, spectateur)
```

## 📁 Structure du Projet

```
minesweeper-game/
├── README.md
├── version-basique/
│   ├── src/
│   │   ├── game.js
│   │   ├── board.js
│   │   └── utils.js
│   ├── main.js
│   ├── package.json
│   └── requirements.txt
├── version-intermediaire/
│   ├── src/
│   │   ├── components/
│   │   ├── App.js
│   │   └── styles/
│   ├── public/
│   ├── package.json
│   └── index.html
├── version-ia/
│   ├── src/
│   │   ├── game.js
│   │   ├── ai-agent.js
│   │   ├── solver.js
│   │   └── utils.js
│   ├── main.js
│   ├── package.json
│   └── requirements.txt
└── docs/
    ├── RULES.md
    ├── AI-ALGORITHM.md
    └── CONTRIBUTING.md
```

## ✨ Caractéristiques

### Communes à toutes les versions
- ✅ Générateur de plateau aléatoire
- ✅ Détection automatique des zones vides
- ✅ Gestion des drapeaux (flags)
- ✅ Système de scoring
- ✅ Historique de jeu

### Spécifiques à chaque version
- **Basique** : Simplicité, apprentissage
- **Intermédiaire** : UX/UI moderne, responsive design
- **IA** : Algorithmes intelligents, machine learning ready

## 🛠️ Technologies

### Version Basique
- **JavaScript** ou **Python**
- Node.js / Python 3

### Version Intermédiaire
- **React** ou **Vue.js**
- **CSS3** / **Tailwind**
- **Webpack**

### Version IA
- **JavaScript/Python**
- **Algorithms** pour résolution
- **Optional** : TensorFlow pour ML

## 📖 Documentation Supplémentaire

- [Règles du Jeu](./docs/RULES.md)
- [Algorithmes IA](./docs/AI-ALGORITHM.md)
- [Guide de Contribution](./docs/CONTRIBUTING.md)

## 🤝 Contribution

Les contributions sont bienvenues ! Veuillez :

1. Fork le projet
2. Créer une branche (`git checkout -b feature/AmazingFeature`)
3. Commit vos changements (`git commit -m 'Add some AmazingFeature'`)
4. Push vers la branche (`git push origin feature/AmazingFeature`)
5. Ouvrir une Pull Request

## 📝 Licence

Ce projet est sous licence MIT. Voir le fichier `LICENSE` pour plus de détails.

## 👨‍💻 Auteur

**hairiesolaimana-stack**

---

## 🎓 Ressources Pédagogiques

Ce projet est conçu pour apprendre :
- 🎮 Logique de jeu
- 🧠 Algorithmes de résolution
- 🤖 Principes de l'IA
- 🎨 Développement web
- 🔧 Architecture logicielle

---

**Amusez-vous bien ! 🎮💣**
