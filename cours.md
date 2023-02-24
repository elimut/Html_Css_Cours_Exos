#HTML CSS

Bases du web
Langages informatiques de création de sites WEB.

>**HTML**: *Hypertext Markup Language*.
>Description contenu , différent programmation = langage de balisage.
**CSS**: *Cascading Style Sheets (feuille de style en cascade). Application style aux éléments HTML.

##HTML:

###Balises et attributs :

<></> Balise paire
<> Balise orpheline ou (</>)
 -> indiquent nature du texte qu'elles encadrent.
Navigateur comprend ce qu'il doit afficher.

Une balise ouverte dans une autre, doit être fermée dans celle-ci : éléments dits "parent" qui conteinnent des éléments dits "enfants".

>**Balise sémantique**: indique contenu de ce qu'elles encadrent.

>**Attributs**: Complètent balises en donnant des infos supplémentaires.

        <balise attribut="valeur">

Indentation de 4 en HTML.

Dossier contient fichiers avec :
ext .html et ext .css, permet modifier style sans toucher au contenu.
(nav affichent par défaut,maj style avec CSS)

1ère page du site : index.html

Tous les "link" avant balise "Title" (si trop de link page longue à charger//lecture synchrone, de haut en bas):

        <meta>
        <link>
        <title>

        <!Doctype html>(!ent)
        ->spécifie ce en quoi on écrit,début du code
        <html.lang="">
        ->langue par défaut du site, fr-FR: français de France
        <head>
        <meta>
        </meta>
        <link>
        <title>
        </head>
        ->métadonnées, intelligence". donne info aux nav (encodage=métacharset;titre page dans onglet google et recherche...)
        <body>
        </body>
        ->affiché à l'écran
        </html>
        ->fin du code







