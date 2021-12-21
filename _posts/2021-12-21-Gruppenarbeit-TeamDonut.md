---
layout: post
title: Gruppenarbeit TeamDonut (QuizSpiel)
---




## Aufgabestellung 

An meiner Schule (BBBaden) haben wir den Auftrag bekommen ein Quizspiel mit C# zu programmieren. Wir haben dieses Programm mit C# erstellt und Windows Forms genutzt.

## Ziele

Bei diesem Portfolio lernt man:

-Wie man macht, dass das Programm bei einer richtigen Antwort ein neues Fenster öffnet und das alte schliesst.

-Wie man macht, dass das Programm bei einer falschen Antwort das "Gameover" Fenster öffnet und das alte schliesst



## Inhalt
Ich habe nun 3 Inhalte:
1. Ein Bild vom Code
2. Ein Ausschnitt vom Code
3. Ein Video vom Fenster-Wechsel (Gameover und richtige Antwort)

### Inhalt 1

Hier ist ein Bild des Codes.
![Code](https://snipboard.io/QFlw5D.jpg)
### Inhalt 2

Hier ist ein Teil des Codes. 

```
 private void button2_Click(object sender, EventArgs e)
        {


            this.Hide();
            var form3 = new Form3();
            form3.Closed += (s, args) => this.Close();
            form3.Show();
        }
```

### Inhalt 3
Hier ist ein Video dazu: ---> [video](https://www.youtube.com/watch?v=Ac4kUrP93yg)

## Reflektion und Verifikation

### Reflektion
Das Programm ist vollständig und funktioniert einwandfrei. Wir sind sehr zufrieden damit. Wir haben auch als Team gut gearbeitet (auch wenn wir nicht immer vollzählig waren) und hatten wenig Probleme beim zusammen arbeiten. 

Ich habe neu gelernt mit Windows Forms zu arbeiten. 

Wir hatten Schwierigkeiten beim erstellen eines neuen Forms aber das haben wir dann am Schluss doch noch geschafft.

Beim nächsten mal sollten wir auch von zu Hause arbeiten können, da viele von uns recht häufig fehlten.

### Verifikation 
Die Ziele wurden ereicht, denn:

-Das Programm öffnet bei einer richtigen Antwort ein neues Fenster und schliesst das alte.  ✓✓

-Das Programm öffnet bei einer falschen Antwort das "Gameover" Fenster und schliesst das alte.  ✓✓




