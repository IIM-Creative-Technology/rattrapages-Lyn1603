
# RATTRAPAGE TAILWIND LYNDA BENABDESSADOK 

#### Bonjour , je suis Lynda Benabdessadok et je vais vous présenter mon exercice effectué avec, comme technologie utilisée, Tailwind.

## 1- Contexte : 
#### Le projet que nous devions réalisé était une intégration de maquette du restaurant Mangoo. 
#### Pour ce faire, je suis partie d'une configuration vanilla avec un fichier HTML et deux fichiers CSS pour pouvoir compiler mon Tailwind.

## 2- Installation de tailwind :
### Voici les étapes d'installation de TailwindCSS avec un fichier HTML :

a. Créer un nouveau répertoire pour votre projet et naviguez-y à l'aide d'un terminal ou d'une invite de commande.

b. Initialiser un nouveau projet npm en exécutant la commande suivante :
   ```
   npm init -y
   ```

c. Installer Tailwind CSS et ses dépendances en exécutant la commande suivante :
   ```
   npm install tailwindcss postcss autoprefixer
   ```

d. Une fois l'installation terminée, créer un fichier de configuration pour Tailwind CSS en exécutant la commande suivante :
   ```
   npx tailwindcss init
   ```

Cela créera un fichier nommé `tailwind.config.js` dans le répertoire de projet. Ce fichier vous permet de paramettrer de Tailwind CSS.

e. Créer un nouveau fichier CSS dans le répertoire de projet, par exemple, `styles.css`.

f. Ouvrir le fichier `styles.css` et importer Tailwind CSS en ajoutant les lignes suivantes en haut du fichier :
   ```css
   @import 'tailwindcss/base';
   @import 'tailwindcss/components';
   @import 'tailwindcss/utilities';
   ```

### Voici les étapes de la compilation et de l'utilisation de Tailwind CSS

g. Dans le répertoire de projet, créer un nouveau fichier nommé `postcss.config.js`.

h. Ouvrir le fichier `postcss.config.js` et ajoutez le code suivant :
   ```javascript
   module.exports = {
     plugins: [
       require('tailwindcss'),
       require('autoprefixer'),
     ],
   };
   ```
   Cette commande permettra de compiler le fichier `styles.css` en utilisant PostCSS et de générer le CSS traité dans `output.css`.

   Cela générera le fichier `output.css` dans votre répertoire de projet.

i. Mettre à jour le fichier `index.html` pour inclure le fichier `output.css` :
   ```html
   <!DOCTYPE html>
   <html>
   <head>
     <link href="output.css" rel="stylesheet">
   </head>
   <body>
     <!-- Votre contenu HTML se trouve ici -->
   </body>
   </html>
   ```

j. Ouvrir un terminal ou une invite de commande et exécutez la commande suivante pour compiler votre fichier CSS :
   ```
   npx tailwindcss -i css/style.css -o dist/output.css --watch
   ```

#### Voici comment j'ai installé et compilé TaiwindCSS avec un fichier HTML.

## 2- Justification de mon choix : 
#### Pourquoi ai-je choisi ce mode de configuration ? 
#### En observant la maquette, j'ai pu y constaté plusieurs similitudes entre les div de la maquette, ce qui m'a facilité le developpement du responsive en adaptant les éléments de mes div en fonction de la taille de l'écran. 
#### De plus, étant un framework qui utilise le mobile first, il a été idéal pour moi de jouer avec les flex hidden pour pouvoir personnalisé un maximum mon responsive que mon format ordinateur tout en respectant la maquette de cette dernière.

## 3- Liens de recherche : 
#### Je me suis principalement aidé de la documention officielle de Tailwind qui est la suivante : 
#### https://tailwindcss.com/docs/installation
#### https://tailwindcss.com/docs
#### Je vous conseille également cette vidéo qui vous explique pas à pas mon raisonnement : 
#### https://www.loom.com/share/07495f9db19a4bf1a6ac914a48163c4d?sid=7c610c4e-aee6-4a16-8770-6989f745c114

## Merci à vous ! 
