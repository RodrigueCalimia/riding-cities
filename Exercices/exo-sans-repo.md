# Exercice P1 - Premiers pas sur le langage HTML sans repository

## Description

Vous allez créer le site internet Riding Cities en local sans repository.

## Table des Matières

1. [Étape 1  : Créez la structure du projet](#étape-1--créez-la-structure-du-projet)
2. [Étape 2  : Créez la structure HTML du fichier ``index.html``](#étape-2--créez-la-structure-html-du-fichier-indexhtml)
3. [Étape 3  : Renseignez le contenu de la balise ``head``](#étape-3--renseignez-le-contenu-de-la-balise-head)
4. [Étape 4 : Renseignez le contenu de la balise ``body``](#étape-4--renseignez-le-contenu-de-la-balise-body)
4.1. [Action 4.1 : Création d'un bloc container](#action-41--création-dun-bloc-container)
4.2. [Action 4.2 : Création du contenu du ``header``](#action-42--création-du-contenu-du-header)
5. [Étape 5 : Création du contenu du ``main``](#étape-5--création-du-contenu-du-main)
5.1. [Action 5.1 : Création de la section "La mission de l'asso"](#action-51--création-de-la-section-la-mission-de-lasso)
5.2. [Action 5.2 : Création de la section "Les membres fondateurs"](#action-52--création-de-la-section-les-membres-fondateurs)
5.3. [Action 5.3 : Création de la section "Découvrez nos cours !"](#action-53--création-de-la-section-découvrez-nos-cours)

## Étape 1  : Créez la structure du projet 

1. Créez le dossier ``**riding-cities**``
2. Dans le dossier ``**riding-cities**``, créez les dossiers ``**css**``, ``**documents**``, ``**images**`` et le fichier ``**index.html**``
3. Dans le dossier ``**css**``, téléchargez le fichier ``**style.css**``
4. Téléchargez dans le dossier ``**documents**``, les fichiers pdf ``**planning-adultes.pdf**`` et ``**planning-enfants.pdf**``
5. Téléchargez dans le dossier ``**images**`` les images ``**header.png**``, ``**marc.png**``, ``**pedro.png**`` et ``**soraya.png**`` depuis [ la maquette figma](https://www.figma.com/file/zGXDzCQkosimKh08RlzUU2/Maquettes-Ride-Cities---Desktop?type=design&node-id=0%3A1&mode=design&t=kOwbqYRo7N7Mh66N-1). 

**Si vous n'arrivez pas à réaliser le point 5, alors télécharger le repository sur votre ordinateur et récupérer les images.**

## Étape 2  : Créez la structure HTML du fichier ``index.html``

1. Ouvrez le dossier ``**riding-cities**`` dans votre IDE favoris (exemple VS Code)
2. Ouvrez le fichier ``**index.html**`` et insérez la structure de base HTML5
3. Indiquez la langue **fr** dans l'attribut ``lang`` de la balise ``html``

## Étape 3  : Renseignez le contenu de la balise ``head``

1. Remplacez le contenu de la balise ``title`` par **Riding Cities**
2. Ajoutez les lignes de code ci-dessous
```html
<link rel="stylesheet" type="text/css" href="css/style.css">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Archivo:wght@400;500;600;800;900&family=Inter:wght@900&display=swap" rel="stylesheet">
```

## Étape 4 : Renseignez le contenu de la balise ``body``

### Action 4.1 : Création d'un bloc container

Vous allez ici créer une div container qui contiendra tout le contenu de la page :
1. Créer une balise ``div`` avec la classe **container** (exemple : `<div class="nomClass"> ... </div>`)
2. Dans la balise ``div``, créez les balises ``header`` et ``main``

- La balise ``header`` représente l'en-tête de notre site. Le ``header`` se répéte sur l'ensemble des pages du site et on y retrouve généralement le logo et menu de navigation du site. Tout comme le ``footer`` qui représente le pied de page du site et qui se répéte sur l'ensemble des pages d'un site.
- La balise ``main`` représente le contenu principal de la page. Elle se trouve entre les balises ``header` et ``footer``.

### Action 4.2 : Création du contenu du ``header``

Vous allez construire le **header** avec une image et le titre principal de la page :
1. Créez une balise ``img`` qui pointe vers l'image **header.png**. Veillez à bien renseigner les attributs **src** (il est important de renseigner un chemin relatif ) et **alt** (à vous de trouver quelque chose de pertinent).
2. Créez une balise ``div`` avec comme classe **headerTextContent**
3. Créez une balise de titre principal avec le contenu **RIDING CITIES** dans la ``div`` précédante

## Étape 5 : Création du contenu du ``main``

### Action 5.1 : Création de la section "La mission de l'asso"

Vous allez dans un premier temps créer une section qui décrit **la mission de l'asso**. 
Cette section est constituée d'un titre et d'une ligne de 4 colonnes d'article. Chaque article est composé d'un titre et d'un paragraphe.

1. Créez une balise ``section``
2. Dans la balise ``section``, créez une balise de titre secondaire _(**attention à respecter la hiérarchisation des titres**)_ avec le contenu **La mission de l'asso** et une balise ``div`` avec comme classe **directionRow**
3. Dans la balise ``div``, créer une balise ``article``
4. Dans la balise ``article``, créez une balise de titre secondaire _(**attention à respecter la hiérarchisation des titres**)_ avec le contenu du titre de la 1ère colonne de la maquette et une balise de type paragraphe avec comme le contenu du paragraphe de la 1ère colonne de la maquette
5. Dupliquez 3 fois l'article précédent et modifiez le titre et le paragraphe selon le contenu de la maquette.

### Action 5.2 : Création de la section "Les membres fondateurs"

Vous allez maintenant créer la deuxième section qui présente **Les membres fondateurs** de l'association. 
Cette section est constituée d'un titre et d'une ligne de 3 colonnes d'article. Chaque article est composé d'une image, d'un titre et d'un paragraphe.

1. Dupliquez la section précédente et ajoutez les classes **"sectionLinearGradientBackground whiteContentSection textCenter"**
2. Supprimez un article
3. Ajoutez les images des membres avant le titre de l'article enrespectant l'ordre de la maquette
4. Modifiez le titre et le paragraphe correspondant à la maquette

### Action 5.3 : Création de la section "Découvrez nos cours !"
Il ne vous reste plus que la dernière section **Découvrez nos cours !**.
Cette section est composé d'un titre et de deux boutons cliquables affichant le planning des cours adultes et enfants se trouvant dans le dossier documents.

1. Créez une section associée aux classes **"sectionLightGreyBackground directionColumn"**
2. Créez un titre avec le texte de la maquette
3. Créez un lien hypertexte qui ouvre les plannings dans un nouvel du navigateur
4. Ajouter les classes **"button buttonHighlight buttonMainColor buttonRounded"** au permier lien hypertexte
5. Ajouter les classes **"button buttonHighlight buttonSecondColor buttonRounded"** au deuxième lien hypertexte

Et voilà ! Vous avez créé votre premier site internet en HTML. Félicitation ! 
