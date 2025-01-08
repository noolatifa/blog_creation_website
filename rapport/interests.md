# Rapport sur la page "Interests Corner"

Cette page, intitulée "Interests Corner", présente les centres d'intérêt personnels de l'utilisateur à travers différents domaines comme le maquillage, la technologie, la recherche, les films et la musique. Le design est moderne, avec une disposition flexible et une interaction soignée. Ce rapport explique les différentes sections de la page ainsi que les méthodes HTML et CSS utilisées pour la structurer et la styliser.

## 1. Structure HTML

### 1.1. En-tête (`<header>`)
L'en-tête de la page contient :
- Un logo à gauche (`<div class="logomenu">`), représentant l'image de l'identité visuelle du site.
- Un menu de navigation (`<nav>`) avec une liste d'éléments (`<ul>`), comprenant des liens vers différentes pages comme "Home", "About Me", "Blog", "Interests Corner", "Contact", et des liens pour la connexion et l'inscription.

### 1.2. Section d'introduction (`<section class="intro">`)
Cette section est utilisée pour introduire la page "Interests Corner" avec :
- Un titre principal (`<h1>`) qui affiche "Interests Corner".
- Un paragraphe (`<p>`) qui donne un aperçu de ce que l'utilisateur va découvrir dans cette section.
- Un lien de défilement (une flèche) permettant de guider l'utilisateur vers le bas de la page.

### 1.3. Catégories d'intérêts (`<section class="categories">`)
Cette section présente différentes catégories d'intérêts sous forme de blocs. Chaque catégorie est représentée par un `<div>` avec une classe `category`, comprenant :
- Un titre (`<h2>`) et une brève description de l'intérêt.

### 1.4. Détails des intérêts (`<section class="detailed-interests">`)
Cette section décrit en détail les intérêts personnels de l'utilisateur dans les domaines suivants :
- **Technologie** (IT)
- **Recherche académique**
- **Maquillage et mode**
- **Films**

Chaque domaine est présenté dans une section avec une table (`<table>`) comprenant une image, un titre (`<h3>`) et une description détaillée sous forme de texte (`<p>`).

### 1.5. Favoris (`<div class="favorites-section">`)
Dans chaque section d'intérêt, un sous-ensemble appelé "Mes Favoris" est présenté avec des images d'éléments favoris (produits de maquillage, films, etc.), chaque élément étant représenté par une image et une légende.

### 1.6. Pied de page (`<footer>`)
Non inclus dans ce code, mais généralement, un pied de page pourrait être présent avec des informations sur le copyright, des liens sociaux, ou d'autres informations pertinentes.

## 2. Méthodes CSS

### 2.1. Mise en page et structure
- **Grille CSS (Grid Layout)** : La classe `.categories` utilise une grille CSS pour créer une mise en page fluide et réactive. Le nombre de colonnes s'ajuste automatiquement en fonction de la taille de l'écran à l'aide de la règle `grid-template-columns: repeat(auto-fit, minmax(250px, 1fr))`.
- **Flexbox** : La classe `.favorites-section` utilise Flexbox pour aligner les éléments de manière flexible et responsive.

### 2.2. Effets de survol et animations
- **Transformation et ombre portée** : Les éléments de la classe `.category` utilisent `transform: scale(1.05)` et une ombre (`box-shadow`) lors du survol, ce qui crée un effet de mise en surbrillance.
- **Hover sur les images** : Les images dans la section des favoris sont également animées pour augmenter de taille et ajouter une ombre au survol grâce à `transform: scale(1.1)` et `box-shadow`.

### 2.3. Typographie
- **Police Poppins** : La page utilise la police 'Poppins', une police sans-serif moderne, importée depuis Google Fonts.
- **Styles de texte** : Les titres et sous-titres utilisent des tailles de police spécifiques (`font-size`) pour les différencier et rendre le contenu hiérarchisé. Les textes de descriptions sont justifiés et ont une taille plus petite pour une lecture plus agréable.

### 2.4. Responsivité
- Le site utilise principalement des techniques de mise en page flexibles telles que **grilles** et **flexbox**, garantissant que la page soit adaptée aux écrans de différentes tailles (ordinateurs de bureau, tablettes et téléphones mobiles).

### 2.5. Mise en forme des formulaires
- La section d'inscription à la newsletter utilise des champs de texte stylisés avec un fond clair, une bordure grise, et des coins arrondis. Le bouton d'envoi change de couleur et devient plus foncé lorsqu'il est survolé, grâce à `:hover`.

## 3. Conclusion

La page "Interests Corner" utilise une combinaison d'HTML sémantique et de CSS moderne pour offrir une expérience utilisateur fluide et responsive. La mise en page est flexible, permettant une lecture agréable sur tous les types d'appareils. Les animations subtiles et les effets visuels renforcent l'interactivité et l'engagement de l'utilisateur. La section "Mes Favoris" et les descriptions détaillées des intérêts personnels permettent de donner une dimension plus personnelle et engageante au contenu.
