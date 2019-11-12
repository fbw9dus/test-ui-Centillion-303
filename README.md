# Phone company site
Projekt für Test im UI Modul

- Schreib das HTML und CSS für die abgebildete Seite
- Die Seite soll responsive sein und sich auf unterschiedlichen Bildschirmbreiten entsprechend der Abbildungen verhalten.

## Anforderungen HTML
- Die Seite soll auf dem Handy bzw. im DevTools-Simulator nicht kleiner skaliert/kleiner gezoomt werden.
- Einrückung der Kinder-Elemente im Code
- Korrekte Dateipfade
- Beschreibende Klassen- oder ID-Namen für Elemente vergeben
## Anforderungen CSS
- Selektoren so speizifisch schreiben, dass unabsichtliche Auswirkungen auf andere Teile der Seite vermieden werden.
- Kein float zum Anordnen von Block-Elementen
- Style-Werte, die sowieso standardmäßig vom Browser gesetzt werden, nicht im CSS deklarieren.

![](drafts/mobile.JPG)
![](drafts/tablet.JPG)
![](drafts/desktop.JPG)
![](drafts/desktop-button-hover.JPG)

###   48/60 Punkten
#### Punktabzüge für:
- [x] (4) Elemente passen sich nicht an Fensterbreite an
```diff
- Der Text und das Formular sind bei mittlerer Fensterbreite untereinander, statt sich in der Breite nebeneinander einzupassen 
```
- [_] (10) Tags nicht geschlossen oder falsch verschachtelt
- [_] (5) Block-Tag in Inline-Tag
- [x] (3) Kinder-Tags im Code nicht eingerückt
```diff
- Im Bereich zwischen Zeilen 57 und 92 ist schwierig Kinder- und Eltern-Elemente zu unterscheiden
```
- [x] (5) Zweckfremde Tags verwendet
```diff
- In @font-face wird "local()" verwendet um eine Schriftart einzubinden, die schon auf dem Computer installiert ist. Um Eine Schriftart-Datei zu laden, muss statt dessen url() verwendet werden
```
- [_] (10) Fehlende essetielle Tags (z.B. Meta-Tags)
- [_] (5) Falsche Datei-Pfade
- [_] (10) CSS-Selektoren, die bei Änderungen im HTML sehr leicht fehlschlagen können
- [_] (5) Fehlende essentielle Tag-Attribute
