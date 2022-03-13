Rush | V.2 - All Bonus ✅
===================== 
Sujet commun
-------------------
Écrire la fonction rush prenant en paramètre deux variables de type entier nommées respectivement x et y. La fonction rush devra afficher à l’écran un rectangle de x caractères de largeur, et y caractères de hauteur.

Exemples
-------------------

#### rush(5, 5) :
```
o---o
|   |
|   |
|   |
o---o
```

#### rush(10, 5)
```
o--------o
|        |
|        |
|        |
o--------o
```

#### rush(20, 1)
```
o------------------o
```
------
Pseudo-Code
-------------------
<dl>
  <dt>Prototypage de ft_putchar</dt>
  <dd>Le prototypage est nécessaire car la Norminette interdit d'include des fichiers au format .c . Ainsi a la compilation avec <b>cc</b>, le compilateur ira chercher les fonctions de ft_putchar</dd>

  <dt>Instanciation de la fonction ft_write</dt>
  <dd>ft_write va servir à l'application de la partie <b>logique</b> mais aussi de <b>l'affichage</b>.</dd>
</dl>

<dl>
  <dt>Affichage de V1</dt>
  <dd>V1, V2 et V3 servent a stocker les signes permettant la mise en forme du résultat. (Cf. tableau ⬇)</dd>
</dl>

#### Ici pour le rush 01, les symboles seront :

| V1 | V2 | V3 |
|--|--|--|
| / | * | \ |

| V1 | V2 | V3 |
|--|--|--|
| * | *vide* | * |

| V1 | V2 | V3 |
|--|--|--|
| \ | * | / |
