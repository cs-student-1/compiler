Fehlerbahandlung (Syntaxanalyse)
===

Der gößte Teil der Fehlerbehandlung findet in der Syntaxanalyse statt, 
da viele Fehler syntaktischer Natur sind

## Ziele der Fehlerbehandlung

- Fehler präzise melden
- die Verarbeitung korrekter Programme soll nicht unverhältnismäßig verlangsamt werden
- Nach dem Fehler wiederaufsetzen, um Folgefehler zu entdecken

## Fehler finden

Manche Parse-Methoden, wie die **LL- oder LR-Methode** entdecken einen 
Syntaxfehler zum frühest möglichen Zeitpunkt. Sie erkennen das Auftreten 
eines Fehlers in dem Moment, in dem das gelesene Präfix der Eingabe 
nicht mehr Präfix eines Wortes der Sprache sein kann. 
