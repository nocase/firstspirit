Hallo Freunde der gepflegten Bildaufl�sungen im FirstSpirit,

das Anlegen und �bertragen von Bildaufl�sungen ist immer wieder ein Thema im FoirstSpirit.
Ich habe heute mal hilfreiche Skripte geschrieben, welche uns das Exportieren, Importieren und �bertragen von Bildaufl�sungen erleichtern werden.
Anbei findet ihr eine ZIP mit folgendem Inhalt:
-	PowerPoint, welche Euch eigentlich die Handhabung der Skripte erkl�rt
-	Paket f�r FS f�r den Import von 2 Skripten
-	Skript f�r Auftr�ge (script_job_release_image_resolutions_to_projects.txt)
-	Beispieldatei f�r den Import von Bildaufl�sungen (import.txt)

Ich habe heute ebenfalls einige Tests damit gemacht - auch wenn nicht alle F�lle abgefangen werden, sind die Skripte f�r viele Alltagssituationen verwendbar und in Kombination m.E. sogar f�r server�bergreifenden Einsatz anwendbar (Export Server 1, Import Server 2 Master, direktes �bertragen auf Slave-Projekte auf Server 2).

Schaut Euch am besten die PowerPoint an, installiert das Paket im Projekt Eurer Wahl und los geht es!

Das Skript f�r Auftr�ge blockiert die Projekte (�ffnen der Projektkonfiguration in Admin-Konsole), wenn bestimmte Exceptions fliegen. Leider kann ich das ExceptionHandling nicht ausgereift liefern�
Falls der Fall also eintritt, muss wohl der Server neu gestartet werden. Vielleicht habt ihr eine L�sung�
Die Skripte funktionieren aber im Normaleinsatz aber stabil und blockieren nichts.


Viele Gr��e,
Matthias

