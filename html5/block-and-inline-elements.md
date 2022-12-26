# HTML Elements - Block and Inline
Dec 26 2022

## Block Elements

The default display value attached to HTML elements can be one of two types:
block or inline.

Block elements are always drawn on a new line, and modern browsers will add a margin around the element by default.  By default, block elements always stretch as far left and right as is available, across the full width of the parent element.  Two of the most commonly used HTML block elements are the ```<p>``` (paragraph element) and ```<div>``` (division or section element) tags.

The following are all block type elements in HTML:
```html
<address> <article> <aside> <blockquote> <canvas> <dd> <div> <dl> <dt> <fieldset> <figcaption> <figure> <footer> <form> <h1>-<h6> <header> <hr> <li> <main> <nav> <noscript> <ol> <p> <pre> <section> <table> <tfoot> <ul> <video> 
```

### Example Block Element: ```<div>```

The div element is most often used as a container for other HTML elements, and has no required attributes but style, class, and id are often used to format the container and make it selectable with javascript.

```html
 <div style="background-color:black;color:white;padding:20px;">
  <h2>London</h2>
  <p>London is the capital city of England. It is the most populous city in the United Kingdom, with a metropolitan area of over 13 million inhabitants.</p>
</div> 
```
***

## Inline Elements

In contrast to block elements, inline elements do not start on a new line and take up only as much width as is necessary for their content.  An inline element *cannot* contain a block type element... what happens if they do?

The following are all inline type elements in HTML:
```html
<a> <abbr> <acronym> <b> <bdo> <big> <br> <button> <cite> <code> <dfn> <em> <i> <img> <input> <kbd> <label> <map> <object> <output> <q> <samp> <script> <select> <small> <span> <strong> <sub> <sup> <textarea> <time> <tt> <var>
```

### Example Inline Element: ```<span>```

The span element is an inline container used to format a part of a document. Span also has no required attributes but, like div, style, class, and id are often used.  With the addition of some CSS, the span element can be used to stylize parts of text.

```html
<p>My mother has <span style="color:blue;font-weight:bold;">blue</span> eyes and my father has <span style="color:darkolivegreen;font-weight:bold;">dark green</span> eyes.</p>
```
