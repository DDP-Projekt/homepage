+++
play = 'https://spiel.ddp.im/embed/?share=7520d016-fc4e-4d81-a7f4-36f35ea17314&nolines&readonly'
weight = 3
+++

<!--
Binde "Duden/Ausgabe" ein.

Wir nennen die öffentliche Kombination aus
	der Zahl x mit Standardwert 0, [(für andere Module) privates Feld]
	der öffentlichen Zahl y mit Standardwert 0, [öffentliches Feld]
einen Vektor2, und erstellen sie so:
	"Nullvektor" oder
	"der Nullvektor" oder [kein Parameter]
	"ein Vektor2 mit x gleich <x>" oder [1 Parameter]
	"ein Vektor2 mit x gleich <x> und y gleich <y>" [alle Parameter]

Die Funktion Schreibe_Vektor mit dem Parameter v vom Typ Vektor2, gibt nichts zurück, macht:
    Schreibe (x von v).
    Schreibe "/".
    Schreibe (y von v) auf eine Zeile.
Und kann so benutzt werden:
    "Schreibe <v>" oder "Schreibe den Vektor2 <v>"

Der Vektor2 v1 ist der Nullvektor.
Schreibe v1.

Schreibe (ein Vektor2 mit x gleich 1).

Der Vektor2 v2 ist ein Vektor2 mit x gleich 5 und y gleich 8.
Schreibe v2.
-->

# Combinations
Of course, the standard data types won't always be enough. That's why you can define your own!

<br>

In DDP we call them combinations, as they consist of multiple data types.
Combinations don't contain functions though, so don't think we're in OOP paradise here.

<br>

Like functions, combinations are also given aliases. These determine how the combination is created.