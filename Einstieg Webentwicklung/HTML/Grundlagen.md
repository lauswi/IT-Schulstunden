# HTML Grundlagen

Was genau ist [HTML](https://de.wikipedia.org/wiki/Hypertext_Markup_Language) und wofür wird es verwendet? 

## Aufbau einer Webseite

Es gibt im HTML Code immer einen Start-Tag `<start-tag>` und einen End-Tag `</end-tag>`. 

```html run

<html>
  <head>
        <title> Meine erste Webseite </title>
  </head>
  <body>
  <!--Das ist ein Kommentar-->
  <p> Hallo Webwelt! </p>
  
  </body>
</html>
```

Zwischen den Tags kann Text stehen, der auf der Webseite angezeigt werden soll oder weitere Tags.
Hierbei gibt es verschiedene Textformate, die auch durch die Art der Tags festgelegt werden.

- `<h1> ... </h1>` Überschrift
- `<p> ... </p>` Fließtext

``` html run
<html>
  <head>
        <title> Meine erste Webseite </title>
        <meta charset= "utf-8"/>
  </head>
  <body>
    <h1> Überschrift 1 </h1>
    <h2> Überschrift 2 </h2>
    <h3> Überschrift 2 </h3>
    <!--Das ist ein Kommentar-->
    <p> Hallo Webwelt! </p>
  </body>
</html>
```
