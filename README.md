# ATELIER 72 - Galerie d'Art

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)](https://www.w3.org/html/)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)](https://www.w3.org/Style/CSS/)
[![Responsive](https://img.shields.io/badge/Responsive-Mobile%20First-green)](https://developer.mozilla.org/fr/docs/Web/Progressive_web_apps)
[![W3C Validated](https://img.shields.io/badge/W3C-Validated-brightgreen)](https://validator.w3.org/)

## Description du projet

Site web vitrine pour la galerie d'art **ATELIER 72**, présentant l'exposition "Solitudes croisées" de l'artiste **Bilal Hamdad**. Ce projet a été développé dans le cadre d'un travail académique en trois étapes : conception graphique, intégration web et optimisation SEO/accessibilité.


## Objectifs du projet

### Étape 1 : Le prototype
La première étape de réalisation du projet va nous permettre de définir l'aspect graphique du projet. Ainsi, nous devrons montrer à M. DECHEWSKY éventuellement le storyboard, les personas (non obligatoires) selon l'étude UX, le benchmark, les visuels (logo par exemple) et la maquette graphique à différentes phases de création (wireframe, prototype, mock-up, etc.).

### Étape 2 : Le site web
La seconde étape du projet est le résultat de l'intégration de la maquette graphique proposée à l'étape 1. La transcription numérique, permettant une publication sur le web, doit scrupuleusement respecter l'aspect et les contraintes graphiques que nous avons précédemment fixés (logo, couleurs, typographie, organisation visuelle, etc.).

D'autre part, l'affichage du site doit être responsive afin de s'adapter à tous les formats d'écran, la priorité initiale étant basée sur un support mobile, de type smartphone.

### Étape 3 : L'accessibilité et le référencement

La dernière étape consiste essentiellement à lister l'application des principales règles de référencement naturel (SEO) et d'accessibilité du site web. Il est donc nécessaire que nous dressions un tableau précisant les mesures mises en place par thème (référencement et accessibilité), avec l'indication de la ligne d'écriture dans le fichier correspondant HTML et/ou CSS.


## 🎨 Charte graphique

### Palette de couleurs

#### Mode clair (défaut)
| Couleur | Code | Usage |
|---------|------|-------|
| **Noir pur** | `#000000` | Header, footer |
| **Blanc** | `#FFFFFF` | Texte sur fond sombre, boutons |
| **Gris clair** | `#F5F5F0` | Fond section exposition |
| **Gris clair secondaire** | `#F8F8F8` | Fond cartes événements |
| **Gris foncé** | `#333333` | Texte principal, bordures |
| **Gris moyen** | `#666666` | Texte secondaire |
| **Gris bouton** | `#4A4A4A` | Call-to-action hero |
| **Gris bouton hover** | `#5A5A5A` | Survol boutons |
| **Marron bordure** | `#4A3A2A` | Bordures œuvres d'art |
| **Dégradé événements** | `#1A2E1A` → `#4A2D1A` | Fond section événements |
| **Bouton clair** | `#E0E0E0` | Boutons événements |
| **Placeholder** | `#999999` | Texte placeholder formulaire |

#### Mode sombre
| Couleur | Code | Usage |
|---------|------|-------|
| **Noir profond** | `#1A1A1A` | Fond principal |
| **Gris foncé** | `#2A2A2A` | Fond secondaire, cartes |
| **Blanc** | `#FFFFFF` | Texte clair |
| **Gris clair** | `#E0E0E0` | Texte principal |
| **Gris moyen** | `#B0B0B0` | Texte secondaire |
| **Gris accent** | `#6B6B6B` | Éléments interactifs |
| **Bordure foncée** | `#444444` | Bordures principales |
| **Bordure claire** | `#555555` | Bordures secondaires |
| **Dégradé sombre** | `#0A0A0A` → `#2A2A2A` | Fond section événements |

### Typographie
- **Police titres/navigation** : `'Aileron', sans-serif`
- **Police corps de texte** : `'Almarai', sans-serif`
- **Interligne** : `1.6` (corps de texte)
- **Espacement lettres** : 
  - Titres principaux : `3-4px`
  - Navigation : `1.5px`
  - Boutons : `2px`
- **Hiérarchie** :
  - H1 (Hero) : `48px` / `font-weight: 400`
  - H2 (Sections) : `32px` / `font-weight: 400`
  - H3 (Artiste) : `28px` / `font-weight: bold`
  - H4 (Œuvres) : `18px` / `font-weight: 400`
  - Navigation : `14px`
  - Corps : `16px`

### Logo
Logo vectoriel SVG "ATELIER 72"
- Header : `50px`
- Footer : `50px`
- Mobile : `32-40px` (adaptatif)

## Fonctionnalités

- Navigation intuitive avec menu ancré (fixe en haut)
- **Mode sombre/clair** : Bouton de bascule avec sauvegarde de préférence (localStorage)
- Section hero avec image d'exposition et animations
- Biographie détaillée de l'artiste Bilal Hamdad avec portrait
- Galerie de 6 œuvres d'art (peintures à l'huile)
- Section événements avec 3 cartes (liens externes sécurisés)
- Formulaire d'inscription newsletter avec validation
- Informations de contact complètes
- Icônes de réseaux sociaux (Instagram, Facebook, LinkedIn)
- Design 100% responsive (mobile, tablette, desktop)
- Animations CSS (hero zoom, hover effects, fade-in)
- Transitions fluides entre thèmes


## Responsive Design

Le site a été développé selon l'approche **Mobile First** :

### Points de rupture
- **Mobile** : < 768px
- **Tablette** : 768px - 1024px
- **Desktop** : > 1024px


## Technologies utilisées

- **HTML5** - Structure sémantique moderne
- **CSS3** - Styles, animations, transitions, variables CSS
- **JavaScript vanilla** - Interactions (formulaire newsletter, thème sombre/clair, localStorage)
- **SVG** - Logo et icônes vectoriels
- **Google Fonts** - Polices personnalisées Aileron et Almarai


## Structure du projet

```
atelier72/
│
├── index.html              # Page principale
├── styles.css              # Feuille de styles principale
├── README.md              # Documentation du projet
│
├── fonts/                 # Polices personnalisées
│   ├── aileron/
│   │   ├── Aileron-Regular.otf
│   │   ├── Aileron-Bold.otf
│   │   ├── Aileron-Light.otf
│   │   ├── Aileron-Italic.otf
│   │   └── Aileron-BoldItalic.otf
│   └── Almarai/
│       ├── Almarai-Regular.ttf
│       ├── Almarai-Bold.ttf
│       └── Almarai-Light.ttf
│
├── images/                # Ressources visuelles
│   ├── hero.png          # Image principale hero section
│   ├── Bilal.png         # Portrait de l'artiste
│   ├── Angelus.png       # Œuvre 1
│   ├── Louise.png        # Œuvre 2
│   ├── Soiree.png        # Œuvre 3
│   ├── Rive.png          # Œuvre 4
│   ├── Horizon.png       # Œuvre 5
│   ├── Cafe.png          # Œuvre 6
│   ├── nuit.png          # Événement 1
│   ├── Orsten.png        # Événement 2
│   └── Gregory.png       # Événement 3
│
├── logo.svg               # Logo ATELIER 72
├── icon-instagram.svg     # Icône Instagram
├── icon-facebook.svg      # Icône Facebook
└── icon-linkedin.svg      # Icône LinkedIn
```


## Validation et conformité

### Validation W3C
**HTML** : Validation W3C sans erreur
**CSS** : Validation W3C sans erreur

### Accessibilité (WCAG 2.0)
| Critère | Mise en œuvre | Ligne(s) |
|---------|---------------|----------|
| **Alternatives textuelles** | Attributs `alt` sur toutes les images | index.html (l.39, l.52-59, l.74, l.87-114, l.125-142) |
| **Navigation au clavier** | Liens et boutons accessibles avec focus | Tous les éléments interactifs |
| **Contraste des couleurs** | Ratio conforme (noir #000/blanc #FFF) | styles.css (l.57-75) |
| **Aria-labels** | Labels descriptifs sur boutons et icônes | index.html (l.25, l.27-36, l.178-186) |
| **Structure sémantique** | Balises HTML5 (`header`, `nav`, `section`, `footer`) | index.html (l.9-37, l.39-42, l.44-116, l.118-144, l.146-193) |
| **Langue du document** | `lang="fr"` sur `<html>` | index.html (l.2) |
| **Focus visible** | États de focus pour navigation clavier | styles.css (l.252-254, l.321-326) |

### Optimisation SEO
| Critère | Mise en œuvre | Ligne(s) |
|---------|---------------|----------|
| **Balise `<title>`** | "ATELIER 72 - Galerie d'Art" | index.html (l.6) |
| **Meta charset** | Encodage UTF-8 déclaré | index.html (l.4) |
| **Meta viewport** | Responsive design mobile-first | index.html (l.5) |
| **Structure Hn** | Hiérarchie logique (H1→H2→H3→H4) | index.html (l.41, l.48, l.56, l.75, l.89+) |
| **Balises sémantiques** | `<header>`, `<nav>`, `<section>`, `<footer>` | index.html (structure complète) |
| **URLs descriptives** | Ancres nommées (`#exposition`, `#artiste`, `#oeuvres`, `#evenements`, `#contact`) | index.html (l.10, l.16-20, l.44, l.55, l.85, l.118, l.146) |
| **Images optimisées** | Format PNG, noms descriptifs | Dossier images/ |
| **Liens internes** | Navigation entre sections via menu | index.html (l.16-20) |
| **Attributs `rel`** | `noopener noreferrer` sur liens externes | index.html (l.129, l.136, l.143) |


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

Le site est disponible via **Netlify** :
[https://atelier72.netlify.app](https://atelier72.netlify.app/#top)


## Améliorations futures

- ~~Galerie d'œuvres avec lightbox~~ → Galerie optimisée avec hover effects
- ~~Animations CSS avancées~~ → Animations hero et transitions implémentées
- ~~Mode sombre/clair~~ → **Implémenté avec sauvegarde localStorage**
- Optimisation des images (conversion WebP)

## Auteurs

**Mathias ANDRAU** 
- GitHub : [@Mathijas29](https://github.com/Mathijas29)
- Email : mathias.andrau29@gmail.com

**Alina Stanimak**
- GitHub : [@alinastanimak4-droid](https://github.com/alinastanimak4-droid)
- Email : alinastanimak@gmail.com

**Grégory CECCHEL**
- GitHub : [@gregorycecchel](https://github.com/gregorycecchel)
- Email : gregory.cecchel@gmail.com


## Licence

Ce projet a été réalisé dans un cadre académique pour M. PERPIGNAN.


**Dernière mise à jour** : Novembre 2025
