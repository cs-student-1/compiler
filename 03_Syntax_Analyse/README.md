Syntaxanalyse
===

Die Syntaxanalyse ist die zweite 
[Phase](../01_Einführung/Compiler_Phasen/README.md) des Compilers. Sie 
wird vom **Parser** ausgeführt.

Der Parser nimmt die Token vom Scanner und produziert als **Output** einen 
Ableitungsbaum, Syntaxbaum oder Zwischencode.

Falls noch nicht vom Scanner erledigt, werden Bezeichner in die 
[Symboltabelle](../01_Einführung/Symboltabelle/README.md) eingetragen.
Außerdem werden **Fehler** erkannt.

## Arten von Parsern (Analysestrategien)

Es gibt im wesentlichen das [Top-Down](./Top_Down_Parsing/README.md) und 
das [Bottom-UpParsing](./Bottom_Up_Parsing/README.md). 

## Sackgassen

**Sackgassen** sollten vermieden werden, da 
**Backtracking** sehr aufwändig ist.

## Fehlbehandlung

Der gößte Teil der Fehlerbehandlung findet in der Syntaxanalyse statt.
[Syntaktische Fehler](./Fehlerbehandlung/README.md) sind zB. falsche Klammerungen. 

~~## Recovery-Strategien~~

~~Im wesentlichen gibt es folgende ~~
~~[Recovery-Strategien](./Recovery_Strategien/README.md):~~

~~1. Panische Recovery~~
~~2. Konstrukt-orientierte Recovery~~
~~3. Fehlerproduktionen~~
~~4. Globale Korrekturen~~
