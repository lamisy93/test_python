# test_python

Durée de la lecture et de l'écriture d'un fichier csv en python : moins de 10 min

Durée des recherches dans la doc (+ tuto) et du débuggage pour résoudre le problème que je rencontrais sur mon premier code test : 1h environ

Difficultés rencontrées au niveau de l'affichage de toutes les valeurs des champs Siren et NIC dans le fichier resultat.csv. 
Je rencontrais des problèmes dans ma boucle for qui affichait uniquement les champs Siren;NIC ainsi que la dernière ligne de ces deux colonnes [row[0], row[1]]. 
Pour remédier au problème, j'ai repris le code à zéro pour tester une syntaxe légèrement différente, un code mieux indenté, et utilisé le filtre del afin de garder toutes les données souhaitées et d'effacer le reste, ce qui a fonctionné directement. 
La même boucle ne donnait pas le même résultat dans le code précédent, je n'ai pas su savoir pourquoi, il n'y avait pas d'erreur indiquée dans le terminal. 
