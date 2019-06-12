# Poolfiltersteuerung
ioBroker Blockly Poolfilter Steuerung



# Funktionen:

*Alle Datenpunkte können automatisch erzeugt werden, einfach den Block über den Variablen-Stamm aktivieren und das Script neu Starten.

*Es gibt zwei Einschaltzeiten (00:00-23:59) sowie zwei Laufzeiten (60) in Minuten die frei wählbar sind.

*Wird die Filterpumpe per Hand eingeschalten nicht durch das Script schaltet die Pumpe nach 60min aus, diese Zeit kann auch geändert werden.

*Es gibt eine Handeinschalt Funktion die die Pumpe einschaltet aber nicht mehr ausschaltet es wird nur stündlich gemeldet das die Pumpe x Stunden an ist.

*Eine Zeitauswahl die die Pumpe für x Minuten (auswählbar) einschaltet und danach wieder ausschaltet.



# To-Do-List

*Erweiterung für pH und Chlor Dosierung



# Blockly Importieren

Unter Scripts erstellt ihr euch ein neues Blockly Script und öffnet dieses, oben rechts gibt es mehrere Icons klickt nun auf das zweite Icon "Blöcke importieren" fügt dort das Script ein und Importiert die Blöcke.

Links oben im script befinden sich die OB-Variablen diese müssen angepasst werde. Man kann auch die Objekte automatisch erzeugen lassen, dafür den deaktivierten Block aktivieren und das Script ein mal starten. Danach sind die Objekte unter Objekte -> javascript.0.Pool zu finden.
