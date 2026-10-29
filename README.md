# 🚀 Portfolio Professionnel - Maxime HANS

> Portfolio développé dans le cadre de l'épreuve U5 du **BTS SIO (Services Informatiques aux Organisations) option SISR**. 
> Ce site sert de carte de visite professionnelle pour mes recherches d'alternance, de stages et d'emplois, tout en présentant mes compétences, mes projets et ma veille technologique.

---

## 🎯 Aperçu du Projet

Ce projet a été conçu selon une approche **One-Page**, épurée, moderne et orientée utilisateur (recruteurs, formateurs, étudiants)[cite: 5, 16]. 

### ✨ Fonctionnalités & Points Forts
* **Design & Identité Visuelle :** Palette de couleurs soignée (bleu océan/cyan), typographie *Doppio One* et intégration d'un logo typographique minimaliste (`MH.`).
* **Expérience utilisateur (UI/UX) :** 
  * Navigation fluide (*Smooth Scroll*) à travers les sections[cite: 12].
  * Bulles d'informations interactives (`<details>` / `<summary>`) pour afficher ou masquer les détails techniques sans surcharger la page[cite: 5, 16].
  * Formulaire de contact avec ciblage dynamique (Entreprise, Étudiant, Professeur).
  * Bouton d'accès direct vers mon profil LinkedIn intégré avec icône FontAwesome[cite: 16].
* **Mode Sombre Automatique :** Gestion native du thème sombre via CSS (`prefers-color-scheme`) en fonction des préférences système du visiteur[cite: 12].
* **Page 404 Créative :** Page "Introuvable" thématique (aéronautique/réseau) dotée d'animations graphiques purement en CSS (animation de câbles électriques débranchés, étincelles multicolores et avion en arrière-plan)[cite: 22].
* **Responsive Design :** S'adapte de manière fluide à tous les types d'écrans (ordinateurs, tablettes, smartphones)[cite: 3, 7].

---

## 🛠️ Stack Technique

Le projet a été développé en respectant strictement les contraintes académiques (sans framework, sans CMS, sans bibliothèque externe lourde) :
* **HTML5 Sémantique** (structure propre, balises sémantiques `<header>`, `<nav>`, `<section>`, `<article>`)[cite: 2].
* **CSS3 Moderne** (Variables CSS/Custom Properties, Flexbox, CSS Grid, Media Queries, animations `@keyframes`).
* **FontAwesome** (pour les icônes vectorielles)[cite: 16].

---

## 📂 Arborescence du Projet

Conformément aux consignes du projet, l'arborescence respecte la structure standard suivante[cite: 3] :

```text
projetU5/
│
├── css/
│   └── style.css          # Fichier de styles unique et modulaire
├── documentation/
│   ├── Cahier des Charges.docx
│   ├── Charte Graphique.docx
│   └── Maquettes.jpg
├── js/
│   └── main.js            # Réservé aux évolutions futures (JavaScript)
├── pages/                 # (Si multi-pages, ou centralisé pour la One-Page)
├── 404.html               # Page d'erreur personnalisée et animée
├── index.html             # Page principale (One-Page)
└── README.md              # Documentation du projet