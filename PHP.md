### Executer PHP : 
php -S localhost :8000 
### Variables scalaires : 
entier :integer 
Réel : float ( à virgule ) 
Booléen : boolean ( true / false ) 
chaîne de caractères : string ("") 
### Composées : 
Tableau : Array 
objet : Object 
### Types speciaux : 
les ressources 
NULL ( variable qui n'a pas de valeur ) 
### Concaténation : 
. entre chaque valeur mises entre '' 
### Les boucles : 
## for 
for ($i = 0 , $i < count ($variable ) , $i ++ ) 
{ return $variable[$i] }
## foreach 
foreach ($movies as $movie ) {
return $movie }
## foreach + key
foreach ( $movies as $key => $movie ) 
{ return $key . $movie 
}
### Tableau associatif : 
Syntaxe : 
$armes =['arme1'=> 'flèche',
         'arme2'=> 'couteau', 
          'arme3' => 'épée'];
          
### Tableau multidimentionnel : 

$armes = [ 'pierre' => ['épee','feuille','ciseaux'],
          'Marc' => ['couteau', 'pierre', 'gun'],
         'Antoine'=> ['flèche','mitraillette','piment']
         ];
# Affiche une valeur d'un tableau en passant par la clé : 
return ['Marc'][1] ; (affiche 'feuille')

## Boucler sur un tableau :

for ( $i = o , $i < count($armes) , $i ++ ) {
echo $armes[$i];
