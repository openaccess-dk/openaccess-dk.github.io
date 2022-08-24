# openaccess.dk

Github repositorie for Dansk netværk for Open Access' hjemmesiden www.openaccess.dk

## Indhold

Websites indhold er gemt i en række markdown filer som har filetypen `.md`

Til at starte med så har jeg lavet følgende filer:

- `index.md` som er forsiden
- `oaw2022.md` til programmet for Open Access Week 2022
- `english.md` for en side på engelsk

Du kan klikke ind på hver fil herover og vælge **Edit** for at ændre i sidernes indhold.

For at lave en ny side, så klikker du på **Add File** og vælger **Create new file**

Hver .md-fil skal starte med følende metadata for at virker korrekt:

```
---
title: Open Access Week 2022
permalink: /oaw2022
layout: default
---

## Overskrift

brødtekst
```

- `title:` er hvad der kommer til at stå i menuen (se nedenfor)
- `permalink:` bruges til at lave en pæn URL uden .md
- `layout:` Skal enten være `default` eller `default-eng` for at få logo og footer på engelsk istedet for dansk

I filen [README-markdown.md](README-markdown.md) kan du læse mere om hvordan man bruger markdown til at formater teksten på hver side.

## Menu

Når du laver nye undersider, så kommer de ikke automatisk med i menuen.

For at ændre i menupunkterne skal du redigere i filen: [_data/navigation.yml](https://github.com/openaccess-dk/openaccess-dk.github.io/blob/main/_data/navigation.yml)

## Problemer?

Hver gang du har gemt ændringer, så genererer github en ny version af hjemmesiden. Der kan derfor går lidt tid før dine ændringer kan ses på openaccess.dk.

Hvis dine ændringer ikke vises efter et par minutter, så kan der være at der noget galt og den automatiske generering har slået fejl.

(c) Copyright 2022

## Credits

This site was created using [Jekyll](https://jekyllrb.com), [Github Pages](https://pages.github.com/) and [Simple.css](https://simplecss.org) following [Kev Quirk's](https://kevq.uk) aswesome guide [How To Build A Jekyll Site Using Simple.css](https://kevq.uk/how-to-build-jekyll-site-simple-css/)
