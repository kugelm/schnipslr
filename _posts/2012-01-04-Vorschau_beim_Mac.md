---
titel: Vorschau beim Mac - das unterschätzte Tool
layout:post
date: 2012-01-04
---

Vorschau ist mit Sicherheit eines der am meisten unterschätzen Programme. Wenn man Quartz Filter richtig einsetzen kann, 
dann kriegt man einige Probleme (z.B. viel zu dicke PDF Dateien) auch vernünftig [gelöst](http://www.blog-it-solutions.de/mac-os-pdf-dateien-verkleinern-optimieren/):


1. ColorSync-Dienstprogramm öffnen (unter Programme -> Dienstprogramme -> ColorSync-Dienstprogramm)
2. Auf den Reiter “Filter” wechseln
3. Mit dem Zeichen + einen neuen Filter anlegen und z.B. den Namen “PDF optimiert” vergeben.
4. Klicken Sie in der neu angelegten Zeile auf den grauen Pfeil auf der rechten Seite und wählen Komponente für Bildeffekt hinzufügen und anschließend Bild Komprimierung.
5. Als Werte vergeben Sie bei Modus “JPEG” und bei Qualität platzieren Sie den Slider bei etwa 80 % (siehe Grafik bei Punkt 6).
6. Klicken Sie anschließend erneut auf den grauen Pfeil auf der rechten Seite und wählen Komponente für Bildeffekt hinzufügen und Bild-Anpassung (Farbe). 
7. Jetzt ist der passende Filter erstellt und muss nur noch an den richtigen Ort kopiert werden. Schließen Sie hierzu das ColorSync-Dienstprogramm und navigieren zum gerade angelegten Filter im versteckten Ordner /Users/IhrBenutzername/Library/Filters/
8. Um zu diesem versteckten Ordner zu navigieren, können Sie die Funktion “Gehe zum Ordner …” verwenden. Hierzu klicken Sie auf den Schreibtisch, wählen “Gehe zu” in der Menüleiste und dann “Gehe zum Ordner …”
9. Die dort hinterlegte Datei mit dem von Ihnen vergebenen Namen kopieren Sie in den Ordner /System/Library/Filters/
10. Bitte beachten Sie, dass hierbei die Eingabe des Administratorkennworts notwendig ist.
11. Der Filter steht nun im Mac OS X Programm Vorschau unter Ablage -> Exportieren … und dann bei Quartz-Filter zur Verfügung.
