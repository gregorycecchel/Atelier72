# ATELIER 72 - Galerie d'Art

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)](https://www.w3.org/html/)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)](https://www.w3.org/Style/CSS/)
[![Responsive](https://img.shields.io/badge/Responsive-Mobile%20First-green)](https://developer.mozilla.org/fr/docs/Web/Progressive_web_apps)
[![W3C Validated](https://img.shields.io/badge/W3C-Validated-brightgreen)](https://validator.w3.org/)

## 📋 Description du projet

Site web vitrine pour la galerie d'art **ATELIER 72**, présentant l'exposition "Solitudes croisées" de l'artiste **Bilal Hamdad**. Ce projet a été développé dans le cadre d'un travail académique en trois étapes : conception graphique, intégration web et optimisation SEO/accessibilité.

---

## 🎯 Objectifs du projet

### Étape 1 : Conception graphique (UX/UI Design)
- Définition de l'identité visuelle (logo, palette de couleurs, typographie)
- Création de wireframes et prototypes
- Élaboration de la maquette graphique (mock-up)
- Étude UX avec personas et benchmark
- Validation du storyboard

### Étape 2 : Intégration web
- Transcription fidèle de la maquette graphique en HTML/CSS
- Respect strict de la charte graphique établie
- Développement **Mobile First** avec design responsive
- Validation W3C HTML et CSS sans erreur
- Versioning avec Git et commits réguliers

### Étape 3 : Optimisation SEO et Accessibilité
- Application des règles de référencement naturel (SEO)
- Conformité WCAG 2.0 pour l'accessibilité
- Structure sémantique optimisée
- Documentation des mesures d'optimisation

---

## 🎨 Charte graphique

### Palette de couleurs
| Couleur | Code | Usage |
|---------|------|-------|
| **Noir pur** | `#000000` | Header, footer, éléments principaux |
| **Blanc** | `#FFFFFF` | Texte sur fond sombre, boutons |
| **Gris clair** | `#f5f5f0` | Fond section exposition |
| **Gris foncé** | `#333333` | Texte principal, bordures |
| **Gris moyen** | `#666666` | Texte secondaire |
| **Beige** | `#f8f8f8` | Cartes événements |
| **Marron foncé** | `#4a3a2a` | Bordures œuvres d'art |
| **Gris bouton** | `#4a4a4a` | Call-to-action hero |
| **Dégradé événements** | `#1a2e1a` → `#4a2d1a` | Fond section événements |

### Typographie
- **Police principale** : `'Arial', 'Helvetica', sans-serif`
- **Interligne** : `1.6` (corps de texte)
- **Lettrage** : 
  - Titres principaux : `letter-spacing: 3-4px`
  - Navigation : `letter-spacing: 1.5px`
  - Boutons : `letter-spacing: 2px`
- **Hiérarchie** :
  - H1 (Hero) : `48px` / `font-weight: 400`
  - H2 (Sections) : `32px` / `font-weight: 400`
  - H3 (Artiste) : `28px` / `font-weight: bold`
  - H4 (Œuvres) : `18px` / `font-weight: 400`
  - Navigation : `14px`
  - Corps de texte : `16px`

### Logo
Logo vectoriel SVG "ATELIER 72" présent dans le header et le footer
- Header : `height: 50px`
- Footer : `height: 50px`
- Mobile : `height: 32-40px` (adaptatif)

---

## 🚀 Fonctionnalités

- Navigation intuitive avec menu ancré
- Section hero avec image de l'exposition
- Biographie détaillée de l'artiste Bilal Hamdad
- Galerie d'œuvres (6 peintures)
- Section événements à venir
- Formulaire d'inscription newsletter
- Informations de contact et réseaux sociaux
- Design 100% responsive (mobile, tablette, desktop)

---

## 📱 Responsive Design

Le site a été développé selon l'approche **Mobile First** :

### Points de rupture
- **Mobile** : < 768px
- **Tablette** : 768px - 1024px
- **Desktop** : > 1024px

---

## 🛠️ Technologies utilisées

- **HTML5** - Structure sémantique
- **CSS3** - Styles et animations
- **JavaScript** - Interactions (formulaire newsletter)
- **SVG** - Logo et icônes vectoriels

---

## 📁 Structure du projet

```
atelier72/
│
├── index.html              # Page principale
├── styles.css              # Feuille de styles
├── README.md              # Documentation
│
└── images/                # Ressources visuelles
    ├── hero.png
    ├── Bilal.png
    ├── Angelus.png
    ├── Louise.png
    ├── Soiree.png
    ├── Rive.png
    ├── Horizon.png
    ├── Cafe.png
    ├── nuit.png
    ├── Orsten.png
    └── Gregory.png
```

---

## ✅ Validation et conformité

### Validation W3C
-  **HTML** : Validation W3C sans erreur
-  **CSS** : Validation W3C sans erreur

### Accessibilité (WCAG 2.0)
| Critère | Mise en œuvre | Ligne(s) |
|---------|---------------|----------|
| **Alternatives textuelles** | Attributs `alt` sur toutes les images | index.html (lignes images) |
| **Navigation au clavier** | Liens et boutons accessibles | Tous les éléments interactifs |
| **Contraste des couleurs** | Ratio conforme (noir/blanc) | styles.css |
| **Aria-labels** | Labels sur icônes sociales | index.html (l.52-70, l.213-231) |
| **Structure sémantique** | Balises HTML5 (`header`, `nav`, `section`, `footer`) | index.html (structure) |
| **Langue du document** | `lang="fr"` sur `<html>` | index.html (l.2) |

### Optimisation SEO
| Critère | Mise en œuvre | Ligne(s) |
|---------|---------------|----------|
| **Balise `<title>`** | Titre descriptif et pertinent | index.html (l.6) |
| **Structure Hn** | Hiérarchie logique (h1 > h2 > h3 > h4) | index.html (structure) |
| **Balises sémantiques** | `<header>`, `<nav>`, `<section>`, `<article>`, `<footer>` | index.html |
| **URLs descriptives** | Ancres nommées (`#exposition`, `#artiste`, etc.) | index.html |
| **Images optimisées** | Format PNG, noms de fichiers descriptifs | Dossier images/ |
| **Liens internes** | Navigation fluide entre sections | index.html (menu) |
| **Viewport** | Meta viewport pour mobile | index.html (l.5) |

---

## 🚀 Installation et utilisation

### En local

1. **Cloner le dépôt**
```bash
git clone https://github.com/votre-username/atelier72.git
```

2. **Ouvrir le projet**
```bash
cd atelier72
```

3. **Lancer le site**
- Ouvrir `index.html` dans un navigateur

### En ligne

Le site est disponible via **netlify**:
[https/atelier72.netlify.app/#top](https/atelier72.netlify.app/#top)

---

---

## 📊 Améliorations futures

- Galerie d'œuvres avec lightbox
- Animations CSS avancées
- Mode sombre/clair
- Multilingue (FR/EN)
- Optimisation des images (WebP)

---

## 👨‍💻 Auteurs

**Mathias ANDRAU**
- GitHub : [@Mathijas29](https://github.com/Mathijas29)
- Email : mathias.andrau29@gmail.com

**Alina Stanimak**
- GitHub : [@alinastanimak4](https://github.com/alinastanimak4)
- Email : alinastanimak@gmail.com

**Grégory CECCHEL**
- GitHub : [@gregorycecchel](https://github.com/gregorycecchel)
- Email : gregory.cecchel@gmail.com

---

## 📄 Licence

Ce projet a été réalisé dans un cadre académique pour M. PERPIGNAN.

---

---

**Dernière mise à jour** : Novembre 2025# Atelier72
