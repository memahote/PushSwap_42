# PushSwap_42

L'objectif principal est de trier une pile d'entiers en utilisant un nombre limité d'instructions, tout en minimisant le nombre total d'opérations nécessaires.


**Piles:** Le programme doit gérer deux piles distinctes, A et B, ainsi que différentes instructions pour manipuler ces piles.

**Tri:** Le but du programme est de trier la pile A en utilisant uniquement un ensemble limité d'instructions.
Les instructions suivantes sont utilisées pour manipuler les piles :

- **sa** : swap a - échanger les deux premiers éléments de la pile A.
- **sb** : swap b - échanger les deux premiers éléments de la pile B.
- **ss** : sa et sb en même temps.
- **pa** : push a - prendre le premier élément de la pile B et le placer au sommet de la pile A.
- **pb** : push b - prendre le premier élément de la pile A et le placer au sommet de la pile B.
- **ra** : rotate a - déplacer vers le haut tous les éléments de la pile A d'un cran. Le premier élément devient le dernier.
- **rb** : rotate b - déplacer vers le haut tous les éléments de la pile B d'un cran. Le premier élément devient le dernier.
- **rr** : ra et rb en même temps.
- **rra** : reverse rotate a - déplacer vers le bas tous les éléments de la pile A d'un cran. Le dernier élément devient le premier.
- **rrb** : reverse rotate b - déplacer vers le bas tous les éléments de la pile B d'un cran. Le dernier élément devient le premier.
- **rrr** : rra et rrb en même temps.

**Optimisation:** Le programme doit trouver la séquence d'instructions optimale pour trier la pile A avec le moins d'opérations possible.
