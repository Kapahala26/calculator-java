OBSERVATION REPORT:

* LOC - 170
* Cyclomatic Complexity for evaluateExpression = 11 - 12 + 2 = 1
* Cyclomatic Complexity for Calculate = 12 - 12 + 2 = 2
* Cognitive Complexity for evaluateExpression = 1 + 1 + 1 + 1 + 1 + 1 + 1 + 1 = 8
* Cognitive Complexity for Calculate = 1 + 1 + 1 + 1 + 1 + 1 + 1 + 1 + 1 + 1 + 1 + 1 + 1 + 1 = 14


1. Calculator.java - Linia de cod 18 - Metoda ToString() ar trebui sa urmeze Java naming convention si ar trebui scris toString()
2. 4. Calculator.Java - Linia de cod 34 - "0 in expression = 0 + expression;" ar trebui sa fie o constanta
3. Calculator.java - Linia de cod 63 - In metoda evaluateExpression catch block va returna "ERROR". Ar fi mai bine sa inregistram exceptia in scop de debugging.
4. Calculator.java - Linia de cod 69 - Metoda Calculate are blocuri de cod repetitive pentru gestionarea diferitelor operațiuni. Acestea pot fi refactorizate pentru a reduce redundanța.
5. Calculator.java - Linia de cod 77 - Ar trebui evitata utilizarea variabilelor statice precum finalResult daca nu este absolut necesar. In schimb, putem lua in considerare returnarea rezultatului direct din metoda.
