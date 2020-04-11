# Typography CSS
This style is created primarily for blog article design.
## Implementation
This typography set uses two .css files that need to be implemented in the HTML header.
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
## Usage
This way of styling blog articles does not use any clues. There is, therefore, no need to add many of these elements to HTML.

However, all one article must be one `<article>` element.
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
## Components
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
![Preview](/preview/web-print.png)