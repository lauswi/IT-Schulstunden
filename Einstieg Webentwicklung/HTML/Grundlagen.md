# HTML Grundlagen

Was genau ist [HTML](https://de.wikipedia.org/wiki/Hypertext_Markup_Language) und wofür wird es verwendet? 

HTML steht für Hypertext Markup Language. Bei der Programmiersprache, geht es um die Gliederung einer Websiete. 

## Aufbau einer Webseite

Es gibt im HTML Code immer einen Start-Tag `<start-tag>` und einen End-Tag `</end-tag>`. 
In einer HTML-Datei beginnt man damit immer mit `<html>` und endet mit `</html>`.
Es wird außerdem in `<head>` und `<body>` eingeteilt. 

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
Außerdem gibt es folgende Attribute:

- alt     = alternative beschreibung eines Bildes
- align   = Position (left, center, right)
- title   = definiert Information über ein Element

## Grafiken einbinden

#### Einbinden von Bildern

``` html
<img src="http://www.link-zu-einem-bild.png">
<img src="/bilder/bild.png">
```

Es kann hier entweder ein Link zu einem Bild von einer Internetseite oder ein Dateipfad für ein Bild von deinem Rechner angegeben werden. Gibst du einen Dateipfad von deinem Rechner an achte darauf, dass du einen sinnvollen Speicherort wählst. 

#### Listen

`<ol>...</ol>` = geordnete Liste

`<ul> ... </ul>` = ungeordnete Liste

`<li> ... </li>` = List Item

Bsp.: 
```html
<ol>
  <li> List Item 1 </li>
  <li> List Item 2 </li>
  <li> List Item 3 </li>
</ol>

<ul>
  <li> List Item 1 </li>
  <li> List Item 2 </li>
  <li> List Item 3 </li>
</ul>
```

## Verlinkungen
Über den Tag `<a> ... </a>` lassen sich Links einbinden. 
```html 
<a href = "http://www.irgendeinewebseite.de/" target="_blank"> Text des Links </a>
```
href ist hier genau wie alt oder align ein Attribut.
## Formulare

Das Element `<form>... </form>` definiert ein Formular. 
Hierin befinden sich, einfacher Text und Input-Elemente, die Eingabefelder darstellen.

Beispiel:
```html

<form>
  Vorname:<br>
  <input type= "text" name="vorname"><br>
  Nachname:<br>
  <input type= "text" name="nachname"><br>
  <input type= "submit">
</form>
```
`<br>` ermöglicht einen Zeilenumbruch.

Durch submit kann die Eingabe des Formulars bestätigt werden.
  
  

