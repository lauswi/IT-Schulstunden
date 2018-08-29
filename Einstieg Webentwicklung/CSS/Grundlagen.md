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

