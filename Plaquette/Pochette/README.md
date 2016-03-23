# Création et découpe de la pochette #

L'objectif est de créer une pochette imprimée par nos soins puis découper à la machine (Silhouette Cameo).

Pour une meilleure découpe, il faut imprimer l'ensemble avec le logiciel Silhouette Studio afin d'avoir des repères de positionnement pour la machine.

Information : la est dotée de capteurs optiques qui lui permet de calibrer sa coupe.

## Réalisation de la mécanique de la pochette avec QCad #

```
Pochette_A4.dxf
```

## Extraction de chaque couche ##

Silhouette Studio importe (malheureusement) les différents calques DXF comme un seul.
Il faut donc créer des fichiers séparés avec des répères (ex: haut-gauche, bas-droit) identiques sur chaque fichier.
```
Pochette_A4_plis.dxf
Pochette_A4_decoupe.dxf
```

## Import des éléments dans Silhouette Studio ##

Il faut configurer l'import des DXF pour que le logiciel ne modifie pas les dimensions puis importé dans la bibliothèque les fichiers suivant :

```
Pochette_A4_plis.dxf
Pochette_A4_decoupe.dxf
```
L'alignement se fait avec les outils du logiciel

Ensuite on importe les logos et textes (au format image bitmap) :

```
Pochette_A4_logo_texte.png
Pochette_A4_logo_feutre.png
```
