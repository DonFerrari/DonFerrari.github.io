---
layout: post
title: The Random-Number-Guesser
---


# The Random-Number-Guesser



## Aufgabestellung

An meiner Schule (BBBaden) haben wir den Auftrag bekommen ein Programm zu programmieren, bei der man eine zufällige Zahl zwischen 1 und 100 schreiben kann kann und dann sagt einem das Programm ob man richtig liegt oder ob die Zahl tier oder höher ist als getippt.

## Ziele
-Ich kann den While-Loop in Kombination mit dem If befehl.

-Ich kann eine Zufällige Zahl programmieren.

-Das Programm ist simpel gestaltet.


## Inhalt
Ich habe nun 3 Inhalte:
1. Ein Bild vom Programm
2. Ein Ausschnitt vom Code
3. Ein Video vom Code und Programm

### Inhalt 1
![Code](https://snipboard.io/nhdMb9.jpg)
### Inhalt 2
```
 if (input < random && input > 0)
                            {
                                Console.WriteLine("zu niedrig");
                                ++versuche;

                            }
                            else if (input > random && input < 101)
                            {
                                Console.WriteLine("zu hoch");
                                ++versuche;

                            }
                            else if (input > 101 || input < 0 || input == 0)
                            {
                                Console.WriteLine("Es soll zwischen 1 und 100 sein!");
                                

                            }
                            else if (input == random)
                            {
                                Console.WriteLine("Richtig!!");


                                Console.ForegroundColor = ConsoleColor.Blue;

                                Console.WriteLine("Bravo du hast es geschaft mit " + versuche + " Versuch(e) ");
                                Console.WriteLine("Willst du nochmal spielen?[ja/nein]");
                                start = Console.ReadLine();
                                break;

                            }
```

### Inhalt 3
Hier ist ein Video dazu: ---> [video](https://www.youtube.com/watch?v=ak6MK-RCAaQ)

## Reflektion und Verifikation

### Reflektion
Das Programm ist vollständig und funktioniert einwandfrei. Ich bin sehr zufrieden damit.

Ich könnte beim nächsten mal etwas besser planen was ich wann machen soll, denn manchmal habe ich nicht das gemacht was ich vor hatte oder sogar zu viel auf einmal gemacht.

### Verifikation 
Die Ziele wurden ereicht: 
-Denn ich kann nun den While-Loop in Kombination mit dem If befehl
-Denn ich kann eine Zufällige Zahl generieren
-Denn es ist simpel gestaltet


