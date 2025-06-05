# NotepadPlusPlus-SmapOne-UDL
This repository provides a Notepad++ User-defined Language (UDL) for the syntax used by SmapOne formulas.  
SmapOne pursues a low-code / no-code approach but formulas can get very hard to read quite fast, especially when you want to avoid extra building blocks (to store "variables") as much as possible.

![smapone highlighting example image](/smapone%20example.png)
Make SmapOne formulas easier to understand and debug using indentation.

## Setup
1. Download [SmapOne.xml](/SmapOne.xml) (or [SmapOne+.xml](/SmapOne+.xml) for a few extra highlightings)
2. Open Notepad++ and go to *Language -> User Defined Language -> Define your language*
3. Click *Import*
4. Select the XML-file you saved
5. Close the dialog and restart Notepad++
6. Go to *Language* again and select `SmapOne` or `SmapOne+` right under *User Defined Language* to enable the highlighting for a file in your current session

Notepad++ should automatically select the language for every *.smap* or *.smapone* file opened from now on.
> [!TIP]
> To customize this UDL, go to *Language -> User Defined Language -> Define your language* and select `SmapOne` or `SmapOne+` in the dropdown menu.
