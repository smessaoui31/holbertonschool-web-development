![Background](template/background.png)

# CSS Advanced - Task 0: SmileSchool

## Description

Ce projet consiste à implémenter le style CSS d'une page web **SmileSchool** à partir d'une maquette Figma. La page HTML de base est déjà fournie, l'objectif est d'appliquer des styles CSS avancés pour reproduire fidèlement le design.

## Structure de la page

La page est composée des sections suivantes :

- **Header** : Logo + navigation (COURSES, PRICING, LOGIN)
- **Hero** : Titre "Get schooled", bouton d'inscription, présentation des instructeurs
- **Quote** : Témoignage d'un utilisateur
- **Tutorials** : Les tutoriels les plus populaires avec notes et durée
- **Membership** : Présentation des avantages de l'adhésion gratuite
- **FAQ** : Questions fréquemment posées
- **Footer** : Logo, liens sociaux et copyright

## Assets / Template

Les ressources graphiques utilisées se trouvent dans le dossier `../template/` :

| Fichier | Usage |
|---|---|
| `background.png` | Image de fond de la section hero |
| `logo.png` | Logo SmileSchool (header & footer) |
| `avatar.svg` | Avatar de la section témoignage |
| `profile_1.png` à `profile_4.png` | Photos des instructeurs |
| `preview_1.png` à `preview_4.png` | Miniatures des tutoriels |
| `star_1.svg` | Étoile active (notation) |
| `star_2.svg` | Étoile inactive (notation) |
| `smile.svg` | Icône pour la section membership |
| `icon_facebook.svg` | Icône réseau social Facebook |
| `icon_twitter.svg` | Icône réseau social Twitter |
| `icon_instagram.svg` | Icône réseau social Instagram |

## Background de la section Hero

L'image `background.png` est utilisée comme fond de la section `.hero`. Elle doit être appliquée en CSS via `background-image` avec les propriétés suivantes :

```css
.hero {
    background-image: url('../template/background.png');
    background-size: cover;
    background-position: center;
}
```

## Technologies utilisées

- HTML5
- CSS3

## Auteur

**smessaoui31** - Holberton School
