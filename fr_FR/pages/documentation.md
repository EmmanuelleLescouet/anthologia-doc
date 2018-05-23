# Documentation

## Comment utiliser la plateforme Anthologia

La [plateforme Anthologia](https://anthologia.ecrituresnumeriques.ca) permet d'ajouter des informations à la base de données.

La plateforme est ouverte et disponible [ici](https://anthologia.ecrituresnumeriques.ca).

Depuis la plateforme il est possible (entre autre) d'ajouter et modifier:
- des épigrammes
- des traductions
- des mots-clés (motifs, genres, parcours de lectures, personnes citées etc.)
- des scholies
- des alignements (correspondance d'un texte avec sa traduction mot à mot)
- des images
- des notes
- des auteurs

### Connexion à la plateforme

Connectez-vous à la plateforme [ici](https://anthologia.ecrituresnumeriques.ca).

Si vous avez déjà un compte, cliquez sur "Login" en haut à droite de la page.

Si vous n'avez pas de compte, vous pouvez en créer en en cliquant sur "Register". Vous pourrez ensuite entrer dans la plateforme en insérant votre mail et votre mot de passe.

### Droits d'accès
Tout utilisateur peut ajouter des informations et modifier les informations qu'il a créées. Il n'est pas possible de modifier les informations créées par un autre utilisateur (à moins d'avoir des privilèges d'administrateur).
Si vous trouvez des erreurs dans la plateforme, veuillez [nous les signaler](mailto:crc.ecrituresnumeriques@gmail.com).

### La structure du site

Dans le menu de gauche vous pouvez accéder à l'ensemble des foctionnalités du site.

![menu](https://imgur.com/ng7Fz9Z)

- Entities: la page avec la liste des épigrammes disponibles dans la base (listées en ordre alphabétique). Depuis cette page vous pouvez ajouter de nouvelles épigrammes ou éditer les épigrammes existantes.
- Authors: la liste des poètes auteurs d'une ou plusieurs épigrammes
- Cities: la liste des villes citées dans des épigrammes ou dans lesquelles sont nés ou mort des poètes
- Languages: la liste des langues de la plateforme. Tout information peut être insérée en une ou plusieurs langues.
- Keyword Categories: les familles de mots-clés qui permettent de classifier les mots-clés. Un mot clé peut appartenir à une seule catégorie (et donc être, par exemple, un genre littéraire, un motif, une personne citées etc.)
- Keyword: les mots-clés
- Notes: les notes à une épigramme (notes critiques, observations, commentaires etc.)
- Les scholies: la transcription et la traduction des scholies présentes dans le manuscrit

Toute information disponible dans la base (épigramme, auteur, ville, mot-clé, traduction etc.) peut être trouvée via le moteur de recherche dans la page d'accueil.

### Créer une entité

Une entité est une épigramme. Chaque entité peut avoir plusieurs versions:
- plusieurs versions en grec (par exemple différentes éditions)
- plusieurs traductions dans différentes langues
- plusieurs versions de traductions dans la même langue

Chaque entité est alignée à l'uri Perseus (si le texte est disponible).

#### Récupérer le URI sur Perseus.

Allez sur l'édition [Perseus de l'Anthologie Palatine](http://www.perseus.tufts.edu/hopper/text?doc=urn:cts:greekLit:tlg7000.tlg001.perseus-grc1).
Le URI est le premier lien dans la colonne de droite.

![uri](https://imgur.com/DnAxUIO)

Concrètement le uri est structuré de la façon suivante :

http://www.perseus.tufts.edu/hopper/text?doc=urn:cts:greekLit:tlg7000.tlg001.perseus-grc1:NuméroLivre.NuméroÉpigramme

Par exemple, le premier épigramme du livre 4 sera :

http://www.perseus.tufts.edu/hopper/text?doc=urn:cts:greekLit:tlg7000.tlg001.perseus-grc1:4.1

le deuxième épigramme du livre 5 sera

http://www.perseus.tufts.edu/hopper/text?doc=urn:cts:greekLit:tlg7000.tlg001.perseus-grc1:5.2

Le URI permet de récupérer le texte grec mis à disposition par Perseus. C'est très important d'utiliser ce texte même s'il y a des erreurs, puisqu'il nous permet d'avoir une référence stable. Dans le cas où le texte contient des erreurs, il est possible d'insérer une deuxième version du texte grec, pour laquelle il faudra sélectionner la langue grec version usager.

#### Insertion de la traduction.

Pour chaque épigramme, on peut insérer plusieurs traductions. Sélectionnez la langue "français moderne". C'est préférable (même si pas obligatoire) que tout utilisateur n'insère qu'une seule traduction. Si vous désirez ajouter plusieurs traductions, vous pouvez le faire avec d'autres comptes utilisateurs.

#### Alignement de la traduction

Sélectionnez le texte grec que vous voulez aligner et ensuite la traduction à aligner. ATTENTION: c'est possible aligner seulement deux textes à la fois; si plusieurs textes sont sélectionnés vous ne pourrez pas les aligner. Une fois les deux textes sélectionnés, un bouton vert apparaîtra à droite; en y appuyant, vous pourrez procéder à l'alignement. Pour aligner, sélectionnez les mots grecs et ensuite les mots français. Appuyez sur le bouton vert pour valider l'alignement. Appuyez sur "send to server" pour enregistrer l'alignement proposé. Vous pouvez choisir la granularité de l'alignement : en général, la granularité la plus fine possible est préférable, mais parfois cela ne sera pas possible. Ça va de soi que l'alignement parfait n'existe pas, essayez pourtant d'aligner tous les mots.

#### Transcription des scholies

Appuyez sur su "Add new Scholie". Selezionate la lingua (αρχαία Ελληνικά) e inserite il testo greco. Se siete incerti sulla trascrizione, o se identificate due o tre interpretazioni possibili, potete aggiungere più volte lo stesso scolio - semplicemente facendo di nuovo "Add new Scholie" e selezionando la lingua greca. In questo caso è preferibile (ma non obbligatorio) che i due testi siano aggiunti da due users diversi.
#### Traduire les scholies

Cliquez sur "Add new scholie", sélectionnez la langue de la traduction et insérez le texte. Dans le cas où une épigramme aie plusieurs scholies, procédez de la même façon pour chaque scholie. À l'état actuel, la plateforme ne permet pas de relier de manière univoque un scholie et sa traduction. Dans un second temps, nous ajouterons manuellement cette information à la base des données : rarement une épigramme contient plus que deux scholies.

#### Ajouter des images.

Pour le moment, une image peut être liée seulement à des épigrammes (une ou plusieurs), mais non pas à un mot-clé.

Se connecter au compte imgur (voir plus haut) et téléverser l'image choisie. Copiez et collez le DIRECT LINK.

Ajoutez le titre et les crédits.
Exemple
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
