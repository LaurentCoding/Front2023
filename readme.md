

## Techno 
Vanilla JS -> Que du JS sans librairie ni framework SASS

## SYSTEME DE ROUTING 
Pour ajouter une page, il faut ajouter le fichier html dans le dossier pages
Ensuite, il faut configurer la route dans le fichier router.js (la variable route) 
Il faut ajouter un ligne suivant ce fonctionnement : 
principe : "/route": "/pages/monFichier.html" 
exemple : "/route": "pathToFileHtml"

Pour inlcure un fichier js dans cette route, il faut modifier la variable routeJS du fichier router.js 
Il faut ajouter un ligne suivant ce fonctionnement : 
principe : "/route": "js/monFichier.js" 
exemple : "/route": "pathToFilejs"