# 🟦 Projet d'Intégration Web – Application de Covoiturage ESPRIT

Ce projet consiste à intégrer une interface web de covoiturage destinée aux étudiants de l'école ESPRIT, en respectant strictement la maquette Figma fournie dans le cadre du module Intégration Web.

---

## 📁 Arborescence du projet
```
/Integration-web
│── /public
│   ├── index.html
│   ├── trajet.html
│   ├── profil.html
│   └── ...
│── /src
│   └── input.css (fichier source Tailwind)
│── style.css (fichier compilé Tailwind v4)
│── tailwind.config.js
└── README.md
```

---

## 👥 Membres de l'équipe & Responsabilités

### 🟨 Besoin 1 : L'utilisateur veut se déplacer en toute tranquillité
- **Maram Boussalem**
- **Ranine Talbi**

### 🟩 Besoin 2 : L'utilisateur veut avoir confiance avant et après réservation
- **Achraf BEN MOUELLI**
- **Mariem Aouadi**

### 🟧 Besoin 3 : L'utilisateur veut organiser facilement ses activités
- **Skander Bardaoui**
- **Mohamed Aziz Msakni**

---

## 🎯 Contraintes du Projet

### ✔ Respect strict de la maquette Figma
- Respect total des couleurs, typographies, espacements, icônes et alignements

### ✔ Utilisation exclusive de Tailwind CSS v4
- ❌ Aucun fichier CSS personnalisé
- ✔ Toutes les mises en page réalisées avec les classes utilitaires Tailwind

### ✔ Structure HTML professionnelle
- Code propre, lisible et indenté
- Utilisation correcte des balises : `<header>`, `<main>`, `<section>`, `<footer>`, `<nav>`
- Nomination claire et hiérarchique des sections

### ✔ Responsive Design obligatoire
Compatible sur :
- 📱 Mobile ≤ 640px
- 📲 Tablette 641–1024px
- 🖥️ Desktop ≥ 1024px

Utilisation des breakpoints Tailwind : `sm:`, `md:`, `lg:`, `xl:`

---

## ⚙️ Instructions d'Exécution du Projet

### 3.1 Prérequis
- Navigateur web moderne
- VS Code (recommandé)
- Node.js (si recompilation Tailwind nécessaire)

### 3.2 Installation

#### Cloner le dépôt
```bash
git clone https://github.com/maramboussalem/covoi.git
cd covoi
```

#### Installer les dépendances
```bash
npm install
```

#### Compilation Tailwind CSS (version 4)
Si vous modifiez `src/input.css`, recompilez avec :
```bash
npx tailwindcss -i ./src/input.css -o ./style.css --watch
```

#### Lancer le projet
Ouvrez `index.html` dans un navigateur web moderne pour visualiser l'application.

---

## 📂 Structure Tailwind

- **`src/input.css`** : fichier source où vous écrivez vos classes Tailwind
- **`style.css`** : fichier compilé généré par Tailwind, à inclure dans vos pages HTML
- **`tailwind.config.js`** : configuration Tailwind (couleurs, breakpoints, plugins…)

---

## 📝 Licence

Ce projet est réalisé dans le cadre académique à ESPRIT.
