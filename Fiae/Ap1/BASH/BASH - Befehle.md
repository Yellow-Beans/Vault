ls -> List Storage, zeigt vorhandene Dateien und Ordner an
- \-a zeigt alle, auch versteckte Dateien an
- \-l zeigt eine detailliertere Ansicht

pwd -> print working directory, zeigt an wo wir uns befinden

cd -> change directory, ordner wechseln
cd alleine führt in das Home-Verzeichnis
cd . <- der Punkt repräsentiert den derzeitigen Ordner
cd .. <- der 2. Punkt steht für den übergeordneten Ordner
cd ~ <- Die Tilde repräsentiert das Home-Verzeichnis
![[Pasted image 20250329123410.png]]
sudo -> Superuser do, ausführen mit erweiterten Berechtigungen
sudo usermod -aG sudo username 
-> fügt den Benutzer 'username' der sudoers Gruppe hinzu 
\- aG a steht für append, G für Group(s). Der Nutzer wird also **zusätzlich** der angegebenen Gruppe(n) hinzugefügt. 

touch some_file.txt 
-> legt die Datei an, falls sie nicht existiert. Erneuert den Zeitstempel der letzten Änderung, falls sie existiert. 

echo 'bla' >> some file.txt 
-> hängt "bla" ans Ende der Datei an

echo 'bla' > some file.txt 
-> ersetzt den Dateiinhalt mit 'bla'

cat 
-> anzeigen einer oder mehrerer Dateiinhalte

man 
-> liefert ein Manual zu befehlen

nano 
-> startet einen simple texteditor

![[Pasted image 20250329125605.png]]


