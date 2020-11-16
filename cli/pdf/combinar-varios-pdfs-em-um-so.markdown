# Combinar vários PDFs em um só

Use o [PDFtk](https://www.pdflabs.com/tools/pdftk-the-pdf-toolkit/).

## Instalação no Debian/Ubuntu

```
sudo apt install pdftk
```

## Utilização

Se você deseja, criar um documento juntando os documentos `arquivo1.pdf` e `arquivo2.pdf` e criar um outro arquivo `arquivos_combinados.pdf`, você pode usar o seguinte comando:

```
pdftk arquivo1.pdf arquivo2.pdf cat output arquivos_combinados.pdf
```

É isso!