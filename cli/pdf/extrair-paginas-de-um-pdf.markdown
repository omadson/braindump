# Extrair algumas páginas de um PDF

Use o [PDFtk](https://www.pdflabs.com/tools/pdftk-the-pdf-toolkit/).

## Instalação no Debian/Ubuntu

```
sudo apt install pdftk
```

## Utilização

Se você deseja, por exemplo, extrair as páginas de `1` até `10` de um documento chamado `book.pdf` e criar um outro arquivo `book_part.pdf`, você pode usar o seguinte comando:

```
pdftk book.pdf cat 1-10 output book_part.pdf
```

É isso!