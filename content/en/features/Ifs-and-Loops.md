+++
play = 'https://spiel.ddp.im/embed/?share=36fc122f-13bf-49b9-b88f-6776fc457fbc&readonly&nolines'
weight = 1
+++

<!--
Binde "Duden/Ausgabe" ein.
Binde "Duden/Eingabe" ein.

Schreibe "Was ist dein Alter?" auf eine Zeile.
Schreibe "P.S. Diese Daten werden nicht gespeichert, also ist es DSGVO konform ;)" auf eine Zeile.

Solange wahr, mache:
    Wenn die nächste Zahl zwischen 6 und 99 ist, dann:
        Schreibe "Du darfst Monopoly spielen!" auf eine Zeile.
        Verlasse die Schleife.
    Sonst:
        Schreibe "Tut mir leid, du darfst nicht mitspielen :(" auf eine Zeile.
        Schreibe "Bitte versuche es erneut." auf eine Zeile.

[ Collatz-Problem ]
Für jede Zahl z von 5 bis 10, mache:
    Die Zahl n ist z.
    Schreibe (z als Text verkettet mit ": ").
    Wiederhole:
        Wenn n modulo 2 gleich 0 ist, teile n durch 2.
        Sonst speichere n mal 3 plus 1 in n.
        Schreibe n.
        Schreibe "  ".
    5 Mal.
    Schreibe "\n".
-->

# Branches and loops
DDP has branches and loops of course
It has equivalents `if`, `else`, `else if`, `while`, `do-while`, `for`, `for-each` und `repeat`.
Brackets don't exist in german writing, so we use tabs (or 4 spaces) to specify indentation.

<br>

You can shorten the control statement if it has only one statement following it.
