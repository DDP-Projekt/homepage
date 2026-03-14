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

# Verzweigungen und Schleifen

DDP hat natürlich auch Verzweigungen und Schleifen
Es gibt Äquivalente für `if`, `else`, `else if`, `while`, `do-while`, `for`, `for-each` und `repeat`.
Geschweifte Klammern gibt es in der Deutschen Schrift nicht, also benutzen wir Tabs (oder 4 Leerzeichen) um die Tiefe anzugeben.

<br>

Falls nach der Kontrollstruktur nur eine Anweisung folgt, kann man abkürzen.