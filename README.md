# Hi there im sidaxe im programmeur :
*ihave a code grid :*
***this is html grid code***
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
*Définition et utilisation:*
|grid|sol|
|---------|---------------------------------------------------------------------------------------------------------------------------------------------------------------|
|grid eara|La grid-areapropriété peut également être utilisée pour attribuer un nom à un élément de grille. Les éléments de grille nommés peuvent ensuite être référencés par la propriété grid-template-areas du conteneur de grille|
|grid-template-areas|La grid-template-areaspropriété CSS spécifie des zones de grille nommées , établissant les cellules dans la grille et leur attribuant des noms.|
|gap|La propriété CSS définit les espaces ( gouttières ) entre les lignes et les colonnes. C'est un raccourci pour et .gap row-gapcolumn-gap|

>***good luck***


