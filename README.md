# topslack

Le best-of du slack Webeux

## Regexp pour mettre en forme les cop/col

(attention, copier aussi les espaces, et mettre l'extension .md à son fichier)

* chercher :
```
(.*]) 
(1 espace après la dernière parenthèse)
```
* remplacer :
```
\*\*$1\*\*  
(2 espaces après le dernier *)
```
* chercher :
```
\n\n
```
* remplacer :
```
  \n\n
(2 espaces avant le 1er \n)
```
* chercher :
```
\n\n\w+.*
```
* remplacer
```
[laisser vide]
```

## todo

Ajouter un dossier de screenshots
