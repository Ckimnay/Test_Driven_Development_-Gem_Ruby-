# Test_Driven_Development_-Gem_Ruby-
A FINIR 


L'ÉNONCÉ
Si on liste tous les entiers naturels strictement inférieurs à 11 et qui sont multiples de 3 ou 5, on obtient 3, 5, 6, 9 et 10. La somme de ces nombres est égale à 33. 
=> Trouve la somme des entiers naturels strictement inférieurs à 1000 et qui sont multiples de 3 ou 5.


APPROCHE ANALYTIQUE

a) la méthode is_multiple_of_3_or_5?(current_number)

Elle vérifie si le chiffre en entrée (current_number) est multiple ou non de 3 ou 5. Elle retourne un booléen (true ou false) en fonction.

Des exemples de sorties attendues de cette méthode selon ce qu'on lui donne en entrée seraient :

3 ou 5 devraient renvoyer true
51 ou 45 devraient renvoyer true
2, 7 ou 64 devraient renvoyer false

b) la méthode sum_of_3_or_5_multiples(final_number)

Elle boucle sur les nombres de 0 à "final_number" : chaque nombre est testé par is_multiple_of_3_or_5?(current_number) pour savoir (à chaque tour de boucle), s'il faut mettre le nombre en question dans la somme finale ou passer au suivant.

Des exemples de sorties attendues de cette méthode selon ce qu'on lui donne en entrée seraient :

10 devrait renvoyer 23,
11 devrait renvoyer 33,
0 ou 3 devraient renvoyer 0,
-1, 1.23 ou "chiffre" devrait nous donner un truc du genre Yo ! Je ne prends que les entiers naturels. TG.
