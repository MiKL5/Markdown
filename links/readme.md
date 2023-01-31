# Les liens et les images

Ces deux éléments ayant presque la même syntaxe, il fallait les aborder ensemble.
Le titre du lien est entre crochets `[` et `]`. C'est la partie visible et c'est sur lui que l'on clique. L'adresse est entre parenthèses `(` et `)`. Il est possible de faire apparaître une description au survol du lien, il se place entre guillemets[¹] simples `'` ou doubles `"` et à l'intérieur des parenthèses.  

En pratique
```md
[aprendre les bases](https://www.markdowntutorial.com/fr/ 'Tutoriel en ligne')
```
et devient  

[apprendre les bases](https://www.markdowntutorial.com/fr/ 'Tutoriel en ligne')  

Mais pour une image, c'est beaucoup plus dur.  
Non, je plaisante, il faut juste précéder le lien d'un point d'exclamation `!`.  
Ça s'écrit :  
```md
![Markdown](../src/Markdown-mark.svg 'logo markdown')
```
et affiche  
![Markdown](../src/Markdown-mark.svg 'logo markdown')  
On peut aussi insérer des images avec le html pour les aligner à gauche, à droite ou limiter la taille de l'image, mais pour la centrer, il faudra la placer dans une `<div>`.  

___
[¹] L'usage des doubles guillemets évitent les bogues à causes de l'apostrophe. 