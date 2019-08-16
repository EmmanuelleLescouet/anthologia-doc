# Documentation

## Utilisation de la plateforme *Anthologia*

La [plateforme Anthologia](https://anthologia.ecrituresnumeriques.ca) permet d'ajouter et d'éditer des informations à la base de données du projet. Ces informations ajoutées peuvent concerner une épigramme issue de l'AP, mais peuvent également consister en l'édition d'un texte étranger à l'Anthologie (comme c'est le cas avec un [extrait du chant 23 de l'*Iliade*](https://anthologia.ecrituresnumeriques.ca/entities/441))

La plateforme est ouverte en écriture comme en lecture et est disponible [ici](https://anthologia.ecrituresnumeriques.ca).

Depuis la plateforme, après création d'un compte utilisateur, il est possible d'effectuer les action suivantes :
- édition des épigrammes
- édition des traductions
- renseignement des mots-clés (motifs, genres, parcours de lectures, personnes citées etc.)
- édition des scholies
- création des alignements (correspondance d'un texte avec sa traduction mot à mot)
- ajout des images du manuscrit
- édition des notes
- renseignement des auteurs
- ajout de références internes
- ajout de références externes ou *liens faibles* [1].

**Important :** Étant donnée que la plateforme se présente en langue anglaise, il est recommandé d'ajouter et d'éditer les informations en anglais afin de préserver la cohérence linguistique du site et de ne pas créer de doublons. 

## Connexion à la plateforme

Afin d'éditer dans la plateforme, veuillez vous connecter [ici](https://anthologia.ecrituresnumeriques.ca).

Si vous avez déjà un compte, cliquez sur "Login" en haut à droite de la page.

Si vous n'avez pas de compte, vous pouvez en créer en en cliquant sur "Register". Vous pourrez ensuite entrer dans la plateforme en renseignant votre mail et votre mot de passe.

## Droits d'accès

Tout utilisateur peut ajouter des informations et modifier ces informations. Il n'est pas possible de modifier les informations créées par un autre utilisateur (à moins d'avoir des privilèges d'administrateur).
Si vous trouvez des erreurs dans la plateforme, veuillez [nous les signaler](mailto:crc.ecrituresnumeriques@gmail.com).

## La structure du site

Dans le menu de gauche vous pouvez accéder à l'ensemble des foctionnalités du site.

![menu](https://i.imgur.com/ng7Fz9Z.png?2)

- *Entities* : la page avec la liste des épigrammes disponibles dans la base (listées en ordre alphabétique). Depuis cette page vous pouvez ajouter de nouvelles épigrammes ou éditer les épigrammes existantes.
- *Authors* : la liste des poètes auteurs d'une ou plusieurs épigrammes
- *Cities*: la liste des villes citées dans des épigrammes ou dans lesquelles sont nés ou mort des poètes
- *Languages* : la liste des langues de la plateforme. Tout information peut être insérée en une ou plusieurs langues.
- *Keyword Categories* : les familles de mots-clés qui permettent de classifier les mots-clés. Un mot clé peut appartenir à une seule catégorie (et donc être, par exemple, un genre littéraire, un motif, une personne citées etc.)
- *Keyword* : les mots-clés
- *Notes* : les notes à une épigramme (notes critiques, observations, commentaires etc.)
- *Les scholies* : la transcription et la traduction des scholies présentes dans le manuscrit.

Toute information disponible dans la base (épigramme, auteur, ville, mot-clé, traduction etc.) peut être trouvée via le moteur de recherche disponible dans la page d'accueil.

## Les entités

Une entité correspond à une épigramme. Chaque entité peut avoir plusieurs versions :
- plusieurs versions en grec (provenant par exemple différentes éditions)
- plusieurs traductions dans différentes langues (à ce jour la plateforme présente des traductions en anglais, français et italien)
- plusieurs versions de traductions dans la même langue.

Chaque entité est alignée à l'URI Perseus (sous réserve de la disponibilité du texte).

## Récupérer le URI sur Perseus.

Allez sur l'édition [Perseus de l'Anthologie Palatine](http://www.perseus.tufts.edu/hopper/text?doc=urn:cts:greekLit:tlg7000.tlg001.perseus-grc1).
Le URI est le premier lien dans la colonne de droite.

![uri](https://i.imgur.com/DnAxUIO.png?1)

Concrètement le URI est structuré de la façon suivante :

http://www.perseus.tufts.edu/hopper/text?doc=urn:cts:greekLit:tlg7000.tlg001.perseus-grc1:NuméroLivre.NuméroÉpigramme

Par exemple, le premier épigramme du livre 4 sera :

http://www.perseus.tufts.edu/hopper/text?doc=urn:cts:greekLit:tlg7000.tlg001.perseus-grc1:4.1

le deuxième épigramme du livre 5 sera :

http://www.perseus.tufts.edu/hopper/text?doc=urn:cts:greekLit:tlg7000.tlg001.perseus-grc1:5.2

Le URI permet de récupérer le texte grec mis à disposition par Perseus. Il est important d'utiliser ce texte même s'il comporte des erreurs (que vous pouvez alors signaler à l'[équipe de Perseus](mailto:perseus_webmaster@tufts.edu), puisqu'il nous permet d'avoir une référence stable. Dans le cas où le texte contient des erreurs, il est possible d'insérer une deuxième version du texte grec, pour laquelle il faudra sélectionner la langue grecque "version usager".

## Insertion de la traduction.

Pour chaque épigramme, on peut insérer plusieurs traductions. Sélectionnez la langue "français moderne". C'est préférable (même si pas obligatoire) que tout utilisateur n'insère qu'une seule traduction. Si vous désirez ajouter plusieurs traductions, vous pouvez le faire avec d'autres comptes utilisateurs.

## Alignement de la traduction

Sélectionnez le texte grec que vous voulez aligner et ensuite la traduction à aligner. 

**Important :** il n'est possible d'aligner que deux textes à la fois ; si plusieurs textes sont sélectionnés vous ne pourrez pas les aligner. 

Une fois les deux textes sélectionnés, un bouton vert apparaîtra à droite ; en y appuyant, vous pourrez alors procéder à l'alignement. Pour aligner, sélectionnez les mots dans la langue d'origine et ensuite les mots dans la langue de traduction. Appuyez sur le bouton vert pour valider l'alignement. Appuyez sur "send to server" afin d'enregistrer l'alignement proposé. Vous pouvez également choisir la granularité de l'alignement : en règle générale, la granularité la plus fine possible est préférable, mais parfois cela n'est pas possible. 

## Édition des scholies

Appuyez sur su "Add new Scholie". 

Sélectioner ensuite la langue de la scholie (par exemple αρχαία Ελληνικά) et insérer le texte de la scholie. 

**Important :** en raison de la multiplicité des interprétations possibles des textes antiques, il est préférable d'identifier l'utilisateur à l'origine de l'édition. 

Pour éditer la traduction de la scholie, cliquez sur "Add new scholie", sélectionnez la langue de la traduction et insérez le texte.

Dans la mesure où une épigramme peut avoir plusieurs scholies, il vous faut procéder ainsi pour chaque nouvelle scholie éditée. 

En l'état actuel, la plateforme ne permet pas encore de relier de manière univoque une scholie et sa traduction [2].

## Ajouter des images

Pour ajouter une image à l'épigramme, il vous faut vous connecter à votre compte [Imgur](https://imgur.com/) et téléverser l'image choisie. Copiez et collez le DIRECT LINK de l'image ajoutée à votre compte.

**Important :** Il est nécessaire de renseigner le titre ET les crédits à l'image que vous ajoutez.

En l'état actuel, il est seulement possible de lier une image à une ou des épigrammes. Il sera prochainement possible de lier une image à un ou des mot-clés. 

## Exemple
Épigramme 5.1

URI: http://www.perseus.tufts.edu/hopper/text?doc=urn:cts:greekLit:tlg7000.tlg001.perseus-grc1:5.1

Texte grec (automatiquement récupéré sur Perseus ):

νέοις ἀνάπτων καρδίας σοφὴν ζέσιν,====
ἀρχὴν Ἔρωτα τῶν λόγων ποιήσομαι:
πυρσὸν γὰρ οὗτος ἐξανάπτει τοῖς νέοις.

Traduction en français moderne :

Enflammant le cœur des jeunes avec une ferveur savante, je ferai que l’Amour soit le commencement de ces discours ; c’est lui, en effet, qui allume le flambeau pour les jeunes
Scholies :

1. φεύγετε νέοι παῖδα Κυθήρης τοξοβόλον ἒρωτα
ἐπιγράμματα ἓρωτικα διαφορων ποιητων

2. ἀρχὴ τῶν επιγραμματων ερωτικων

Genre :

 Érotique

Époque :

Byzantine

Forme métrique :

Trimètre ïambique

Personnages mentionnés :

Aucun
Motifs :

Jeunes

Images :

## Les données

Les données sont exposées en json. L'uri de chaque objet est disponible sur la Plateforme *Anthologia*.

Par exemple:
http://anthologia.ecrituresnumeriques.ca/api/v1/entities donne la liste de toutes les entités

anthologia.ecrituresnumeriques.ca/api/v1/entities86 donne toutes les informations sur l'entité avec id 86

![entites86](https://i.imgur.com/ut5mis9.png)

[1]: Certaines actions, comme la suppression d'un fragment, ne sont accessibles qu'aux utilisateurs-administrateurs du projet. 

[2]: Il est cependant rare qu'une épigramme contienne plus d'une scholie. 
