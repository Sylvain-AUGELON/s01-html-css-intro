# Introduction au HTML/CSS

## Le langage HTML

Le langage HTML est un langage de **balisage**, c'est-à-dire qu'il a pour vocation de délimiter des portions du contenu d'une page Web afin de pouvoir les identifier et de leur donner différentes propriétés.

Chaque **balise** permettant de délimiter des blocs a une **valeur sémantique**, c'est-à-dire un sens, une signification. La valeur sémantique des balises n'a pas d'impact sur l'aspect visuel de la page, mais permet aux robots de référencement, par exemple, de comprendre à quoi sert chaque élément. Il est donc important de privilégier la signification de chaque contenu plutôt que le rendu visuel souhaité dans le choix des noms de balise.

## Le langage CSS

Le langage CSS est un langage permettant de contrôler **l'apparence** d'une page Web. Ce langage fonctionne sur un principe de règles:

## La séparation des concepts

On s'efforce autant que possible de mettre tout ce qui a trait au **contenu** d'une page dans des fichiers HTML, et tout ce qui a trait à **l'apparence** d'une page dans des fichiers CSS. Dans un site d'e-commerce, par exemple, cela permet de faire une différence claire entre des changements associés au contenu du site (nouveaux produits, opérations de promotion…), et des changements associés à son identité visuelle (refonte graphique, changements dans la disposition des éléments…).

## Les codes couleur

Les couleurs sont classiquement exprimées selon la norme **RGB** (**R**ed, **G**reen, **B**lue), qui correspondent à tous les mélanges possibles d'une diode rouge, une diode verte, et une diode bleue dans nos écrans, chacune allumée à n'importe quel niveau parmi 256 possibles (de 0 = complètement éteinte à 255 = complètement allumée).

En CSS, on peut écrire les codes couleur sous la forme `rgb(0, 80, 255)` ou bien `#0080FF`. Cette seconde version, qppel2e **héxadécimale**, est simplement une autre façon de noter les nombres qui correspond exactement aux trois valeurs de la notation RGB.
