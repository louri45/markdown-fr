# Titles

Comme nous commençons à écrire un document markdown, nous avons besoin d'ajouter un titre et quelques sous-titres.

Le Markdown supporte deux styles d'entêtes, les Setext et les atx.

Les entêtes Setext sont “soulignées” en utilisant le signe égal (pour une entête de premier niveau) et des tirets (pour les entêtes de second niveau). Par exemple:

```
Ceci est un H1
==============

Ceci est un H2
--------------
```

N'importe quel nombre de signes "=" ou "-" pour souligner fonctionnera.

Les entêtes atx utilisent de 1 à 6 mots-dièse en début de ligne, correspondant aux entêtes de niveau 1 à 6. Par exemple:

```
# Ceci est un H1

## Ceci est un H2

###### Ceci est un H6
```


Facultativement, vous pouvez "fermer" les entêtes atx. Ceci est purement esthétique — vous pouvez l'utilisez si vous trouvez cela plus joli. Les mots-diéses fermant n'ont pas besoin de correspondre au nombre de mots-diése ouvrant, utilisés pour commencer l'entête. (Le nombre de mot-diése ouvrant détermine le niveau de l'entête.) :

```
# Ceci est un H1 #

## Ceci est un H2 ##

### Ceci est un H3 ######
```


---

Voici un quiz a propos des titres markdown.

Selectionnez l'entête valide:
- [x] `# hello`
- [ ] `#hello`

> L'entête a besoin d'espace entre le mots-diése et le texte.

Selectionnez l'entête valide:
- [ ]  
```
test
########
```
- [x]   
```
test
=======
```

> Seulement '=' et '-' sont acceptés pour souligner une entête.

---


