# SEW I - Sommerschule 2021

(Neue Aufgaben sind mit * markiert.)

## _Aufwärmen_ mit _LeonDing_ *

Implementieren Sie eine Methode `convertToLeonDing`, die eine Ganzzahl akzeptiert und gemäß der folgenden Regeln einen `String` zurückgibt:
* Ist die Zahl durch 5 teilbar, so soll `"Leon"` zurückgegeben werden.
* Ist die Zahl durch 7 teilbar, so soll `"Ding"` zurückgegeben werden.
* Ist die Zahl durch 5 **und** 7 teilbar, so soll `"Sommerschule"` zurückgegeben werden.
* Ansonsten soll einfach die Zahl zurückgegeben werden.

Implementieren Sie nun eine Methode `printLeonDing` die eine Ganzzahl zur Angabe der Länge akzeptiert und folgenden Output (beispielsweise für die Länge 30) erzeugt:

```
1 2 3 4 Leon 6 Ding 8 9 Leon 11 12 13 Ding Leon 16 17 18 19 Leon Ding 22 23 24 Sommerschule 26 27 Ding 29 Leon
```

## Primzahlen-Berechnung *
Implementieren Sie eine Methode `isPrime`, die überprüft ob eine übergebene Zahl eine Primzahl ist. Orientieren Sie sich dabei an folgender Angabe:

[Angabe: Primzahlen-Berechnung](Primzahlen.pdf)

## Kosinus-Berechnung mittels _Taylor_-Reihe *
Implementieren Sie eine Methode `calculateCosineByTaylor` die den Kosinus mithilfe einer _Taylor_-Reihe annähert. Orientieren Sie sich dabei an der folgenden Angabe:

[Angabe: Kosinus mittels _Taylor_-Reihe](UebungKosinusTaylor.pdf)

## _FizzBuzz_ Als _Array_ *
Implementieren Sie eine Methode `createFizzBuzzSeries`, die eine Länge akzeptiert und ein _Array_ mit Ganzzahlen erzeugt und zurückgibt. Die Zahlen sollen dabei von 1 bis zur angegeben Länge gehen und gemäß der folgenden Regeln ggf. ersetzt werden:
* Ist die Zahl durch 3 teilbar, so soll `-3` gespeichert werden.
* Ist die Zahl durch 5 teilbar, so soll `-5` gespeichert werden.
* Ist die Zahl durch 3 **und** 5 teilbar, so soll `0` gespeichert werden.
* Ansonsten soll einfach die Zahl gespeichert werden.

Für die Länge 20 würde so folgendes _Array_ entstehen:
`{1, 2, -3, 4, -5, -3, 7, 8, -3, -5, 11, -3, 13, 14, 0, 16, 17, -3, 19, -5}`

Implementieren Sie weiters eine Methode `printFizzBuzzSeries`, die ein _Array_ aus Ganzzahlen akzeptiert und dieses wie im obigen Beispiel ausgibt.

## _Noten Verteilung_
Implementieren Sie die Übung _[Angabe: Noten Verteilung](UebungNotenVerteilung.pdf)_ **unter Zuhilfenahme von Methoden**. Machen Sie sich Gedanken, wie Sie die einzelnen Funktionalitäten sinnvoll aufteilen können.

## _Arrays Dedupen_
Implementieren Sie die Übung _[Angabe: Duplikate Entfernen](UebungDuplikateEntfernen.pdf)_ **unter Zuhilfenahme von Methoden**. Erweitern Sie die Ausgabe am Schluss mithilfe von zwei zusätzlichen Methoden:
* Eine Methode soll das _Array_ spiegeln (i.e. aus `{1, 2, 3}` wird `{3, 2, 1}`).
* Eine Methode soll das _Array_ sortieren (Sortier-Algorithmus frei wählbar).

## _Sieb Des Eratosthenes_ *
Implementieren Sie das _Sieb des Eratosthenes_ zur Ermittlung aller Primzahlen bis zu einer bestimmten Obergrenze. Orienteren Sie sich an folgender Angabe und Animation, verwenden Sie Hilfsmethoden wo diese sinnvoll sind.

[Angabe: _Sieb Des Eratosthenes_](AngabeErathostenes.pdf)

![](images/AnimationEratosthenes.gif)

## Schnittmenge von _Strings_
Implementieren Sie die Übung _[Angabe: Schnittmenge von Zeichenketten](UebungStringIntersection.pdf)_ **unter Zuhilfenahme von Methoden**.

## Wort-Statistik
Implementieren Sie die Übung _[Angabe: Wort-Statistik](UebungWortStatistik.pdf)_.

## Wort-Rate-Spiel *
Implementieren Sie die Übung _[Angabe: Wort-Rate-Spiel](UebungWordGuessingGame.pdf)_ **unter Zuhilfenahme von Methoden**.

## Prüfzahlenberechnungen
Implementeren Sie die Übungen _[Angabe: Sozialversicherungsnummer-Prüfung](UebungSvnrPruefer.pdf)_ und _[Angabe: Kreditkartennummer-Prüfung](UebungCreditCardChecker.pdf)_.

## Anagramm-Checker *
Implementieren Sie die Übung _[Übung: Anagramm-Checker](UebungAnagrammCheckerSortiert.pdf)_.