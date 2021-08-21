# Mode d'emploi Markdown

## Paragraphes

```markdown
Paragraphe 1
(laisser une ligne vide)
Paragraphe 2
```

**Résultat :**

Paragraphe 1

Paragraphe 2

### Sauts de ligne

```markdown
Texte
Texte
```

**Résultat :**

Texte
Texte

## Gras, italique

### Gras

```markdown
**Texte en gras** avec 2 étoiles
```
ou :

```markdown
__Texte en gras__ avec 2 tirets du 8
```

### Italique

```markdown
*Texte en italique* avec 1 étoile
```
ou :

```markdown
_Texte en italique_ avec 1 tiret du 8
```

### Gras et italique

```markdown
***Texte en gras et italique*** avec 3 étoiles
```

ou :

```markdown
___Texte en gras et italique___ avec 3 tirets du 8
```

### Texte souligné

```markdown
<u>Texte souligné</u>
```

**Résultat :**

<span style="text-decoration:underline">Texte souligné</span>

### Texte barré

```markdown
~~Texte barré~~
Entourer le texte de 2 "tildes" (Alt Gr + 2)
```

**Résultat :**

~~Texte barré~~

## Titres

```markdown
Titre 1 (titre principal de la page)
==========
À souligner avec des symboles égal

Titre 2
----------
À souligner avec des tirets
```

**Résultat :**

Titre 1
==========

Titre 2
----------

ou :

```markdown
# Titre 1 (1 dièse)

## Titre 2 (2 dièses)

...

###### Titre 6 (6 dièses)

## On peut aussi rajouter des dièses à la fin → ##
```

**Résultat :**

# Titre 1

## Titre 2

...

###### Titre 6

## Listes

### Listes non numérotées

```markdown
* Liste
* Liste
```

ou :

```markdown
+ Liste
+ Liste
```

ou :

```markdown
- Liste
- Liste
```

**Résultat :**

- Liste
- Liste

### Listes numérotées

```markdown
1. Liste
2. Liste
3. Liste
```

**Résultat :**

1. Liste
2. Liste
3. Liste

### Sous-listes

```markdown
* Liste
	* Sous-liste
		* Sous sous-liste...
	* Sous-liste
	* Sous-liste
* Liste
* Liste
* Liste
```

**Résultat :**

* Liste
	* Sous-liste
		* Sous sous-liste...
	* Sous-liste
	* Sous-liste
* Liste
* Liste
* Liste

## Citations

```markdown
> Citation
> Citation
> 
> Paragraphe dans la citation (laisser une ligne vide, comme pour les paragraphes normaux)
> 
> > Réponse
> > Réponse
> > 
> > Paragraphe dans la réponse
```

**Résultat :**

> Citation  
> Citation
> 
> Paragraphe dans la citation
> 
> > Réponse  
> > Réponse
> > 
> > Paragraphe dans la réponse

## Liens

```markdown
[Texte du lien](adresse de l'image)
```
**Exemple :**

```markdown
[Inscription](https://cate.epizy.com/espacecate/inscription.php)
```

**Résultat :**

Inscription [au caté](https://cate.epizy.com/espacecate/inscription.php) / [à l'aumônerie](https://cate.epizy.com/aumonerie/inscription.php).

## Images

```markdown
![Texte alternatif](adresse de l'image)
```

**Exemple :**

```markdown
![Logo du site du caté](https://cate.epizy.com/espacecate/favicon.png)
```

**Résultat :**

Logo du site du caté :
![Logo du site du caté](https://cate.epizy.com/espacecate/favicon.png)

Logo du site de l'aumônerie :
![Logo du site de l'aumônerie](https://cate.epizy.com/aumonerie/favicon.png)

## Barre horizontale

```markdown
(avec des étoiles)
*****
```

ou :

```markdown
(avec des tirets)
-----
```

**Résultat :**

-----
