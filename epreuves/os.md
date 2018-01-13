### OS

Vous devez coder `YoloArchiveur`, qui est un archiveur et un désarchiveur en utilisant un algorithme de RLE (https://en.wikipedia.org/wiki/Run-length_encoding).  
L'archiveur doit être en mesure d'archiver un fichier ou un réptertoire.    

Pour utiliser l'archiveur, il faut y procéder comme ceci:  
`./yoloArchiveur -a monFichier -o yolo.archive`  
où l'argument `-a` représente un fichier à archiver et où `-o` représente le nom de l'archive créé.    

`./yoloArchiveur -ar /etc -o yolo.archive`  
où l'argument `-ar` représente un répertoire à archiver.    

`./yoloArchiveur -x yolo.archive`  
où `-x` signifie qu'on veut désarchiver le contenu de yolo.archive   

#### Règles
`YoloArchiveur` doit être codé en C et fonctionner sous Linux. Vous n'avez pas à gérer les liens symboliques ou autres trucs complexes.  
Pas de librairies externes, doit venir avec les sources et un `Makefile`.
