# Exercice P1 - Premiers pas sur le langage HTML avec repository

## Description

Vous allez créer le site internet Riding Cities et le stocker à distance soit sur GitHub ou GitLab.
L'objectif et de réaliser un versionning avec des branches.

## Table des Matières

1. [Étape 1  : Créez le repository](#étape-1--créez-le-repository)
2. [Étape 2  : Créez la structure du projet](#étape-2--créez-la-structure-du-projet)
3. [Étape 3 : Créez la branche ``develop``](#étape-3--créez-la-branche-develop)
4. [Étape 4 : Créez une issue](#étape-4--créez-une-issue)
5. [Étape 5  : Créez la structure HTML du fichier ``index.html``](#étape-5--créez-la-structure-html-du-fichier-indexhtml)
6. [Étape 6 : Remontez vos modifications à votre repository distant](#étape-6--remontez-vos-modifications-à-votre-repository-distant)
7. [Étape 7  : Renseignez le contenu de la balise ``head``](#étape-7--renseignez-le-contenu-de-la-balise-head)
8. [Étape 8 : Renseignez le contenu de la balise ``body``](#étape-8--renseignez-le-contenu-de-la-balise-body)
8.1. [Action 8.1 : Création d'un bloc container](#action-81--création-dun-bloc-container)
8.2. [Action 8.2 : Création du contenu du ``header``](#action-82--création-du-contenu-du-header)
9. [Étape 9 : Création du contenu du ``main``](#étape-9--création-du-contenu-du-main)
9.1. [Action 9.1 : Création de la section "La mission de l'asso"](#action-91--création-de-la-section-la-mission-de-lasso)
9.2. [Action 9.2 : Création de la section "Les membres fondateurs"](#action-92--création-de-la-section-les-membres-fondateurs)
9.3. [Action 9.3 : Création de la section "Découvrez nos cours !"](#action-93--création-de-la-section-découvrez-nos-cours)

## Étape 1 : Créez le repository

1. Créez le repository sur GitHub ou le projet sur GitLab avec le nom **riding-cities**
2. Clonez le repository ou le projet sur votre ordinateur

## Étape 2 : Créez la structure du projet 

1. Créez le dossier ``**riding-cities**``
2. Dans le dossier ``**riding-cities**``, créez les dossiers ``**css**``, ``**documents**``, ``**images**`` et le fichier ``**index.html**``
3. Dans le dossier ``**css**``, téléchargez le fichier ``**style.css**``
4. Téléchargez dans le dossier ``**documents**``, les fichiers pdf ``**planning-adultes.pdf**`` et ``**planning-enfants.pdf**``
5. Téléchargez dans le dossier ``**images**`` les images ``**header.png**``, ``**marc.png**``, ``**pedro.png**`` et ``**soraya.png**`` depuis [ la maquette figma](https://www.figma.com/file/zGXDzCQkosimKh08RlzUU2/Maquettes-Ride-Cities---Desktop?type=design&node-id=0%3A1&mode=design&t=kOwbqYRo7N7Mh66N-1). 

**Si vous n'arrivez pas à réaliser le point 5, alors télécharger le repository et récupérer les images.**

6. Réalisez un ``commit`` puis un ``push``. Pour réaliser un push sur GitLab il faut utiliser la commande `git push --set-upstream origin main`.

## Étape 3 : Créez la branche ``develop``

Vous allez réaliser du versonning à partir de la branche ``develop``. A partir de cette branche vous allez créer des issues en lien avec les étapes / actions ci-dessous que vous devrez merger dans un premier temps sur la branche develop puis sur la branche principale main ou master.

1. Créez la branche ``develop`` au travers de votre terminal. Soit directement dans le terminal de votre IDE ou dans le terminal de votre ordinateur ou avec git bash.
2. Basculez sur la branche ``develop``

## Étape 4 : Créez les issues

1. Créez les issues en lien avec les étapes 5, 7 et les actions 8.1, 8.2, 9.1, 9.2 et9.3 
- Mettez dans le champ **title** l'intitulé de l'étape
- Sélectionnez **issue** dans le champ **type**
- Mettez dans **description** le contenu de l'étape

## Étape 5 : Créez la structure HTML du fichier **``index.html``**

1. Ouvrez le dossier **``riding-cities`**` dans votre IDE favoris (exemple VS Code)
2. Ouvrez le fichier **``index.html``** et insérez la structure de base HTML5
3. Indiquez la langue **``fr``** dans l'attribut ``lang`` de la balise ``html``

## Étape 6 : Remontez vos modifications à votre repository distant

Dans cette étape, vous allez lier l'issue aux modifications que vous remontez à votre repository distant.
1. Enregistrez les modifications via la commande `git add .`
2. Réalisez un ``commit`` avec la commande `git commit -m "Création de la structure HTML du fichier index.html #1"`. Ici **#1** correspond au numéro de l'issue qu'il faut solder.
3. Réalisez un ``push``
4. Basculez sur la branche ``main`` puis réalisez un ``merge`` de la branche ``develop``
5. Rendez-vous sur votre repository et exécutez une ``pull request`` pour GitHub et une ``new merge request`` pour GtiLab
6. Cloturez l'issue depuis votre repository

## Étape 7 : Renseignez le contenu de la balise ``head``

1. Basculez sur la branche ``develop``
2. Remplacez le contenu de la balise ``title`` par **Riding Cities**
3. Ajoutez les lignes de code ci-dessous
```html
<link rel="stylesheet" type="text/css" href="css/style.css">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Archivo:wght@400;500;600;800;900&family=Inter:wght@900&display=swap" rel="stylesheet">
```
4. Remontez vos modifications à votre repository distant. Reprenez ici ce que vous avez réalisé à l'[Étape 6](#étape-6--remontez-vos-modifications-à-votre-repository-distant)

## Étape 8 : Renseignez le contenu de la balise ``body``

### Action 8.1 : Création d'un bloc container

Vous allez ici créer une div container qui contiendra tout le contenu de la page :
1. Basculez sur la branche ``develop``
2. Créer une balise ``div`` avec la classe **container** (exemple : `<div class="nomClass"> ... </div>`)
3. Dans la balise ``div``, créez les balises ``header`` et ``main``

- La balise ``header`` représente l'en-tête de notre site. Le ``header`` se répéte sur l'ensemble des pages du site et on y retrouve généralement le logo et menu de navigation du site. Tout comme le ``footer`` qui représente le pied de page du site et qui se répéte sur l'ensemble des pages d'un site.
- La balise ``main`` représente le contenu principal de la page. Elle se trouve entre les balises ``header` et ``footer``.

4. Remontez vos modifications à votre repository distant. Reprenez ici ce que vous avez réalisé à l'[Étape 6](#étape-6--remontez-vos-modifications-à-votre-repository-distant) associé au bon numéro de l'issue.

### Action 8.2 : Création du contenu du ``header``

Vous allez construire le **header** avec une image et le titre principal de la page :
1. Basculez sur la branche ``develop``
2. Créez une balise ``img`` qui pointe vers l'image **header.png**. Veillez à bien renseigner les attributs **src** (il est important de renseigner un chemin relatif ) et **alt** (à vous de trouver quelque chose de pertinent).
3. Créez une balise ``div`` avec comme classe **headerTextContent**
4. Créez une balise de titre principal avec le contenu **RIDING CITIES** dans la ``div`` précédante
5. Remontez vos modifications à votre repository distant. Reprenez ici ce que vous avez réalisé à l'[Étape 6](#étape-6--remontez-vos-modifications-à-votre-repository-distant) associé au bon numéro de l'issue.

## Étape 9 : Création du contenu du ``main``

### Action 9.1 : Création de la section "La mission de l'asso"

Vous allez dans un premier temps créer une section qui décrit **la mission de l'asso**. 
Cette section est constituée d'un titre et d'une ligne de 4 colonnes d'article. Chaque article est composé d'un titre et d'un paragraphe.

1. Basculez sur la branche ``develop``
2. Créez une balise ``section``
3. Dans la balise ``section``, créez une balise de titre secondaire _(**attention à respecter la hiérarchisation des titres**)_ avec le contenu **La mission de l'asso** et une balise ``div`` avec comme classe **directionRow**
4. Dans la balise ``div``, créer une balise ``article``
5. Dans la balise ``article``, créez une balise de titre secondaire _(**attention à respecter la hiérarchisation des titres**)_ avec le contenu du titre de la 1ère colonne de la maquette et une balise de type paragraphe avec comme le contenu du paragraphe de la 1ère colonne de la maquette
6. Dupliquez 3 fois l'article précédent et modifiez le titre et le paragraphe selon le contenu de la maquette.
7. Remontez vos modifications à votre repository distant. Reprenez ici ce que vous avez réalisé à l'[Étape 6](#étape-6--remontez-vos-modifications-à-votre-repository-distant) associé au bon numéro de l'issue.

### Action 9.2 : Création de la section "Les membres fondateurs"

Vous allez maintenant créer la deuxième section qui présente **Les membres fondateurs** de l'association. 
Cette section est constituée d'un titre et d'une ligne de 3 colonnes d'article. Chaque article est composé d'une image, d'un titre et d'un paragraphe.

1. Basculez sur la branche ``develop``
2. Dupliquez la section précédente et ajoutez les classes **"sectionLinearGradientBackground whiteContentSection textCenter"**
3. Supprimez un article
4. Ajoutez les images des membres avant le titre de l'article enrespectant l'ordre de la maquette
5. Modifiez le titre et le paragraphe correspondant à la maquette
6. Remontez vos modifications à votre repository distant. Reprenez ici ce que vous avez réalisé à l'[Étape 6](#étape-6--remontez-vos-modifications-à-votre-repository-distant) associé au bon numéro de l'issue.

### Action 9.3 : Création de la section "Découvrez nos cours !"
Il ne vous reste plus que la dernière section **Découvrez nos cours !**.
Cette section est composé d'un titre et de deux boutons cliquables affichant le planning des cours adultes et enfants se trouvant dans le dossier documents.

1. Basculez sur la branche ``develop``
2. Créez une section associée aux classes **"sectionLightGreyBackground directionColumn"**
3. Créez un titre avec le texte de la maquette
4. Créez un lien hypertexte qui ouvre les plannings dans un nouvel du navigateur
5. Ajouter les classes **"button buttonHighlight buttonMainColor buttonRounded"** au permier lien hypertexte
6. Ajouter les classes **"button buttonHighlight buttonSecondColor buttonRounded"** au deuxième lien hypertexte
7. Remontez vos modifications à votre repository distant. Reprenez ici ce que vous avez réalisé à l'[Étape 6](#étape-6--remontez-vos-modifications-à-votre-repository-distant) associé au bon numéro de l'issue.

Et voilà ! Vous avez créé votre premier site internet en HTML. Félicitation ! 
