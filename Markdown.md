# Markdown

<br>

Dans cette partie on va commencer par voir **les bases du markdown** en 10 grands points. Ils permettent déjà beaucoup mais principalement des choses simples donc on essayera de pousser un peu plus loin pour notament ecrire des **maths**. On va donc ensuite essayer de couvrir le plus possible les possibilitées permises par **LaTeX** dans ce domaine lors deuxieme partie de ce document. 

 <br>

## 1. Structure de base

On peut créer des titres de plus en plus petit au fur et a mesure qu'on rajoute des `#` avec une limite à 6.

```markdown
# Grand titre
## Sous-titre
### Sous-sous-titre
...
```

<br>

## 2. Texte normal

Par défaut on écrit du texte normal

```markdown
On écrit juste
```

<br>

## 3. Mise en forme

On peut changer la mise en forme du texte pour le passer en gras ou en italique

```markdown
**gras**
*italique*
***gras et italique***
~~barré~~
```

**Exemple** : *La liberté commence où l'ignorance finit.*

~~barré~~ 

<br>

## 4. Listes

```markdown
- premier point
- second point
    - sous point
```

**Exemple :**

- Definition

- Propriété
  
  - La distributivité

<br>

## 5. Code

### Code inline

```markdown
On pose `x = 12`
```

$\Rightarrow$  On pose `x = 12`

<br>

### Bloc de code

```markdown
```python
print("J'ai faim")
```

<br>

## 6. Formules mathématiques

### Formule inline

```markdown
Le résultat est $y = \sqrt{12}$
```

$\Rightarrow$ Le résultat est $y = \sqrt{12}$ 

<br>

### Formule centrée

```markdown
$$
x_{n+1} = x_n - \frac{f(x_n)}{f'(x_n)}
$$
```

**Résultat** :

$$
x_{n+1} = x_n - \frac{f(x_n)}{f'(x_n)}
$$

<br>

## 7. Liens

```markdown
[Nom du lien](https://example.com)
```

**Exemple :** [Wikipedia](https://www.wikipedia.org/)

<br>

## 8. Images

```markdown
![description](image.png)
![test](Images/test1.jpg)
```

**Exemple :** 

<img src="Images/test1.jpg" title="" alt="test" width="237">

<br>

## 9. Séparateurs

```markdown
---
```

**Exemple :**

---

<br>

## 10. Tableaux

```markdown
|titre1|titre2|titre3|
|---|---|---|
|blabla|bla|blablabla|
```

**Résultat :**

| titre1 | titre2 | titre3    |
| ------ | ------ | --------- |
| blabla | bla    | blablabla |

<br>

## Un peu de LaTeX...

<br>

### Fonctions

- $\sin$ : `$\sin$`, $\cos$ : `\cos`, $\tan$ :`$\tan$`, $\cot$ : `$\cot$`

- $\arcsin$ : `$\arcsin$`, $\arccos$ : `$\arccos$`, $\arctan$ : `$\arctan$`

- $\sinh$ : `$\sinh$`, $\cosh$ : `$\cosh$`, $\tanh$ : `$\tanh$`, $\coth$ : `$\coth$`

- $\ln$ : `$\ln$`, $\log$ : `$\log$`, $\exp$ : `$\exp$`

- $\max$ : `$\max$`, $\min$ : `$\min$`, $\sup$ : `$\sup$`, $\inf$ :`$\inf$`, $\lim$ : `$\lim$`

- $\ker$ : `$\ker$`, $\deg$ : `$\deg$`

- $\mod {n}$ : `$\mod {n}$`, $\bmod {n}$ : `$\bmod {n}$` (sans tabulation), $\pmod {n}$ : `$\pmod {n}$` (avec parenthèses), $\pod {n}$ : `$\pod {n}$` (sans mod mais avec parenthèses)
  
   
