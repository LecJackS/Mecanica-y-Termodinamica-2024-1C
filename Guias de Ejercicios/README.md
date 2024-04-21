#### Codigo para crear directorios a partir de archivo con lista de nombres:
```bash
cut -d " " -f 1 guias.txt | xargs mkdir
```