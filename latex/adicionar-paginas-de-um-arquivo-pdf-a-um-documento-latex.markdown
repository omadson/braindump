# Adicionar páginas de um arquivo PDF a um documento LaTeX

Use o pacote [pdfpages](https://www.ctan.org/pkg/pdfpages).


```
\usepackage{pdfpages}
```

Para incluir todas as páginas em um arquivo PDF:


```
\includepdf[pages=-]{myfile.pdf}
```

Para incluir somente uma página:

```
\includepdf[pages={1}]{myfile.pdf}
```

Para incluir somente uma página:

```
\includepdf[pages={1}]{myfile.pdf}
```