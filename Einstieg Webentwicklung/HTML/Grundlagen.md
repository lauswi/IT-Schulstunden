# HTML Grundlagen

Was genau ist [HTML](https://de.wikipedia.org/wiki/Hypertext_Markup_Language) und wofür wird es verwendet? 

## Aufbau einer Webseite

Es gibt im HTML Code immer einen Start-Tag `<start-tag>` und einen End-Tag `</end-tag>`. 

```html

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

`<h1> ... </h1>` = Überschrift

`<p> ... </p>` = Fließtext

``` html
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

`<meta charset= "utf-8"/>` macht es möglich, dass Umlaute, wie Ü, Ä, Ö... angezeigt werden

## Attribute

Es gibt unzählige, unterschiedliche Funktionen, die als Attribute bezeichnet werden. 

Zum Beispiel: 
``` html
<h1 align="center"> Eine zentrierte Überschirft </h1>
```

## Grafiken einbinden

###### Einbinden von Bildern

``` html
<img src="http://www.link-zu-einem-bild.png">
<img src="/bilder/bild.png">
```

Es kann hier entweder ein Link zu einem Bild von einer Internetseite oder ein Dateipfad für ein Bild von deinem Rechner angegeben werden. Gibst du einen Dateipfad von deinem Rechner an achte darauf, dass du einen sinnvollen Speicherort wählst. 



