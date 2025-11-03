# Here is title of my new file
- Animals
  - Dogs
    - Bearded Collie

# Figures
``` {figure} figures/favicon.svg
:width: 10%
:name: test-favicon
favicon - via downloaded file in /content/figure
```

``` {figure} https://polslab.tnw.tudelft.nl/figures/training.JPG
:width: 50%
:name: lecture-hall
lecture hall - via external url
```
# iframe
```{iframe} https://www.youtube.com/embed/dhzrlXzYOlU?si=n2U0HSJyotjp-r93
:width: 80%

Purves et al. - Jupyter Book 2 0 – A Next Generation tool for sharing for Computational Content
```

# Code
``` python
print("HELLO WORLD")
```

``` javascript
console.log("This is not python");
```
#### `fibonacci.py`
``` python
def fib(n):
    if n < 0:
        return
    if n in [0, 1]:
        return n
    else:
        return fib(n-2) + fib(n-1)
```
#### Wiki
[Bloomberg Wikipedia Page](wiki:Bloomberg_L.P.) 

#### xref
[myst-guide](xref:myst-guide)
- included in myst.yml under `references`

[Jupyter Book Markdown Cheat Sheet](https://jupyter-book.github.io/workshop-template/cheat-sheet)
[Jupyter Book Markdown Cheat Sheet local ref](xref:content/2_cheat_sheet.md)
