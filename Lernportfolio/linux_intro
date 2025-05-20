# Die Linux Verzeichnishierarchie

Linux kommt, im Gegensatz zu Windows nicht mit verschiedenen Datenträgern (C:/, D:/ usw.) daher, sondern ist in viele Ordner und Unterordner strukturiert. Der Linux-Verzeichnisbaum ist dabei keineswegs willkürlich gewählt, sondern bietet eine durchdachte Struktur. Jedoch sind die Namen der Ordner nicht wirklich sprechend, da sie häufig (in der Softwareentwicklung übliche) Abkürzungen verwenden. Daher wird im Folgenden die Bedeutungen der Hauptverzeichnisse und die wichtigsten Unterverzeichnisse, die es z.B. unter Debian gibt, erläutert.


-   Der Verzeichnisbaum beginnt bei Linux beim Verzeichnis `/`
    (Vergleichbar mit `C:\` unter Windows)

-   Das Verzeichnis `/`wird auch Wurzel- oder Rootverzeichnis genannt

-   Verzeichnisse eine oder mehrere Hierarchiestufen weiter unten werden
    durch `/`-Zeichen getrennt

-   Beispiele:

        /etc/
        /usr/local/nginx
        /usr/bin/
        /home/user1



## Wichtige Verzeichnisse      

		/
Das Wurzelverzeichnis oder Stammverzeichnis genannte Verzeichnis ist die höchste Ebene der Verzeichnisstruktur. In diesem befinden sich alle Verzeichnisstrukturen des Betriebssystems einschließlich weiterer Speichermedien.

		/bin  :: binaries (dt. Binärdateien/Programme)
Die wichtigsten Kommandos (Programme) die von Betriebssystem gebraucht werden wie cp, echo, `mkdir` oder `rm` befinden sich in diesem Verzeichnis. Sie haben alle gemeinsam, dass sie Binärdateien sind und von allen Benutzern ausgeführt werden dürfen. (/sbin nur fürs System/root).


		/dev :: devices (dt. Geräte)
Hier befinden sich Gerätedateien zur Ansteuerung von Hardware wie Festplatten, RAM, Bildschirm oder auch der Maus. Die Dateien stellen die Existenz der Treiber eines Gerätes dar und können auch leere Dateihülsen sein. Andere bieten konkrete Funktionalität an. Für jedes Hardwareteil gibt es vorsorglich einen solchen Eintrittspunkt, auch wenn dieser nicht zwingend benötigt wird.

		/etc ::  et cetera (dt. „alles übrige“), auch edit to configure
Dieser Ordner beinhaltet die meisten systemweit gültigen **Konfigurationsdateien** und stellt damit den zentralen Anlaufpunkt zum Verändern von Einstellungen dar.

		/home     
In diesem Verzeichnis befinden sich standardmäßig die Heimatverzeichnisse der Nutzer. In diesen Ordnern können Benutzer ihre persönlichen Dateien und je nach Anwendung auch benutzerspezifische Konfigurationen ablegen. In Ihrem System ist Ihr Homeverzeichnis zu finden unter `/home/meinusername`.

		~   :: tilde oder "Schlange"
	
		/home/meinusername
Das Tilde-Zeichen `~` kennzeichnet Ihr **Homeverzeichnis** und ist dasselbe wie `/home/meinusername`.

Hier legen Sie Ihre Dateien ab, die Sie bearbeiten. Erste Übungen können Sie auch hier machen.

		/lib :: libraries (dt. Bibliotheken)
Hier sind Funktionsbibliotheken des Systems wieder zu finden. Dies sind Bibliotheken, die bei dem Systemstart benötigt werden und, wenn der Kernel modular aufgebaut ist, die entsprechenden Kernel-Module.

		/opt :: optional
Hier werden alle Programme abgelegt, die nicht im Paketformat vorliegen (folglich händisch installiert und nicht durch Paketmanager verwaltet), wie auch viele kommerzielle Softwarepakete.

		/run    
Dieser Ordner beherbergt Dateien von laufenden Prozessen. In diesem Ordner finden sich die meisten PID-Files (Process identifier).

		/sbin  :: system binaries (dt. Systemprogramme)
In diesem Ordner findet man Programm Binärdateien wieder, die Root-Rechte zum Ausführen benötigen.

		/tmp ::  temporary (temporär)
In diesem Verzeichnis können temporäre Daten abgelegt werden. Zu beachten ist, dass dieses Verzeichnis nach einem Neustart in der Regel bereinigt wird.

		/usr  ::   unix system resources (dt. UNIX Systemressourcen, NICHT USER)
Programme die nicht direkt für das Betriebssytem gebraucht werden, sondern eher für die Benutzer, sind in diesem Ordner zu finden. Dabei enthält dieser Ordner weitere Unterordner, die sich thematisch gliedern.

		/usr/local     
Als wichtiges Unterverzeichnis von /usr ist dieses Verzeichnis zu nennen. In diesem können Benutzer ihre eigenen Programme installieren. Das Verzeichnis ist wie /usr thematisch in Unterordner unterteilt.

		/var  ::   variable (dt. variabel)
In diesem Ordner sind variable Daten wie Logfiles, Mails oder auch Druckerspooler verortet. 

		/var/www/html :: Web-Server Dateien
Dieser Ordner ist nicht standardmäßig in der Debian Distribution angelegt, sollte aber dennoch Erwähnung finden. Er gilt als Standardordner für die Inhalte eines Webservers (z.B. Apache2 für PHP Scripts und Co.).


