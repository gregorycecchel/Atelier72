# ATELIER 72 - Galerie d'Art

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)](https://www.w3.org/html/)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)](https://www.w3.org/Style/CSS/)
[![Responsive](https://img.shields.io/badge/Responsive-Mobile%20First-green)](https://developer.mozilla.org/fr/docs/Web/Progressive_web_apps)
[![W3C Validated](https://img.shields.io/badge/W3C-Validated-brightgreen)](https://validator.w3.org/)

## Description du projet

Site web vitrine pour la galerie d'art **ATELIER 72**, présentant l'exposition "Solitudes croisées" de l'artiste **Bilal Hamdad**. Ce projet a été développé dans le cadre d'un travail académique en trois étapes : conception graphique, intégration web et optimisation SEO/accessibilité.


## Objectifs du projet

### Étape 1 : Le prototype
La première étape de réalisation du projet va nous permettre de définir l’aspect graphique du projet. Ainsi, nous devrons montrer à M. DECHEWSKY éventuellement le storyboard, les personas (non obligatoires) selon l’étude UX, le benchmark, les visuels (logo par exemple) et la maquette graphique à différentes phases de création (wireframe, prototype, mock-up, etc.).

### Étape 2 : Le site web
La seconde étape du projet est le résultat de l’intégration de la maquette graphique proposée à l’étape 1. La transcription numérique, permettant une publication sur le web, doit scrupuleusement respecter l’aspect et les contraintes graphiques que nous avons précédemment fixés (logo, couleurs, typographie, organisation visuelle, etc.).

D’autre part, l’affichage du site doit être responsive afin de s’adapter à tous les formats d’écran, la priorité initiale étant basée sur un support mobile, de type smartphone.

### Étape 3 : L'accessibilité et le référencementDevoir

La dernière étape consiste essentiellement à lister l’application des principales règles de référencement naturel (SEO) et d’accessibilité du site web. Il est donc nécessaire que nous dressions un tableau précisant les mesures mises en place par thème (référencement et accessibilité), avec l’indication de la ligne d’écriture dans le fichier correspondant HTML et/ou CSS.

---

## Charte graphique

### Palette de couleurs
| Couleur | Code | Usage |
|---------|------|-------|
| **Noir pur** | `#000000` | Header, footer, éléments principaux |
| **Blanc** | `#FFFFFF` | Texte sur fond sombre, boutons |
| **Gris clair** | `#F5F5F3` | Fond section exposition |
| **Gris foncé** | `#333333` | Texte principal, bordures |
| **Gris moyen** | `#666666` | Texte secondaire |
| **Beige** | `#D9D9D9` | Cartes événements |
| **Marron foncé** | `#4B1806` | Bordures œuvres d'art |
| **Gris bouton** | `#4a4a4a` | Call-to-action hero |
| **Dégradé événements** | `#1a2e1a` → `#4a2d1a` | Fond section événements |

### Typographie
- **Police principale PROVISOIRE** : `'Arial', 'Helvetica', sans-serif`
- **Police finale** : `'Almarai', sans-serif`
- **Police du logo** : `'Aileron', sans-serif`
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

## Fonctionnalités

- Navigation intuitive avec menu ancré
- Section hero avec image de l'exposition
- Biographie détaillée de l'artiste Bilal Hamdad
- Galerie d'œuvres (6 peintures)
- Section événements à venir
- Formulaire d'inscription newsletter
- Informations de contact et réseaux sociaux
- Design 100% responsive (mobile, tablette, desktop)

---

## Responsive Design

Le site a été développé selon l'approche **Mobile First** :

### Points de rupture
- **Mobile** : < 768px
- **Tablette** : 768px - 1024px
- **Desktop** : > 1024px

---

## Technologies utilisées

- **HTML5** - Structure sémantique
- **CSS3** - Styles et animations
- **JavaScript** - Interactions (formulaire newsletter)
- **SVG** - Logo et icônes vectoriels

---

## Structure du projet

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

## Validation et conformité

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

## Installation et utilisation

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

## Améliorations futures

- Galerie d'œuvres avec lightbox
- Animations CSS avancées
- Mode sombre/clair
- Multilingue (FR/EN)
- Optimisation des images (WebP)

---

## Auteurs

**Mathias ANDRAU** 
- GitHub : [@Mathijas29](https://github.com/Mathijas29)
- Email : mathias.andrau29@gmail.com

**Alina Stanimak**
- GitHub : [alinastanimak4-droid](https://github.com/alinastanimak4-droid)
- Email : alinastanimak@gmail.com

**Grégory CECCHEL**
- GitHub : [@gregorycecchel](https://github.com/gregorycecchel)
- Email : gregory.cecchel@gmail.com

---

## Licence

Ce projet a été réalisé dans un cadre académique pour M. PERPIGNAN.

---

---

**Dernière mise à jour** : Novembre 2025# Atelier72
