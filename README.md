# M159
Instruktionen zum Modul 159 (Directory Services)

1 Ablauf des Moduls

Der genaue Ablauf des Modules ist im Dokument «Modultagebuch.docx» chronologisch festgehalten. Sie müssen diesen Inhalt nicht auswendig kennen, dieses Dokument dient vor allem für die Lehrperson. Einen Blick dürfen Sie dennoch gerne hineinwerfen. Das Dokument ist in zehn Tage à 4 Lektionen aufgeteilt, wobei die letzten zwei Tage für Abnahme Ihres Portfolios reserviert sind.



2 Virtuelle Umgebung

Für eine erfolgreiche Durchführung des Modul 159 Directory Services konfigurieren und in Betrieb nehmen, brauchen Sie zwei virtuelle Windows 2019 Server Standard Desktop Maschinen und eine virtuelle Windows 2019 Server Standard Core Maschine, sowie zwei virtuelle Windows 10 Pro/Edu Clients. Informieren Sie sich selber über die Minimalanforderungen.
https://docs.microsoft.com/en-us/windows-server/get-started-19/sys-reqs-19

Für einen virtuellen Router(MikroTik) benötigen Sie lediglich 128MB Ram und 30MB Harddisk.

Falls Sie zu wenig Festplattenspeicher besitzen (ca. 250GB), müssen Sie eine externe SSD organisieren. Bitte beachten Sie, dass eine normale externe Harddisk mit grosser Wahrscheinlichkeit zu langsam ist. Für die Performance Ihrer virtuellen Umgebung sind Sie selbst verantwortlich. Eine zu schwache Umgebung, kann Einfluss auf Ihre Arbeit und somit Note haben.
Es gibt auch die Möglichkeit im Betrieb oder Zuhause eine virtuelle Umgebung auf einem Server einzurichten und mit RDP von der Schule aus darauf zuzugreifen. Diese Variante empfehle ich den Schülern mit schlechtem Notebook. 

3 Portfolio

Der Unterricht ist so aufgebaut, dass es meistens in der ersten und manchmal auch während der zweiten Lektion theoretische Inputs zum Modulinhalt geben wird. 
Anschliessend arbeiten Sie an und mit Ihrer virtuellen Umgebung. 
Die ganze Planung sowie die Dokumentation der virtuellen Umgebung, muss in einem Portfolio-Dokument festgehalten werden. 
Damit Sie wissen, was alles in diesem Dokument festgehalten werden muss, bekommen Sie die Vorlage «M159-Portfolio-Vorlage.docx» zur Verfügung gestellt. Verwenden Sie dieses Dokument für Ihr Portfolio.
Sie erhalten die Vorlage fürs Portfolio zu Beginn ausgedruckt sowie digital. Sie beginnen es, anfänglich von Hand ausfüllen. Für die Besprechung am Schluss des Moduls mit der Lehrperson, erstellen Sie eine komplette digitale Version davon, welche wiederum ausgedruckt werden muss.
Die digitale Version laden Sie auf den BSCW in den Ordner Portfolio. Erstellen Sie einen Ordner mit Ihrer Gruppe. Z.B. Gruppe 3. Schreiben Sie in die Beschreibung Ihrer Gruppe die Gruppenmitglieder hinein.


4 Gruppen

Sie dürfen einzeln oder maximal in zweien Gruppen arbeiten. 

4.1 Einzelarbeit

Für eine Einzelarbeit braucht Ihr Notebook eine gewisse Leistung, damit vier virtuelle Maschinen gleichzeitig ausgeführt werden können. Siehe Infos unter Punkt 2 «Virtuelle Umgebung».

4.2 Zweiergruppen

Wenn Sie in Zweiergruppen arbeiten, können Sie die virtuellen Maschinen auf beide Notebooks aufteilen und haben dadurch einen Performance-Vorteil. Vorgabe dafür ist jedoch, dass Ihre beiden Notebooks via physischem LAN-Kabel mit 1GB verbunden werden können. Falls Ihr Notebook keinen LAN Port besitzt, organisieren Sie einen USB->RJ45 Adapter. Achten Sie darauf, dass Sie in dieser Konstellation nur zusammenarbeiten können. Wenn Sie etwas Zuhause machen müssen, dann müssen Sie sich treffen.

5 Aufgaben

Das Aufsetzen Ihrer AD-Umgebung ist in 8 einzelne Aufgaben eingeteilt. Sie finden die Beschreibung dieser Aufgaben auf dem BSCW im Ordner Aufgaben. Jede Aufgabe erfordert unterschiedliche Ausgaben oder Exporte. Diese Resultate aus den Aufgaben werden ebenfalls im Portfolio festgehalten. Für die Outputs/Exporte finden Sie einen separaten Abschnitt im Portfolio


6 Backup

Für das Backup Ihrer virtuellen Maschinen sind Sie jederzeit selbst verantwortlich. Schauen Sie, dass Sie nach jedem Schultag ein Backup Ihrer Umgebung erstellen können. Installieren Sie allenfalls eine Virtualisierungsumgebung welche Snapshots zulässt, damit keine Arbeiten verloren gehen. 

 
7 Lernbeurteilungen (Prüfungen)

Ihre Modulnote resultiert aus zwei Lernbeurteilungen (LB1 & LB2).

7.1 LB1

Die LB1 besteht aus einer theoretischen Prüfung, welche Sie am PC im Ecolm absolvieren. Die Prüfung dauert 30 Minuten und besteht aus Single-, Multiple Choice und freien Antworten.
Themen welche an der Prüfung abgefragt werden:

Aus dem Verzeichnisdienst.pdf
•	Kapitel 13   bis und mit 13.2.4
•	Kapitel 13.4 bis und mit 13.9
•	Kapitel 14.6

Das PDF Geschichte.pdf

Alles was im Unterricht zum Thema «DNS» behandelt wurde
•	Gültige Zeichen einer Domäne
•	Forward-/ Reverse Lookup
•	Zonenfile
•	DNS Records
•	TTL
•	Top-, second-, third-level Domains
•	NSLOOKUP, DNS DIG
•	DNS Server unter Windows Server einrichten und konfigurieren
o	Zonentransfer
o	Sichere und nicht sichere Updates

Alles was im Unterricht zum Thema «Benutzerprofile» behandelt wurde
Alles was im Unterricht zum Thema «DIT» behandelt wurde
Alles was im Unterricht zum Thema «Gruppenrichtlinien» behandelt wurde

7.2 LB2

Während des ganzen Modules können Sie gelöst bwz. abgeschlossene Aufgaben von der Lehrperson kontrollieren und bestätigen lassen.
In der Datei "Bewertung-Aufgaben-LB2.xlsx" finden Sie eine Übersicht der Punkte, welche für die einzelnen Aufgaben vergeben werden können. 
Am Schluss gilt die Formel (( Erreichte Punkte / Max. Punkte x 5 ) + 1) = Note LB2 auf Zehntel gerundet.

Versuchen Sie gelöste Aufgaben so bald als möglich der Lehrperson zu zeigen. Es hat diverse Vorteile wenn Sie damit nicht bis zum Schluss warten. 


7.3 Modulnote

Modulnote = LB1 (25%) + LB2 (75%) -> Auf 0.5 gerundet
