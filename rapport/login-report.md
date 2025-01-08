# Rapport des Sections Incluses

## 1. **Page HTML (`login.html`)**

### 1.1 **En-tête (Header)**

- **Menu de navigation** : Un menu horizontal en haut de la page, comprenant les éléments suivants :
  - **Logo** : Le logo du site est affiché à gauche dans le menu.
  - **Liens de navigation** : 
    - **Home** : Lien vers la page d'accueil (`index.html`).
    - **About Me** : Lien vers la page à propos (`about.html`).
    - **Blog** : Lien vers la page du blog (`blog.html`).
    - **Interests Corner** : Lien vers la page des intérêts (`interests.html`).
    - **Contact** : Lien vers la page de contact (`contact.html`).
    - **Login** : Lien vers la page de connexion (`login.html`), avec une classe `active` pour indiquer que c'est la page actuelle.
    - **Sign Up** : Lien vers la page d'inscription (`signup.html`), avec la classe `signup`.

### 1.2 **Contenu Principal (Main Content)**

- **Logo principal** : Un logo est affiché en haut du formulaire pour renforcer l'identité visuelle du site.
- **Formulaire de Connexion** :
  - **Titre du formulaire** : "Login to Your Account", centré et en gras pour attirer l'attention de l'utilisateur.
  - **Champs de formulaire** :
    - **Email** : Un champ pour entrer l'email avec un attribut `required` pour la validation du formulaire.
    - **Mot de passe** : Un champ pour entrer le mot de passe avec un attribut `required` pour la validation.
  - **Bouton de soumission** : Un bouton "Login" avec une action `POST` envoyant les informations au serveur.
  - **Message de redirection** : Un texte informatif incitant l'utilisateur à s'inscrire s'il n'a pas encore de compte, avec un lien vers la page d'inscription (`signup.html`).
  - **Message de bienvenue** : Un message supplémentaire encourageant l'utilisateur à se connecter pour explorer le site.

### 1.3 **Pied de Page (Footer)**

- **Logo du pied de page** : Le logo est affiché à nouveau dans le pied de page, mais avec une version modifiée en couleur blanche.
- **Liens vers les autres pages** : 
  - **Home** : Lien vers la page d'accueil (`index.html`).
  - **About Me** : Lien vers la page à propos (`about.html`).
  - **Blog** : Lien vers la page du blog (`blog.html`).
  - **Interests Corner** : Lien vers la page des intérêts (`interests.html`).
  - **Contact** : Lien vers la page de contact (`contact.html`).
- **Icônes sociales** : Quatre icônes sociales (Facebook, Twitter, Instagram, LinkedIn) avec des liens qui peuvent être modifiés pour pointer vers les comptes sociaux correspondants.

---

## 2. **Fichier CSS (`login.css`)**

### 2.1 **Styles généraux du corps de la page (Body)**

- **Police** : Utilisation de la police "Poppins", importée de Google Fonts, avec des poids différents pour offrir de la variété typographique.
- **Disposition** : 
  - **Flexbox** : Le contenu est centré à la fois horizontalement et verticalement grâce à `display: flex` et `align-items: center`, `justify-content: center`.
  - **Dimensions** : La hauteur de la page est définie à 100vh (la hauteur totale du viewport), avec un fond d'image couvrant toute la page (`background-size: cover`).
  - **Bordure d'arrière-plan** : L'image d'arrière-plan est centrée et s'étend sur toute la largeur et hauteur de la page.
  - **Défilement** : Ajout d'un défilement vertical pour permettre à l'utilisateur de faire défiler la page si le contenu dépasse la hauteur de la fenêtre.

### 2.2 **Conteneur du Formulaire (Container)**

- **Style de fond** : Le fond du conteneur est légèrement transparent avec une couleur blanche (`rgba(255, 255, 255, 0.85)`), ce qui permet de voir partiellement l'arrière-plan tout en gardant le texte lisible.
- **Coins arrondis et ombre portée** : Les coins du conteneur sont arrondis (`border-radius: 8px`) et une ombre est ajoutée pour donner de la profondeur (`box-shadow: 0 8px 16px rgba(0, 0, 0, 0.2)`).
- **Dimensions du conteneur** : Le conteneur a une largeur maximale de 500px et occupe toute la largeur disponible dans la fenêtre. Sa hauteur maximale est de 70vh pour éviter qu'il devienne trop grand.

### 2.3 **Formulaire de Connexion (Form)**

- **Champs de saisie** :
  - **Email et mot de passe** : Ces champs ont un fond transparent avec une bordure fine et grise. Un espace est ajouté au-dessus de chaque champ pour séparer les éléments.
  - **Style de texte** : Le texte des champs de saisie est affiché en petite taille et en gris clair. L'effet `focus` donne une bordure bleue pour améliorer l'accessibilité et l'interaction.
- **Bouton de Connexion** : Le bouton utilise un dégradé de couleurs (`linear-gradient(135deg, #6e8efb, #a777e3)`) pour un effet visuel attrayant. Lors du survol, la couleur du bouton change et une ombre est ajoutée pour l'effet de "clic".
- **Message d'inscription** : Le lien "Sign Up" utilise une couleur bleue qui devient soulignée lors du survol pour une meilleure interaction visuelle.

### 2.4 **Texte de l'Inscription (Signup Text)**

- **Texte d'encouragement à l'inscription** : Un petit texte est ajouté en bas du formulaire pour encourager les utilisateurs à s'inscrire s'ils n'ont pas de compte. Le lien est stylisé en bleu et devient souligné lorsqu'on le survole.

### 2.5 **Texte Interactif (Interaction Text)**

- **Message de bienvenue** : Ce texte est centré et apparaît en dessous du formulaire de connexion pour inviter l'utilisateur à s'engager davantage sur le site.

### 2.6 **Placeholders et Focus des Champs de Saisie**

- **Placeholders** : Les placeholders dans les champs de saisie sont stylisés avec une couleur gris clair et une petite taille de police pour les différencier du texte saisi.
- **Focus** : Lorsqu'un champ de saisie est sélectionné (focus), une bordure bleue apparaît autour de celui-ci, ce qui améliore l'expérience utilisateur en indiquant visuellement quel champ est actif.

