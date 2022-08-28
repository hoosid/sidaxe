### Hi there im sidaxe
##ihave a code grid :
***this is html***
```html
<!DOCTYPE html>
<html>
<head>
<style>
.item1 { grid-area: header; }
.item2 { grid-area: menu; }
.item3 { grid-area: main; }
.item4 { grid-area: right; }
.item5 { grid-area: footer; }

.grid-container {
  display: grid;
  grid-template-areas:
    'header header header header header header'
    'menu main main main right right'
    'menu footer footer footer footer footer';
  gap: 10px;
  background-color: #2196F3;
  padding: 10px;
}
```
##Définition et utilisation
|grid|sol|
|---|----|
|grille-ligne-début
grille-colonne-début
fin de ligne de grille
grille-colonne-fin|La grid-areapropriété spécifie la taille et l'emplacement d'un élément de grille dans une disposition de grille et est une propriété abrégée pour les propriétés suivantes :

grille-ligne-début
grille-colonne-début
fin de ligne de grille
grille-colonne-fin
La grid-areapropriété peut également être utilisée pour attribuer un nom à un élément de grille. Les éléments de grille nommés peuvent ensuite être référencés par la propriété grid-template-areas du conteneur de grille. Voir les exemples ci-dessous.


|

