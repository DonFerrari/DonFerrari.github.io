---
layout: post
title: Gruppenarbeit Vokabelabfrage per .csv-Datei
---










## Aufgabestellung 

An meiner Schule (BBBaden) haben wir den Auftrag bekommen ein Programm mit C# zu programmieren, bei der man ein Programm programmieren sollte, das Vokabeln einer Datei abfragt. Der Benutzer kann dann die Wörter übersetzen.

## Ziele
-Das Programm kann Daten aus einer .csv-Datei aufrufen.



## Inhalt
Ich habe nun 3 Inhalte:
1. Ein Bild vom Programm
2. Ein Ausschnitt vom Code
3. Ein Video vom Code und Programm

### Inhalt 1

Hier ist ein Bild des Programms.
![Code](https://snipboard.io/ornE53.jpg)

### Inhalt 2

Hier ist ein Teil des Codes.

```
 if (sprache == "Italienisch" || sprache == "i" || sprache == "I" || sprache == "italienisch")
    {
        string inPath = @"italianwords.csv";
        string text = File.ReadAllText(inPath);

        string[] lines = text.Split("\r\n");
        int words = lines.Length;
        string[] italienisch = new string[words];
        string[] deutsch = new string[words];


        for (int line = 0; line < lines.Length; line++)
            {
               string[] items = lines[line].Split(',');
               italienisch[line] = items[0];
               deutsch[line] = items[1];
            }
```

### Inhalt 3
Hier ist ein Video dazu: ---> [video](https://www.youtube.com/watch?v=zx16Kk15Uz8)

## Reflektion und Verifikation

### Reflektion
Das Programm ist vollständig und funktioniert einwandfrei. Wir sind sehr zufrieden damit. Wir haben auch als Team gut gearbeitet und hatten wenig Probleme beim zusammen arbeiten. Ich habe neu gelernt, wie man .csv-Dateien aufrufen kann mit dem Programm.

Wir hatten Schwierigkeiten beim Abfragen der Wörter und beim Speichern der falsch geschrieben Wörter. Aber das hat sich dann auch erledigt.

Beim nächsten Mal sollten wir ein Bisschen mehr besprechen wer was macht.

### Verifikation 
Die Ziele wurden ereicht: 

-Denn, das Programm kann Daten aus einer Datei aufrufen. ✓✓




