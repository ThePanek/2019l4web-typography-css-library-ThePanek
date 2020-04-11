# Typography CSS
Tento styl je vytvořen primárně pro design článku na blogu.
## Implementace
Tento set typografie využívá dva soubory .css, které je třeba implementovat do hlavičky html.
```html
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <meta http-equiv="X-UA-Compatible" content="ie=edge" />
    <title>Title</title>
    <!-- load normalize.css -->
    <link rel="stylesheet" href="normalize.css" />
    <!-- load typography.css -->
    <link rel="stylesheet" href="typography.css" />
</head>
```
## Použití
Tento způsob stylizace článků na bloku neužívá žádné klásy. Není tudíž třeba do html přidávat mnoho těchto prvků. 

Ovšem celý jeden článek musí být jeden `<article>` element.
```html
<article>
    <h2>Heading</h2>
    <p>
        Lorem ipsum
    </p>
    <h2>Heading</h2>
    <p>
        Lorem ipsum
    </p>
</article>
```
## Komponenty
### Header
```html
<header>
    <h1>Main heading</h1>
    <p>
        by<a href=""> author's name</a>
    </p>
</header>
```
### Image with caption
```html
<figure>
    <img src="" alt="" />
    <figcaption>
        by<a href=""> author's name</a>
    </figcaption>
</figure>
```
### Blockquote
```html
<blockquote cite="">
    <p>
        <q>quote</q> author's name
    </p>
</blockquote>
```
### List
```html
<!-- Unordered -->
<ul>
    <li>Lorem</li>
    <li>Lorem</li>
    <li>Lorem</li>
</ul>

<!-- Ordered -->
<ol>
    <li>Lorem</li>
    <li>Lorem</li>
    <li>Lorem</li>
</ol>
```
### Footer
```html
<footer>
    <p>
        Created by<a href=""> author's name</a>
    </p>
</footer>
```