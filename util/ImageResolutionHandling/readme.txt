Hallo Freunde der gepflegten Bildauflösungen im FirstSpirit,

das Anlegen und Übertragen von Bildauflösungen ist immer wieder ein Thema im FoirstSpirit.
Ich habe heute mal hilfreiche Skripte geschrieben, welche uns das Exportieren, Importieren und Übertragen von Bildauflösungen erleichtern werden.
Anbei findet ihr eine ZIP mit folgendem Inhalt:
-	PowerPoint, welche Euch eigentlich die Handhabung der Skripte erklärt
-	Paket für FS für den Import von 2 Skripten
-	Skript für Aufträge (script_job_release_image_resolutions_to_projects.txt)
-	Beispieldatei für den Import von Bildauflösungen (import.txt)

Ich habe heute ebenfalls einige Tests damit gemacht - auch wenn nicht alle Fälle abgefangen werden, sind die Skripte für viele Alltagssituationen verwendbar und in Kombination m.E. sogar für serverübergreifenden Einsatz anwendbar (Export Server 1, Import Server 2 Master, direktes Übertragen auf Slave-Projekte auf Server 2).

Schaut Euch am besten die PowerPoint an, installiert das Paket im Projekt Eurer Wahl und los geht es!

Das Skript für Aufträge blockiert die Projekte (Öffnen der Projektkonfiguration in Admin-Konsole), wenn bestimmte Exceptions fliegen. Leider kann ich das ExceptionHandling nicht ausgereift liefern…
Falls der Fall also eintritt, muss wohl der Server neu gestartet werden. Vielleicht habt ihr eine Lösung…
Die Skripte funktionieren aber im Normaleinsatz aber stabil und blockieren nichts.


Viele Grüße,
Matthias

