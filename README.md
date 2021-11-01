# Étape 3 : Mise en place des éléments de base css

1. Créer la structure du répertoire "src" :
```
src  
└─── css
│	│ style.css
│	└─── base
│	│   │ icons.css
│	│   │ main.css
│	│   │ media.css
│	└─── components
│	│   │ buttons.css
│	│   │ card.css
│	│   │ carousel.css
│	│   │ hero.css
│	│   │ menu.css
│	│   │ searchform.css
│	└─── layout
│	│   │ footer.css
│	│   │ forms.css
│	│   │ header.css
│	│   │ sections.css
│	└─── pages
│	│   │ single.css
│	└─── utils
│	│   │ variables.css
│	└─── vendors
│	│   │ normalize.css
└─── fonts
│	│ icomoon.svg
│	│ icomoon.ttf
│	│ icomoon.woff
```
2. Faire la déclaration du fichier `style.css` dans l'en-tête de chaque page.
3. Importer dans `style.css` tous les fichiers css avec la règle `@import`
```
/*
Theme Name: crdtheme
Description: Thème du Conservatoire de Belfort
Author: Xavier SENENTE
*/
@import  url('https://fonts.googleapis.com/css2?family=Mulish:ital,wght@0,300;0,700;1,300;1,700&family=Space+Mono:ital@0;1&display=swap');

/* Vendors */
@import  "vendors/normalize.css";

/* Utils */
@import  "utils/variables.css";

/* Base */
@import  "base/main.css";
@import  "base/icons.css";
@import  "base/media.css";

/* Components */
@import  "components/menu.css";
@import  "components/buttons.css";
@import  "components/hero.css";
@import  "components/card.css";
@import  "components/carousel.css";
@import  "components/searchform.css";

/* Layout */
@import  "layout/header.css";
@import  "layout/footer.css";
@import  "layout/forms.css";
@import  "layout/sections.css";

/* Pages */
@import  "pages/single.css";
```
4. Importer les variables css depuis Figma dans `variables.css`
5. Ecrire la base dans `main.css` et `media.css`
6. Intégrer la font pour les icônes de réseaux sociaux dans `icons.css`