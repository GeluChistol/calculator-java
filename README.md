# calculator-java
simple calculator written in Java; supports addition, subtraction, multiplication and division

LOC pentru întregul proiect (prin observarea vizuală a celor două fișiere): 214 (188 LOC în fișierul Calculator.java + 26 linii de cod în fișierul Start.java);
Folosind mediul de dezvoltare Intellij IDEA - Code - Calculate Metrics am obținut următorul rezultat: Project Metrics LOC - 153 (aceeași valoare cu LOCp/Lines of product code).

Folosind același mediul de dezvoltare am obținut: complexitatea ciclomatică a metodei evaluateExpression - 12, complexitatea ciclomatică a
metodei Calculate - 12, complexitatea cognitivă a metodei evaluateExpression - 14, complexitatea cognitivă a metodei Calculate - 23. 

Fișier Calculator.java - pachetul implicit fără nume nu ar trebui utilizat;
Fișier Calculator.java - numărul liniei de cod 4 - clasele de utilitate nu ar trebui să aibă constructori publici;
Fișier Calculator.java - numărul liniei de cod 18 - mumele metodelor  și ale câmpurilor nu ar trebui să fie identice sau să se deosebească doar prin scrierea cu majuscule;
Fișier Calculator.java - numărul liniei de cod 24 - mumele metodelor ar trebui să se conformeze convenției de numire;
Fișier Calculator.java - numărul liniei de cod 53 - bucla for ar putea fi înlocuită cu o buclă for îmbunătățită;
Fișier Calculator.java - numărul liniei de cod 70 - este o practică rea ca variabilele locale să fie declarate și returnate imediat;
Fișier Calculator.java - numărul liniei de cod 74 - mumele metodelor ar trebui să respecte convenția de denumire;
Fișier Calculator.java - numărul liniei de cod 183 - jumper-ul return este inutil;
Fișier Start.java - pachetul implicit fără nume nu ar trebui utilizat;
Fișier Start.java - numărul liniei de cod 6 - numele variabilelor locale și parametrii metodelor ar trebui să respecte regulile de definire;
Fișier Start.java - numărul liniei de cod 8 - ieșirile standard nu ar trebui să fie utilizate direct pentru a loga ceva;
Fișier Start.java - numărul liniei de cod 19 - ieșirile standard nu ar trebui să fie utilizate direct pentru a loga ceva;
Am folosit plugin-ul Sonarlint din mediul de dezvoltare Intellij IDEA.
