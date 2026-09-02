# BUILD.md

Aquest projecte emplea `jekyll` per tal de construir es html a base de trossos, per poder veure sa web emplea `jekyll build` o `jekyll serve`.

## Com escriure entrades del blog

A la carpeta `_posts/`, s'hi ha de crear un fitxer Markdown seguint el següent
patró pel nom: `YYYY-mm-dd-nom-de-lentrada.md`. La data que poseu al nom del
fitxer serà la que es mostrarà al blog com a data de publicació. Dins el fitxer:

```md
---
title: "Títol de l'entrada"
author: "Nom de l'autor"
image: https://enllac.com/a/una/imatge.png
---

Subtítol de l'entrada, un breu resum.

Text...
```

La línia d'`image` és opcional; si no en posau, apareixerà una imatge per
defecte. És important que vos assegureu que la imatge sigui visible
públicament, i que no tengui l'accés restringit.
