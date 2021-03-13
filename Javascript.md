# Javascript les concepts de base.  
le code Javascript s'integre dans une page HTML avec ces balises . directement à l'interieur ou dans un fichier séparé avec le lien ds le html .
```
<script></script> 
<script src="script.js"></script>
```
les commentaires pour expliquer les etapes de son code :
```
// commentaire une ligne 
/* ...*/ multiligne
```
***
## Les variables  
Les variables permettent d'allouer un espace dans la mémoire vive, où on peut y stocker des données.
```
var name = "bob";
```
On Utilise :
let lorsqu'on veut pouvoir ré-assigner la variable 
const représente une variable que l'on ne peut pas ré-assigner.
utiliser dès que je suis sure que  la variable ne doit pas être réassignée.
*** 
## Les types de données 
la fonction **typeof** est utilisé pour savoir le type de donné d'une variable. 
les types de données dites **primitives** : qui sont immuables , on ne peut pas les changer :
* string          
* number
* booleans 
* undefined
* null (est utilisé pour indiquer une abscence intentionnelle de valeur ) / undefined = variable déclaré mais pas de valeur assigné .
les types de données **non primitifs** dit complexes elles peuvent changer:
* objets 
* function 
