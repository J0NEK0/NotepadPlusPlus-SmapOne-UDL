# Notepad++ SmapOne-UDL



<details open>

<summary>Deutsch (Englisch version below)</summary>
Dieses Repository enthält eine benutzerdefinierte Sprache (UDL) für SmapOne Formeln zur Verwendung in Notepad++.
SmapOne verfolgt einen low-code / no-code Ansatz mit einer Syntax die Excel stark ähnelt.
Ohne Zeilenumbrüche, Einschübe und Einklappen können komplexere Formeln schnell schwer zu lesen und verstehen sein (besonders wenn extra Bausteine als "Variablen"-Speicher vermieden werden sollen).
Um dem Abhilfe zu verschaffen, können andere Editoren wie Notepad++ verwendet werden, um komplexere Formeln besser lesbar zu machen.

Das Bild am Ende zeigt dieselbe Formel aus der [Beispieldatei](/smapone%20example.smap) im Web-Editor (links) und in Notepad++ unter Verwendung dieser UDL (rechts).
Wenn Dich die rechte Seite mehr anspricht, wird Dir diese UDL sicherlich helfen.

## Einrichtung
1. Lade [SmapOne.xml](/SmapOne.xml) (oder [SmapOne+.xml](/SmapOne+.xml) für einige zusätzliche Hervorhebungen) herunter.
2. Öffne Notepad++ und navigiere zu *Sprache -> Benutzerdefinierte Sprache -> Eigene Sprache definieren*.
3. Drücke auf *Importieren*.
4. Wähle die heruntergeladene XML-Datei aus.
5. Schließe den Dialog und starte Notepad++ neu.
6. Navigiere wieder zu *Sprache* und wähle `SmapOne` oder `SmapOne+` unterhalb des Eintrags *Benutzerdefinierte Sprache* aus, um die Hervorhebungen (Sprache) für die aktuell geöffnete Datei zu aktivieren.

Notepad++ sollte von nun an automatisch diese Sprache für jede neu geöffnete Datei mit der Endung *.smap* oder *.smapone* auswählen.
> Tipp:
> Um diese UDL individuell anzupassen, gehe zu *Sprache -> Benutzerdefinierte Sprache -> Eigene Sprache definieren* und wähle `SmapOne` oder `SmapOne+` im Dropdown-Menü.
</details>

---

<details>

<summary>English</summary>
This repository provides a Notepad++ User-defined Language (UDL) for the syntax used by SmapOne formulas.  
SmapOne pursues a low-code / no-code approach using a syntax similar to Excel.
Absent line-breaks, indentations and folding, more complex formulas can be difficult to read and understand (especially if extra building blocks to store "variables" should be avoided as much as possible).
This can be alleviated by using another editor such as Notepad++ to create a more human readable view of complex formulas.

The image at the end displays the same formular from the [example file](/smapone%20example.smap) in the web-editor (left) and in Notepad++ using this UDL (right).
Feel free to make use of this UDL if the right side looks more appealing to you!

## Setup
1. Download [SmapOne.xml](/SmapOne.xml) (or [SmapOne+.xml](/SmapOne+.xml) for a few extra highlightings)
2. Open Notepad++ and go to *Language -> User Defined Language -> Define your language*
3. Click *Import*
4. Select the XML-file you saved
5. Close the dialog and restart Notepad++
6. Go to *Language* again and select `SmapOne` or `SmapOne+` right under *User Defined Language* to enable the highlighting for a file in your current session

Notepad++ should automatically select the language for every *.smap* or *.smapone* file opened from now on.
> Tip: 
> To customize this UDL, go to *Language -> User Defined Language -> Define your language* and select `SmapOne` or `SmapOne+` in the dropdown menu.

</details>

![smapone highlighting example image](/smapone%20example%202.png)
