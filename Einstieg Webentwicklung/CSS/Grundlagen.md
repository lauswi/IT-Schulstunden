# CSS Grundlagen

Was genau ist [CSS](https://de.wikipedia.org/wiki/Cascading_Style_Sheets) und wofür wird es verwendet? 

CSS steht für Cascading Style Sheet. Es handelt sich hierbei um eine Programmiersprache, bei der es um die Gestaltung und Anordnung der Elemente einer Webseite geht. Es können hierdurch zum Beispiel Farben oder Schriftarten verändert werden.

## Einbindung
Es gibt verschiedene Möglichkeiten CSS in das Coding einer Webseite einzubringen. 

Zum Beispiel können die CSS Funktionen als Attribute in das HTML Skript eingebaut werden. 
```html
<h1 style="color: orange;"> Irgendeine Überschrift</h1>
```
Der Text "Irgendeine Überschirft" wird jetzt in orange angezeigt.


Da diese Methode aber bei vielen CSS Befehlen unübersichtlich wird, sollte CSS extern eingebunden werden.

### Externe Einbindung
Im `<head>` des HTML Dokuments muss eine Referenz auf das CSS Dokument eingebunden werden.
```html
<head>
  <link rel="stylsheet" href="cssdokument.css">
</head>
```
#### Tags
Kann für einen bestimmten Tag ein Design festgelegt werden, also zum Beispiel für alle Überschriften kann dieser im CSS Dokument als Selector definiert werden.

Bsp.: 
```css
h1{
  color: green;
  background-color: aqua;
  font-family: Arial;
}
```

Alle Überschirften mit dem Tag `<h1>` würden hiernach mit grüner schriftfarbe, blauer Hintergrundfarbe und in der schirftart arial angezeigt. 

#### IDs
Alternativ kann eine ID verwendet werden, um verschiedenen Elementen ein Design zuzuordnen. 

Im HTML Dokument:
```html
<p id="blauer_absatz"> Das ist ein blauer Absatz </p>
```
Die ID kann dann folgendermaßen im CSS Dokument definiert werden.

```css
#blauer_absatz {
  color: blue;
}
```

#### Klassen
Außerdem können Designs auch als Klassen eingebunden werden. 

Im HTML Dokument:
```html
<p class= "blau"> Das ist ein blauer Absatz </p>
```

Im CSS Dokument:

```css
.blau {
color: blue;
}
```

## Farben

Farben können sowohl namentlich, aber auch durch das RGB-Modell angegeben werden. 
Hier wird die Farbe durch die Angabe von drei Werten "gemischt".

Bsp.: 
```css
.p_rot{
  color: rgb(255,0,0);
}
```

Hier wird beispielsweise Rot als Farbe angegeben.

`rgb(0,255,0)` ist grün und `rgb(0,0,255)` ist blau. 

#### weitere Attribute

- font-size = Schirftgröße
- font-weight = Transparenz der Schirft (Bsp.: bold, light,...)
- background-collor = Hintergrundfarbe
- font-family = [Schriftart](https://en.wikipedia.org/wiki/List_of_typefaces_included_with_Microsoft_Windows) (Achtung! Die schönste Schriftart bei der Entwicklung hilft dir nichts, wenn sie der User nicht hat) 

## Das Box Modell

![Boxmodell](IT-Schulstunden/Einstieg Webentwicklung/CSS/boxmodell.png)





