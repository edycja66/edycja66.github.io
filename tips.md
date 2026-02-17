---
layout: page
title: Markdown tips
permalink: /tips/
---

<div id="pl"></div>

## Parę zasad edycji plików .md ##

Nagłówki: 

    # Tytuł główny (H1)
    ## Podtytuł (H2)
    ### Mniejszy nagłówek (H3)

Pogrubienie i kursywa:

    **To będzie pogrubione** → To będzie pogrubione
    *To będzie kursywą* → To będzie kursywą

Listy:

    - Element listy (kropka)
    1. Element listy (numerowana)

Linki i obrazki:

    Link: [Tekst linku](https://adres.pl)
    Obrazek: ![Opis alternatywny](link-do-obrazka.jpg)

Bloki kodu (jak te czarne sekcje w nn. tekście):

    Wcięcie spacjami (zwykle 4 spacje lub 1 Tab)

Ogrodzone bloki kodu: Użyj potrójnych znaczników wstecznych

  ```javascript
  function hello() {
    console.log("Hello World!");
  }
  ```     

Cytaty, jak:
>Litwo, ojczyzno moja

    Użyj symbolu > (> To jest cytat)

Przypisy: 

    Użyj składni [^1] do pisania akademickiego

  To jest zdanie z przypisem[^1].
  [^1]: To jest treść przypisu.
  
Linie poziome:

    Użyj --- lub ***

***

*Na podstawie tekstu ze strony:* [blog.tomaszdunia.pl](https://blog.tomaszdunia.pl/blog-jekyll-github/) *oraz* [md-tool.com](https://md-tool.com/pl/markdown-guide)
