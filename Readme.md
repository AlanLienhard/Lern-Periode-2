





# Lernperiode 2



## Grobplanung

Alan Lienhard

Lernperiode 2 von nach den Herbstferien bis zu den Weihnachtsferien



#### 20.10.2023

- [x]  Am OBA von M431 arbeiten

- [ ] Am Eportfolio von M319 arbeiten

- [ ]  Falls Zeit übrig ist, an dem Programmierprojekt arbeiten, das ich in der letzten Woche von Lernperiode 1 begonnen habe, weiter arbeiten

 
Heute habe ich am OBA-Portfolio vom Modul431 gearbeitet. Leider habe ich daran arbeiten "müssen", weil ich, wie viele andere auch, am Mittwoch haben, dass das "O" in OBA, das optional bedeutet, nicht für die Schüler so ist, sondern für die Lehrer. Ich habe bis zur 15:00 Uhr Pause gearbeitet, bis es in der Pause dann einen gewissen Unterbruch gab. Danach konnte ich mich nicht so konzentrieren wie vor der Pause.
Nächste Sitzung möchte ich weiter an meinem Programmierprojekt arbeiten, damit ich dort Fortschritt mache, und weil das auch mehr Spass macht.
Ich hätte mich heute besser konzentrieren können und ich will das auch nächste Woche so machen.
In dem Projekt will ich lernen, mit Dateien auf meinem PC/Notebook zu programmieren, Dateien (z.B. txt) ändern und zu verschieben, ähnlich wie im Linux Terminal mit "cd, move, ...". (136 Wörter)
### Arbeitspaket für 27.10.2023

-[ ] An meinem Programmierprojekt arbeiten.

Ich konnte heute nicht an meinem Programmierprojekt nicht arbeiten, weil ich doch noch Einiges für mein ePortfolio M319 machen musste. Nächste Woche sollte ich dann nächste Woche endlich an meinem Programmierprojekt arbeiten können. Die M319 Abgabe ist diesen Sonntag 23:59 Uhr, und ich habe sonst noch keine grossen Schulprojekte, die die zusätzliche Zeit im Lernatelier benötigen, also sollte ich die restliche Lernperiode (hoffentlich) Zeit haben, an meinem Programmierprojekt zu arbeiten.

### Arbeitspaket für 3.11.2023

-[ ] An meinem Programmierprojekt arbeiten

Ich habe heute am Programmierprojekt mit Amar und Ylli gearbeitet (ist ein Gruppenprojekt, das Projekt bei Herrn Fähndrich). Bei unserem Projekt erstellen wir einen Hypothekenrechner. Zuerst wollen wir es in der Konsole machen, und wenn die Zeit übrig bleibt, fügen wir ein GUI (Graphical User Interface zu). Das Programm kann bisher die Hypotheken berechnen, berechnen ob eine Hypothek überhaupt nötig ist und ob man die Hypothek tragen kann (genug Geld und Einkommen hat). Das Programm kann noch keine Exceptions behandeln (z.B. wenn jemand bei der User-prompt "Kaufpreis der Immobilie:" Buchstaben oder Sonderzeichen eingibt, stürzt das Programm zurzeit ab, aber es sollte mit dieser Ausnahme umgehen können. (106 Wörter) ![image](https://github.com/AlanLienhard/Lern-Periode-2/assets/142605666/600c4147-f9c4-4eae-8241-1812ddbf2034)

```csharp
Console.WriteLine();
```
´

### Arbeitspaket für 10.11.2023

- [x] Projekt Exception-Verarbeitung hinzugüfen
- [ ] Wenn nichts mehr zu erledigen ist, an eigenem Projekt (Files verschieben und ändern) arbeiten

     Heute habe ich am Gruppenprojekt bzw. dem Hypothekenrechner gearbeitet. Ich habe Exception-Behandlungen hinzugefügt, damit, wenn der User Buchstaben oder andere Zeichen eingibt, die nicht Zahlen sind, das Programm nicht "unkommentiert" abstürzt. Nämlich kommt da dann eine Fehlermeldung. Ich möchte noch für nächstes Mal probieren, dass anstatt, dass nur eine Fehlermeldung kommt und dann das Programm fertig ist, dass man dann eine Möglichkeit hat, zurück Zum Anfang des Programmes zu gehen. Wenn ich dann noch Zeit habe, möchte ich mit meiner Gruppe anfangen, an einer GUI Version  mit WindowsForms (oder ähnliches, weil Ylli's Macbook OSx hat) zu arbeiten. Ich stelle mir vor, dass das mit Exceptions (try + catch) und mit "go to" funktionieren würde. (114 Wörter)

### Arbeitspaket für 17.11.2023

- [ ] go to Funktion einfügen
- [x] Anfangen, ein GUI zu machen

Wir haben in dieser Session anstatt die go to Funktion die "out" Funktion benutzt. Unser Code für unser Command Line Interface ist so ziemlich "vollendet" bzw. fertig. Was wir jetzt noch tun müssen, ist das "importieren" unseres Codes in unser GUI WindowsForms Projekt (das wird nicht mit Copy & Paste funktionieren). Unser Programm kann auch damit umgehen, wenn eines der gespeicherten Werte "0" beträgt, ein Buchstaben oder Sonderzeichen hat, das Programm weist auch den Benutzer auf dieses Problem hin und verlangt wieder eine Prompt bzw. Eingabe vom Benutzer. Also fängt das Programm wieder "von vorne" an.  (96 Wörter)

### Arbeitspaket für 24.11.2023

- [x] Code in GUI übertragen
- [ ] Falls Zeit übrig bleibt, GUI verschönern

Heute haben wir den Code (noch nicht vollständig) von unserem CLI-Prototyp in unseren GUI-Prototyp "portiert". Wir wollen damit am Montag, oder spätestens im nächsten Lern-Atelier damit abschliessen.
Wir haben bei uns noch einen logischen Fehler in unserer Berechnung der Amortisationskosten (obligatorische Rückzahlung der zweiten Hypothek). Es war leider problematisch, bei WinForms zu livesharen, da man nur den Code sharen konnte, aber nicht das Forms-Design. Dadurch konnten wir nicht sehr effizient zusammenarbeiten. 
Wir wollen nächstes mal fertig werden mit dem Portieren vom Code, den Fehler in unserer Amortisationsrechnung beheben und das Forms-Design übersichtlicher (mit z.B. Buttons und symetrischem Design) übersichtlicher machen. (100 Wörter)


### Arbeitspaket für 01.12.2023

- [ ] Code fertig in GUI-Application portieren
- [ ] Fehler in den Amortisationsberechnung beheben
- [ ] GUI übersichtlicher machen


In der Gruppe haben wir heute uns vor allem darauf konzentriert, den Fehler in den Amortisationsformel zu beheben. Die zwei GUI Arbeitspakete hatten unterste Priorität, denn es war für uns wichtig, dass unser Programm Berechnungen richtig durchführt. Wir haben es leider nicht geschafft, obwohl wir auch im Internet eine Formel gefunden haben, diese funktioniert auch eigentlich. Jedoch hat sie bei unserer Zahlen, die wir als "Standart zum Testen probieren", nicht funktioniert. ![image](https://github.com/AlanLienhard/Lern-Periode-2/assets/142605666/6c067296-0769-41e1-beda-c6aa1ff3187d) (Ein Bild der Formel vom Youtube-Video https://youtu.be/lkNJvsy0qU8?si=DeG1Wz05AjcE6OZF )

Nächstes mal möchte ich AdventOfCode machen, um meine Programmierfähigkeiten zu verbessern und für abwechlungsreiche Projekte. Wenn ich das doch nicht interessant finde (was ich bezweifle) möchte ich noch ein neues Projekt, alleine machen, aber ich muss mir dann auch noch Zeit nehmen, ein Thema auszuwählen. (125 Wörter)

### Arbeitspaket für 08.12.2023

- [ ] AdventOfCode Rätsel/Aufgaben lösen (auch von vorherigen Tagen nachholen und nicht nur vom 08.12. machen)
- [x] Neues Projekt starten und Thema auswählen (falls mir AoC nicht reicht)

Ich habe zuerst heute mit AoC begonnen, aber ich schlug da fehl, weil, ich es so dachte, dass mir das nötige Programmierwissen und die Progerammiererfahrung fehlt. Daher habe ich mich entschieden, ein neues Projekt anzufangen. Es ist kein richtiges eigenständiges Projekt, sondern ein Kurs. Der Kurs, für den ich mich entschied heisst "TheOdinProject". Da lernt man hauptsächlich, mit Linux zu arbeiten (falls man sich für Linux entscheidet) und FullStack Development. Ich dachte, das sei eine gute Entscheidung, weil ich viel Gutes darüber gehört habe und dachte, das sei ein guter Weg um auch alleine (ausserhalb der Schule) Coden zu lernen. Ich denke (und hoffe auch), dass es nicht zu schwierig sein soll, mein (dort erlangtes) Wissen von CSS, HTML und Javascript in C# umzuändern. Man lernt dort auch, Git zu benutzen.
Heute habe ich erst angefangen und also noch nicht gecodet. Ich habe auf meinem Laptop eine DualBoot Version von Linux Ubuntu installiert und zum Laufen gebracht (157 Wörter).
![image](https://github.com/AlanLienhard/Lern-Periode-2/assets/142605666/b638a19c-b8c0-4c82-b506-db6c04bc5693)


### Arbeitspaket für 15.12.2023

- [x] weiter an TheOdinProject (ToP) arbeiten (Kurs befolgen)

Ich habe heute wie geplant den Kurs befolgt. Im Kurs waren Basics über HTML und es wurde erklärt, wieso und wozu man HTML, CSS und JavaScript für Websiten verwendet.
Es wurde auch erklärt was HTML-tags und Elemente sind. In dem Kurs ist nicht nur Theorie, sondern er fordert auch Einen auf, Fragen zu beantworten oder auch Probleme bzw. Aufgaben zu lösen.
Ich möchte nächstes Mal daran weiter arbeiten. Es gibt da auch eine "lesson" (wie Unterkapitel) namens "Git basics". Ich habe diese heute übersprungen, weil ich heute mit HTML beginnen wollte, aber ich möchte die Git basics nächstes Mal nachholen. Vielleicht lerne ich etwas über Git (vorallem Github), was ich noch nicht wusste (113 Wörter).

### Arbeitspaket für 22.12.2023

- [x] In ToP "GitBasics" nachholen und durcharbeiten
- [ ] In ToP an den HTML Basics weiterarbeiten

Ich habe heute vieles über Git gelernt. Zum Beispiel, dass Git ein sogenanntes Version Control System ist. Es ist auch ähnlich wie eine Cloud (OneDrive, GoogleDrive), aber es hat einige Vorteile. Wenn man eine Datei aktualisiert/ändert, kann man auch, wenn man will, zu einer vergangenen Version wechseln. Das heisst, man "verliert" eine Version der Datei nicht und kann bei fehlerhaften Dateien auf die alte, noch funktionierende Version zurückgreifen.
Daten miteinander auszutauschen ist auch viel einfacher und schneller als bei vielen anderen Dienste. Normale CLouds sind abhängig von Servern, wenn diese ausfallen, kann man den Dienst nicht mehr benutzen (temporär). Git ist zentralisiert, d.h. es tauscht die Daten unter den Benutzern aus (so wie ich es verstanden habe, ist es ähnlich wie Peer-to-Peer hosting) (123 Wörter).


## Reflexion

