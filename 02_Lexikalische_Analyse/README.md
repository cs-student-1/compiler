Lexikalische Analyse
===

Die Lexikalische Analyse ist die erste 
[Phase des Compilers](../01_Einführung/Compiler_Phasen/README.md).
Sie liest Zeichenketten zu **Tokenobjekten**. Das Programm, welches die 
Token erzeugt heißt [Scanner](./Scanner/README.md). Die Zeichenkette, 
welche zu einem einzelnen Token wird, heißt **Lexem**.

Meistens wird der Scanner als Unterprogramm vom Parser aufgerufen und gibt nach jedem Aufruf ein einzeles Token zurück (siehe [Interaktion mit Parser](./Scanner/Interaktion_mit_Parser/README.md)). 
