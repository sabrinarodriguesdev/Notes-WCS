# STRING 

### La longueur (length) de la variable :
strlen() 
### Tronquer caracteres blancs (espace tab ) 
trim() / rtrim() pareil mais à gauche ou à droite 
### Renvoie chaine en minuscule :
strtolower() 
### renvoie chaîne en majuscule : 
strtoupper() 
### premier caractere de la chaîne en majuscule :
ucfirst() 
### chaque premiere lettre de mot en majuscule :
ucwords()
### remplace tout ou partie de chaîne par une autre : 
str_replace (mot à remplacer , nouveau mot , variable dans laquelle est le mot ) 
str_ireplace() insensible à la casse 
### converti les balises html pour qu'elles ne soient pas interprétees : 
htmlentities() 
### Convertir STRING en ARRAY : 
explode() 
### renvoie une partie de la chaine :
substr( chaîne , début , longueur de la sous chaîne ) 
### Renvoyer la chaîne inversée : 
strev() 
### afficher uniquement une chaîne de caractères 
print() 
### retourner le nombre d'occurence de needle dans une chaine : 
substr_count ( la chaîne de caractère , ce qu'on recherche , l'eventuel decalage à partir duquel on commence (int ) ) 




# ARRAY 
### afficher les valeurs : 
var_dumpt() 
### convertir ARRAY en STRING /
implode() 
### Trier tableau par ordre croissant :
sort() pour chiffre , pour string , par ordre alpha . QUE SUR TABLEAUX NUMERIQUES 
### Trier un tableau par ordre decroissant : 
rsort() 
### Trier tableau en gardant clés intactes : 
asort() 
### Verifier presence d'une valeur dans un tableau : 
in_array(valeur recherché , tableau ) 
### Calculer la somme d'un tableau : 
array_sum() 
### ajouter une valeur à un tableau : 
array_push(nom du tableau , valeur ) 

