# data-metrique

## real-dataset

Nous avons ici deux fichiers aux formats fasta contenant des séquences nucléotidiques.
Il s'agit de 2 ensembles de données expérimentales :
     
   ### CLL-20.fasta :   
   - ce fichier a été généré en échantillonnant des séquences du clone le plus abondant d'un répertoire monoclonal de CLL
   
   - il y a 20 séquences, chacune ayant une occurrence >= 1 : au total 3406 séquences
   
   - les séquences sont alignées entre elles
   ### TAS-42.fasta : 
   - ce fichier provient d'une base de données publique disponible sur https://github.com/matsengrp/gctree/tree/master/example
   
   - il y a 42 séquences + la séquence naïve, cette dernière est unique, les 42 autres séquences ont une occurrence >= 1 : au total 66 séquences
   
   - les séquences sont alignées entre elles
                      
## simulated-data

Ce dossier contient plusieurs dossiers comptabilisant au total 92 lignées BCR simulées,
obtenues avec le simulateur GCtree disponible ici : https://github.com/matsengrp/gctree

Chaque dossier contient plusieurs fichiers fasta correspondant à l'arbre de la lignée BCR,
contenant au maximum le même nombre de séquences que le nom du dossier.

Pour chaque fichier de lignée donné "tree.fasta", il y a :
   - le véritable arbre "tree.naive.nk"

   - l'arbre déduit par ClonalTree "tree.clonalTree.nk"
