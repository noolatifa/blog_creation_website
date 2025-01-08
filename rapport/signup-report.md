# Rapport des Sections Incluses pour Chaque Page et Fichier

## Fichier : signup.html

### 1. En-tête (Header) :
- **Logo et Menu** : 
  - Logo de l'entreprise.
  - Menu de navigation avec les liens vers les pages principales du site :
    - *Home* (Accueil)
    - *About Me* (À propos de moi)
    - *Blog* (Blog)
    - *Interests Corner* (Coin des intérêts)
    - *Contact* (Contact)
    - *Login* (Connexion)
    - *Sign Up* (Inscription) : Page active actuellement.

### 2. Contenu Principal (Main Content) :
- **Logo** : Un logo est affiché en haut du formulaire d'inscription.
- **Formulaire d'inscription** : 
  - **Champs de formulaire** : 
    - Prénom (First Name)
    - Nom (Last Name)
    - Âge (Age)
    - Sexe (Gender) : Liste déroulante avec options "Homme" et "Femme".
    - Numéro de téléphone (Phone Number) : Validation de format.
    - E-mail (Email) : Champ de texte pour l'adresse email.
    - Mot de passe (Password) : Champ pour saisir le mot de passe.
  - **Bouton d'inscription** : Bouton pour soumettre le formulaire.
- **Lien vers la page de connexion** : Lien pour les utilisateurs déjà inscrits.
- **Message interactif** : Texte encourageant l'utilisateur à rejoindre la communauté et à explorer plus d'options.

### 3. Pied de page (Footer) :
- **Logo** : Logo blanc du site.
- **Informations légales** : Mention de droits d'auteur pour 2025.
- **Liens** : Liens vers les pages principales du site.
- **Icônes sociales** : Liens vers des profils de réseaux sociaux (Facebook, Twitter, Instagram, LinkedIn).

## Fichier : signup.css

### 1. Corps de la page (Body) :
- **Fond personnalisé** : Utilisation d'un fond d'écran personnalisé avec une image en arrière-plan.
- **Disposition flexible** : Utilisation de *flexbox* pour centrer les éléments verticalement et horizontalement, assurant ainsi une disposition responsive.
- **Hauteur** : Le corps de la page prend 100% de la hauteur de la fenêtre pour un alignement parfait.

### 2. Conteneur (Container) :
- **Boîte de formulaire** : 
  - Fond semi-transparent avec des bords arrondis.
  - Ombre légère autour du conteneur pour le faire ressortir.
  - Largeur maximale de 500px avec des marges pour centrer le contenu.

### 3. Formulaire (Form) :
- **Champs de saisie** : 
  - **Input** : Les champs ont un fond léger, des bords arrondis, et un rembourrage pour plus de confort. Chaque champ est bien espacé.
  - **Sélecteur de sexe** : Champ de sélection avec options "Homme" et "Femme".
  - **Validation** : Chaque champ a une validation (e-mail, téléphone).
- **Bouton d'inscription** : 
  - Dégradé de couleur pour un effet visuel agréable.
  - Effet au survol : changement de couleur et ajout d'ombre.
  
### 4. Texte du formulaire (Form Text) :
- **Texte de connexion** : Lien pour se connecter si l'utilisateur possède déjà un compte.
- **Texte d'interaction** : Message incitant à rejoindre la communauté.

### 5. Styles additionnels :
- **Placeholder** : Les éléments de saisie (input/select) ont des styles de texte personnalisés pour les éléments de placeholder.
- **Focus** : Effet de surbrillance sur les champs de saisie au focus (bordure colorée).

