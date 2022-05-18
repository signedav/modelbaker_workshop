# modelbaker_workshop

## Einladungstext

D: Einführung in QGIS Model Baker und Datenvalidierung

Einführung in das Erstellen von QGIS-Projekten zum Erfassen von Geodaten basierend auf Interlis-Datenmodellen. Im Workshop wird gezeigt wie man QGIS-Projekte aus Interlis-Datenmodellen erstellt, wie man Zusatzinformationen aus dem "UsabILIty-Hub" nutzt, wie man Interlis-Daten importiert und exportiert und wie man die editierten Daten gegen das Datenmodell validiert und Fehler behebt.

## Programm

- Empfehlung QGIS 3.22
- Download ILI und XML KbS_1

1. Einführung (romedi) 15'
   1. GitHub
   2. Issues
   3. Organisation
   4. Finanzierung
2. Workshop
   1. Download TG und SH über geodienste.ch (romedi) 10'
   2. Start QGIS Installation Model Baker (dave) 5'
   3. Wizzard (dave) 90' siehe [speaker notes](speaker_notes/wizzard_script.md)
      1. Drag-and-drop XTF, ILI, XML - Durchklicken und zeigen, dass QGIS-Projekt unbrauchbar ist
      2. Nochmal von vorne nur mit XTF
         1. Models von Repos
      3. Advanced Options
         1. Optionen
         2. TOML-File (romedi)
            1. Multipolygon
            2. Multilanguage
      4. Smart Inheritance
      5. Katalog automatisch mit ilidata.xml und Demo UsabILIty Hub
      6. Datenimport / Basket Handling
(Pause)
   4. Daten erfassen inkl. Basket (romedi) 10'
      1. Link Child
      2. Fehler erfassen
   5. Daten Export mit Fehler (romedi) 5'
   6. Validierung in QGIS (romedi) 5'
   7. Daten Export mit richtigen Daten (romedi) 5'
   8. Konzept und Erstellung Projekt mit UsabILIty Hub > Ausblick dass Export kommt (romedi) 15'
3.  Diskussion, Inputs, Verbesserungsvorschläge (romedi, dave) 20'
