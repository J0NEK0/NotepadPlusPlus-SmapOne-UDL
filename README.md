# Notepad++ SmapOne-UDL



<details open>

<summary>Deutsch (Englisch version below)</summary>



</details>

---

<details>

<summary>English</summary>
This repository provides a Notepad++ User-defined Language (UDL) for the syntax used by SmapOne formulas.  
SmapOne pursues a low-code / no-code approach using a syntax similar to Excel.
Absent line-breaks, indentations and folding, more complex formulas can be difficult to read and understand (especially if extra building blocks to store "variables" should be avoided as much as possible).
This can be alleviated by using another editor such as Notepad++ to create a more human readable view of complex formulas.

The image below compares the same formular from [smapone example](/smapone%20example.smap) in the native editor (left) and in Notepad++ using this UDL (right).
If you think the right side makes it easier to understand and explain, then this UDL can help you!

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
