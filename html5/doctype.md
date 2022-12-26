# DOCTYPE
Dec 26 2022

The doctype declaration is a directive telling the browser what type of document to expect,
it is *not* an html tag.  It is also *not* case - sensitive, although the standard seems to 
be using caps.

## Example

```html
<!DOCTYPE html>
<html>
    <head>
        <title>Title of the document</title>
    </head>

    <body>
        The content of the document......
    </body>

</html> 
```

With HTML5, the declaration is relatively straightforward.  Older types of documents show less succint declarations, which also included a "Document Type Declaration" (DTD).

## Example

```html
 <!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01 Transitional//EN" "http://www.w3.org/TR/html4/loose.dtd">
```

```html
 <!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.1//EN" "http://www.w3.org/TR/xhtml11/DTD/xhtml11.dtd">
```

HTML5 is the most modern, contemporary standard, but the others are still available and may offer some legacy features which have been deprecated.  For an extensive list of HTML tags and their compatibility with different doctype declarations, see [w3schools - HTML Elements Valid DOCTYPES](https://www.w3schools.com/tags/ref_html_dtd.asp).