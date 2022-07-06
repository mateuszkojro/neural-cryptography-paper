# latex-templates
Latex template for standard presentations and texts

## Exporting from matplotlib

Export file loadable in latex
```python
    matplotlib.use("pgf")
    matplotlib.rcParams.update({
        "pgf.texsystem": "pdflatex",
        'font.family': 'serif',
        'text.usetex': True,
        'pgf.rcfonts': False,
    })
```
