# SITE-DE-PRESSE-RESPONSIVE
## Description
Ces fichiers html et CSS définit le style général d'une page web en utilisant des polices importées de Google Fonts et en appliquant des règles de mise en page cohérentes pour différents éléments de la page.

## Contenu

## Description
Ce projet est une page web dédiée à CANAL2, une plateforme d'actualités et de programmes TV. Il présente des sections variées comme les actualités du jour, les émissions en direct et les programmes populaires.

## Technologies utilisées
- **HTML5** : Structure de la page
- **CSS3** : Mise en page et styles (via `./assets/CSS/style.css`)
- **Bootstrap** *(optionnel si utilisé)* : Mise en page responsive
- **JavaScript** *(si ajouté plus tard)* : Interactions dynamiques

## Arborescence du projet
```
CANAL2/
│── index.html
│── assets/
│   ├── CSS/
│   │   ├── style.css
│   ├── images/
│   │   ├── logo.svg
│   │   ├── menu.svg
│   │   ├── Fight.jpeg
│   │   ├── world.jpg
│   │   ├── economie.png
│   │   ├── town.jpg
│   │   ├── img-paulbiya.svg
│   │   ├── image-enfants.svg
│   │   ├── vincent.svg
│   │   ├── Rectangle 22.svg
│   │   ├── Group 45.svg
│   │   ├── debat.jpg
│   │   ├── soir.jpg
│   │   ├── presse.jpg
│   │   ├── Zik.png
│   │   ├── jackson-david-BL_Q4zjduGU-unsplash 2.svg
```

## Fonctionnalités
- **Navigation** : Barre de menu avec liens vers différentes sections
- **Actualités** : Présentation des informations les plus récentes
- **Programmes TV** : Liste des émissions avec leurs horaires
- **Vidéo en direct** : Intégration d'une vidéo YouTube
- **Espace publicité** : Section dédiée aux annonces
- **Pied de page** : Liens vers les réseaux sociaux

## Installation et utilisation
1. **Téléchargez** ou clonez ce repository :
   ```sh
   git clone https://github.com/votre-repo/canal2.git
   ```
2. **Ouvrez le fichier `index.html`** dans un navigateur web.
3. Assurez-vous que les images et le fichier CSS sont bien liés dans `assets/`.

## Améliorations futures
- Ajouter des animations avec JavaScript
- Intégrer une base de données pour gérer les actualités dynamiquement
- Optimiser pour les performances et l'accessibilité

## Auteur
**Nom de l'auteur** *(à compléter si nécessaire)*



### Importation des Polices
Trois familles de polices sont importées depuis Google Fonts :
- **Inter**
- **IBM Plex Sans**
- **Poppins**

### Variables CSS
Des variables globales sont définies pour les couleurs et les polices :
- `--primary-color`: #79AC78
- `--secondary-color`: #000E01
- `--third-color`: #FFFFFF
- `--color-button`: #618264
- `--font-family1`: "Inter", serif
- `--font-family2`: "IBM Plex Sans", serif
- `--font-family3`: "Poppins", sans-serif

### Styles Généraux
- Réinitialisation des marges, des paddings et des bordures pour tous les éléments (`*`)
- Définition d'une base de 10px pour la taille de police (`html`)
- Largeur et hauteur du `body` ajustées à la taille de la fenêtre (`100vw`, `100vh`)
- Désactivation du défilement horizontal (`overflow-x: hidden`)

### Navigation (`nav`)
- Affichage en `flex` pour aligner les éléments horizontalement
- Padding de `3.5rem` et utilisation de `font-family1`
- Liste des liens (`.nav-links`) avec un espacement (`gap: 5rem`)
- Effet de survol des liens (`hover`) qui change la couleur en `--primary-color`

### Boutons
- Largeur : `14rem`
- Hauteur : `5rem`
- Fond : `--color-button`
- Texte blanc et arrondi (`border-radius: 3rem`)
- Effet de survol pour changer de couleur

### Sections Principales
- `.section1` : mise en page en `flex`, gestion des images et des textes
- `.head` : contient une image de fond avec un dégradé (`.gradient`)
- `.side1` : autre bloc d'affichage de contenu avec titres et paragraphes
- `.images` : affichage en grille avec des images stylisées
- `.section3` : section centrée contenant un titre et une iframe pour une vidéo
- `.section5` et `.section7` : sections contenant des cartes et des images adaptées à différents affichages

### Pied de page (`footer`)
- Fond en `--primary-color`
- Centrage du contenu
- Icônes sociales avec effet de zoom au survol

### Responsivité
- Pour les écrans de `430px` et moins, les éléments sont réorganisés en colonne
- Menu masqué par défaut et affiché en mode mobile (`.menu` visible en version mobile)
- Réduction des marges et ajustement des tailles de texte et d'images

## Utilisation
- Inclure ce fichier CSS dans votre projet HTML via `<link rel="stylesheet" href="style.css">`
- Modifier les variables CSS pour adapter les couleurs et les polices selon vos besoins

## Auteur
Projet développé par Yann et Raïssa.

‣慌摮湩ⵧ慣慮㉬吭楡睬湩ⵤ䅙乎�