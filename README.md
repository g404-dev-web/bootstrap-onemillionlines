# TP : One Million Lines

Bienvenue dans ce TP d'intégration web. Vous allez reproduire une *landing page* complète et responsive à partir d'une maquette graphique, en utilisant les fonctionnalités de **Bootstrap**.

---

## 🎯 Objectifs pédagogiques
- Maîtriser le système de grille Bootstrap.
- Manipuler les composants interactifs Bootstrap.
- Savoir surcharger proprement du CSS sans altérer la bibliothèque tierce.
- Mettre en place un scroll fluide et des interactions en JavaScript Vanilla.

---

## 📋 Spécifications techniques & Cahier des charges

### 1. Sémantique et découpage
Votre page doit respecter le découpage ordonné suivant :
1. `<header>` / `<nav>` : Barre de navigation fixe ou collante (`sticky-top`) avec logo à gauche et liens à droite.
2. `<section id="home">` : Section d'accroche (Hero) contenant le titre, le slogan et le bouton d'action.
3. `<section id="who">` : Présentation du projet avec texte et image illustrative.
4. `<section id="get-involved">` : Grille Bootstrap présentant les différentes manières de participer.
5. `<footer>` : Pied de page contenant les mentions légales, copyright et liens réseaux sociaux.
6. `<button id="back-to-top">` : Bouton flottant permettant de remonter au sommet de la page.

### 2. Modale Vidéo
- Un clic sur le bouton **« Learn more »** de la section Home doit ouvrir une **modale Bootstrap**.
- La modale doit embarquer une vidéo YouTube en conservant un ratio d'affichage parfait grâce à la classe `.ratio .ratio-16x9`.

### 3. Responsive & Breakpoints
La maquette doit s'adapter fluidement à toutes les résolutions :
- **Mobile (< 768px)** : La navbar se replie dans un menu hamburger (`navbar-toggler`), les colonnes de la section `#get-involved` s'empilent verticalement sur 1 colonne.
- **Tablette (≥ 768px et < 992px)** : Répartition sur 2 colonnes.
- **Desktop (≥ 992px)** : Menu déplié à plat, répartition sur 3 ou 4 colonnes selon la maquette.

### 4. Styles & Customisation (`css/custom.css`)
- **Règle d'or** : Ne **JAMAIS** modifier les fichiers sources de Bootstrap.
- Utilisez des variables CSS et surchargez les classes Bootstrap ciblées pour respecter la typographie, les couleurs et les espacements de la maquette.

---

## 🚀 Bonus & Bonnes pratiques
- [ ] **Smooth Scroll natif** : Défilement doux lors du clic sur les ancres du menu et le bouton *Back to top*.
- [ ] **Back-to-top dynamique** : Le bouton n'apparaît que lorsque l'utilisateur a scrollé de plus de 300px vers le bas.
- [ ] **Support Dark Mode** : Prise en charge du thème sombre avec `data-bs-theme="dark"`.
