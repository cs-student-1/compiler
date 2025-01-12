Linksableitung
===

Eine Linksableitung ist die Ableitung des am weitesten links stehenden 
Nichtterminals.

## Beispiel

G={{A,B,C,S}, {a,b,c}, S, P}

mit P:

```
S -> ABC
A -> Aa | $
B -> Bb | $
C -> Cc | $
```

Wenn **AaBbbCccc** gegeben ist, sind zwei Linksableitungen möglich, 
nämlich genau die Ableitungen der Variable **A**:

**AaaBbbCccc** oder **aBbbCccc**
