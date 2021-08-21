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

On peut aussi faire des paragraphes dans les *listes* et dans les *citations*.

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

Avec 2 étoiles :

```markdown
**Texte en gras**
```
Avec 2 tirets du 8 :

```markdown
__Texte en gras__
```

**Résultat :** **Texte en gras**

### Italique

Avec 1 étoile :

```markdown
*Texte en italique*
```
Avec 1 tiret du 8 :

```markdown
_Texte en italique_
```

**Résultat :** *Texte en italique*

### Gras et italique

Avec 3 étoiles :

```markdown
***Texte en gras et italique***
```

Avec 3 tirets du 8 :

```markdown
___Texte en gras et italique___
```

**Résultat :*** _**Texte en gras et italique**_

### Texte souligné

```markdown
<u>Texte souligné</u>
```

**Résultat :** <span style="text-decoration:underline">Texte souligné</span>

### Texte barré

Entourer le texte de 2 *tildes* (Alt Gr + 2) :

```markdown
~~Texte barré~~
```

**Résultat :** ~~Texte barré~~

## Titres

```markdown
Titre 1 (titre principal de la page)
==========
```
À souligner avec des symboles *égal*

```markdown
Titre 2
----------
```
À souligner avec des tirets

**Résultat :**

Titre 1
==========

Titre 2
----------

On peut aussi écrire :

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

###### Titre 6 (tout petit !!)

## Listes

### Listes non numérotées

Avec des étoiles :

```markdown
* Liste
* Liste
```

Avec des plus :

```markdown
+ Liste
+ Liste
```

Avec des tirets :

```markdown
- Liste
- Liste
```

**Résultat :**

- Liste
- Liste

### Listes numérotées

Il faut numéroter les éléments.

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
* 
* Paragraphe dans la liste
* 
	* Sous-liste
		* Sous sous-liste...
		* 
		* Paragraphe 1 dans la sous sous-liste
		* 
		* Paragraphe 2 dans la sous sous-liste
	* Retour à la sous-liste
	* Sous-liste
* Retour à la liste
* Liste
* Liste
```

**Résultat :**

* Liste
* 
* Paragraphe dans la liste
* 
	* Sous-liste
		* Sous sous-liste...
		* 
		* Paragraphe 1 dans la sous sous-liste
		* 
		* Paragraphe 2 dans la sous sous-liste
	* Retour à la sous-liste
	* Sous-liste
* Retour à la liste
* Liste
* Liste

## Citations

```markdown
> Citation
> Citation
> 
> Paragraphe dans la citation
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

Les liens sont reconnus automatiquement et deviennent cliquables :
```markdown
- https://cate.epizy.com/espacecate
- https://cate.epizy.com/aumonerie
```

**Résultat :**

- https://cate.epizy.com/espacecate
- https://cate.epizy.com/aumonerie

Pour changer le texte du lien, il faut écrire :

```markdown
[Texte du lien](adresse du lien)
```
**Exemple :**

```markdown
[Inscription](https://cate.epizy.com/espacecate/inscription.php)
```

**Résultat :**

Inscription [au caté](https://cate.epizy.com/espacecate/inscription.php) / [à l'aumônerie](https://cate.epizy.com/aumonerie/inscription.php).

### Adresses mail

Mettre l'adresse mail entre les symboles `<` (plus petit que) et `>` (plus grand que) :
```markdown
<laurentfavole03@gmail.com>
```

**Résultat :**

Mon adresse mail : <laurentfavole03@gmail.com>

## Images

```markdown
![Texte alternatif](adresse de l'image)
```

**Exemple :**

```markdown
Logo du site du caté :
![Logo du site du caté](https://cate.epizy.com/espacecate/favicon.png)

Logo du site de l'aumônerie :
![Logo du site de l'aumônerie](https://cate.epizy.com/aumonerie/favicon.png)
```

**Résultat :**

Logo du site du caté :
![Logo du site du caté](https://cate.epizy.com/espacecate/favicon.png)

Logo du site de l'aumônerie :
![Logo du site de l'aumônerie](https://cate.epizy.com/aumonerie/favicon.png)

## Barre horizontale

Avec des étoiles :

```markdown
*****
```

Avec des tirets :

```markdown
-----
```

**Résultat :**

-----
