<a name="top"></a>
# virtual-pin-pad
Application réalisée en équipe dans le cadre de ma formation Java / C# / .net.
Le but du projet est de prendre en main un projet en équipe, découvrir github, les méthodes agiles, apprendre à analyser les besoins du client à partir desquels l'on va définir des tâches à réaliser pour proposer une solution finale au client final.

# Sommaire
- [virtual-pin-pad](#virtual-pin-pad)
- [Sommaire](#sommaire)
- [Équipe](#équipe)
    - [Nom de l'équipe et signification](#nom-de-léquipe-et-signification)
    - [Composition du groupe](#composition-du-groupe)
    - [Nom du scrum master](#nom-du-scrum-master)
- [Contexte du projet](#contexte-du-projet)
- [Réalisation et différentes étapes du projet](#réalisation-et-différentes-étapes-du-projet)
  - [Sprint 0](#sprint-0)
    - [Restrictions](#restrictions)
    - [Tâches réalisées](#tâches-réalisées)
    - [Dessiner un croquis représentant les besoins du client](#dessiner-un-croquis-représentant-les-besoins-du-client)
    - [Réaliser un wireframe](#réaliser-un-wireframe)
        - [Quel outil avons-nous utilisé et pourquoi?](#quel-outil-avons-nous-utilisé-et-pourquoi)
    - [Réaliser une maquette statique](#réaliser-une-maquette-statique)
- [Définitions](#définitions)
  - [Générique](#générique)
    - [`Github`](#github)
    - [`Repository`](#repository)
    - [`La méthode agile Kanban`](#la-méthode-agile-kanban)
    - [`Quel est le rôle du Product Owner`](#quel-est-le-rôle-du-product-owner)
  - [HTML/CSS](#htmlcss)
    - [`A quoi sert le doctype__?`](#a-quoi-sert-le-doctype__)
    - [`A quoi servent les entêtes dans un document HTML?`](#a-quoi-servent-les-entêtes-dans-un-document-html)
    - [`A quoi sert l’entête __meta viewport__?`](#a-quoi-sert-lentête-__meta-viewport__)
    - [`Pourquoi est-il recommandé d’avoir les styles dans un fichier à part?`](#pourquoi-est-il-recommandé-davoir-les-styles-dans-un-fichier-à-part)
    - [`Expliquer le __modèle de boîtes en CSS__?`](#expliquer-le-__modèle-de-boîtes-en-css__)
    - [`Qu’est-ce qu’un __sélecteur CSS__?`](#quest-ce-quun-__sélecteur-css__)
    - [`Qu’est-ce qu’une __propriété CSS__?`](#quest-ce-quune-__propriété-css__)
    - [`Liste des principaux liens utilisés pour s’aider à réaliser la maquette HTML/CSS?`](#liste-des-principaux-liens-utilisés-pour-saider-à-réaliser-la-maquette-htmlcss)

# Équipe
### Nom de l'équipe et signification
Notre équipe se nomme __SRP__, qui est l'un des principes __SOLID__, qui regroupe cinq principes de conception destinés à produire des architectures logicielles plus compréhensibles, flexibles et maintenables.
__SRP__ signifie en Anglais `sigle responsibility principle`, ce qui veut dire, dans la programmation orientée objet (__POO__), que chaque classe doit avoir sa propre responsabilité et une seule préoccupation.
### Composition du groupe
Le groupe est composé de 3 développeurs, zhiying, Françis et de moi, Jérôme.
### Nom du scrum master
Le scrum master de l'équipe est Jérôme.

[⬆️ Haut de la page](#top)

# Contexte du projet
Dans le cadre d’un PoC (Proof of Concept) notre client souhaite développer un prototype d’écran de saisie de code PIN à des fins d’authentification ou de paiement utilisable dans différentes applications.
# Réalisation et différentes étapes du projet
## Sprint 0
__Proposer un wireframe de l'application puis une maquette Web statique pour valider la compréhension des besoins.__

### Restrictions
- Il doit y avoir une seule page HTML, un seul fichier CSS
- Organiser son code
- La page doit s’adapter au périphérique
- Rester le plus fidèle possible au croquis et au wireframe validé.
### Tâches réalisées
1. Définir les besoins du client.
2. Dessiner un croquis à la main représentant l'application.
3. A partir du croquis, réaliser un wireframe avec l'outil de notre choix.
4. A partir du wireframe, réaliser une interface statique en HTML et CSS.

 [⬆️ Haut de la page](#top)

### Dessiner un croquis représentant les besoins du client
Le croquis représente une première esquisse qui permet de représenter les besoins du clients. Le fait de la faire sur du papier, permet de la modifier plus facilement, et de l'adapter en cas de mauvaise compréhension des besoins, ou si elle ne convient pas au product Owner.

<img src='https://user-images.githubusercontent.com/49954831/141993313-ea1dc7f4-cc22-4fc1-ad61-93e2fc1fc05e.jpg' width='300px' />

[⬆️ Haut de la page](#top)

### Réaliser un wireframe
Le wireframe est une représentation graphique basique de l'application, qui pourra être présenté au client, et qui contient les éléments de base et le contenu.
##### Quel outil avons-nous utilisé et pourquoi?
Pour réaliser le wireframe de l'application, nous avons utilisé un outil en ligne nommé __mockflow__, car c'est un outil gratuit, simple d'utilisation et qui permet de réaliser des wireframe complexes.

<img src='https://user-images.githubusercontent.com/49954831/141995583-a0df1baf-1a44-4230-93c3-ddf8faee307c.png' width='300px' />

### Réaliser une maquette statique
> A partir du wireframe, développer la maquette statique de l'application.

[⬆️ Haut de la page](#top)

# Définitions
<a name="générique"></a>
## Générique
### `Github`
GitHub permet aux développeurs de stocker et de partager, publiquement ou non, le code qu’ils créent.
Chaque utilisateur peut contribuer aux projets mis en ligne publiquement en proposant des modifications.
### `Repository`
Un __repository__ est un dépôt de stockage centralisée dans lequel est stocké les données des projets, ainsi que les différentes versions du code auquels l'on peut accéder au besoin.
### `La méthode agile Kanban`
Kanban met en avant le découpage des fonctionnalités en tâches, et utilise un tableau afin de visualiser facilement l'avancement des tâches et leurs priorités. Elle met l'accent sur la responsabilité de chacun des développeurs composant l'équipe.

__Quel est l'intérêt de diviser son travail en tâches, de les prioriser ?__
> Cela permet de réduire la compléxité des tâches et de pouvoir mieux les identifier. L'on va traiter les tâches prioritaires en premier.

__Quel est le but dans une équipe d’avoir un tableau de suivi partagé entre les membres d’une équipe ?__
> Cela facilite le travail en équipe, suivre l'avancement des tâches et permet d'identifier facilement leurs priorités.

### `Quel est le rôle du Product Owner`
Le __product owner__ est l'intermédiaire entre le client, le scrum master et les développeurs.
C'est un peu comme un chef de projet en mode agile. Il est en charge de satisfaire les besoins des clients en menant à bien la livraison d'un produit de qualité.

[⬆️ Haut de la page](#top)

## HTML/CSS
### `A quoi sert le doctype__?`
Le doctype sert à déterminer quel comportement le navigueur doit appliquer pour afficher la page web. Actuellement pour HTML 5, `<!DOCTYPE html>` est le standard à utiliser. Pour les navigateurs les plus anciens, il faudra appliquer le doctype adapté afin que le navigateur en émule le comportement.
### `A quoi servent les entêtes dans un document HTML?`
Les entêtes HTML sont placées entre les balises `head` du fichier hTML. Elles contiennent nottament des informations sur la page comme des métas-données(titre, description, mots clés), les feuilles de style importées. Elles sont aussi utiles pour un meilleur référencement dans les moteurs de recherche.
### `A quoi sert l’entête __meta viewport__?`
L'entête `meta viewport` permet de contrôler l'affichage sur plusieurs types d'écrans. On peut y définir des valeurs pour certaines largeurs ou hauteurs d'écrans, ainsi que de définir le mode de zoom initial.
### `Pourquoi est-il recommandé d’avoir les styles dans un fichier à part?`
Cela permet d'éviter les répétitions de code, de ne pas surcharger les fichiers HTML pour une meilleure lisibilité. Cela évite également d'avoir à changer dans chaque fichier le style s'il est utilisé à plusieurs endroits.

[⬆️ Haut de la page](#top)

### `Expliquer le __modèle de boîtes en CSS__?`
Le __modèle de boîte__ en css permet de définir comment sont positionnés les éléments de la page en fonction des balises sur lesquelles ils sont impliqués. Chaque élément sur une page représente une boîte, il existe des boîtes de type __bloc__, d'autres de type __inline__, et les éléments ne gère pas de la même manière leurs dimensionnements, ou leur espacements.
### `Qu’est-ce qu’un __sélecteur CSS__?`
Un sélecteur CSS permet de cibler quel élément sur la page HTML va être stylisé. Il est entouré d'accolades et peut contenir plusieurs proriétés et leurs valeurs CSS associées.
### `Qu’est-ce qu’une __propriété CSS__?`
Une propriété CSS permet de modifier une propriété de l'élément ciblé par le sélecteur CSS (taille, couleur, espacement, etc...)
### `Liste des principaux liens utilisés pour s’aider à réaliser la maquette HTML/CSS?`
- https://css-tricks.com/snippets/css/complete-guide-grid/ `Informations sur grid`
- https://developer.mozilla.org/fr/ `Informations diverses`

[⬆️ Haut de la page](#top)
