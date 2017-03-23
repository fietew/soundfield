# soundfield
A LaTeX Package reflecting the Nomenclature of Sound Field Synthesis

## Installation
### Linux (Tex Live 2015)

For current user:
``` 
cp soundfield.sty `kpsewhich -var-value TEXMFHOME`/tex/latex/ 
```
System-wide (as root/using sudo):
```
cp soundfield.sty `kpsewhich -var-value TEXMFLOCAL`/tex/latex/
texhash
```

## Usage
```LaTeX
\usepackage{soundfield}
```
