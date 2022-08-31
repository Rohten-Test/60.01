ISO:
Abbild einer CD/DVD im ISO Format.
Internation Standard Organisation ISO-9660

Mount:
Einbindung eines Massenspeichers oder Datenträgers in einem Laufwerk.

Scheduling:
Mit Scheduling wird der zeitliche Befehlsablauf beschrieben.

bits in byte:
8 bits = 1 byte

Taktfrequenz:
Wird in Hz angegeben. 1Hz bedeutet 1 mal pro sek. 1Mhz = 1.000.000 mal pro sek.

Entscheidungskriterien für den kauf eines Druckers.
 - Privat oder gewerblich?
 - Druckgeschwindigkeit
 - Strom verbrauch
 - Papierformat
 
Partition:
Bei MBR partitionsschema entweder 4 Primäre oder 3 Primäre und 1 erweiterte Partion möglich. Bis maximal 2TiB
ich zitiere Steve: in einer erweiterten Partion kann man beliebig viele Logische Partionen erstellen. 
MBR nutzt BIOS und kann nicht UEFI
MBR speichert information in den ersten Sektor mit logischen block adresse (LBA) 1.
Diese beinhaltet die master partition table (MPT), den master Boot Code (MBC) und die Disk Signature.
Das Bios sucht nach der Partion mit dem MBR und führt dann den Bootcode aus.
Als nächstes aktiviert der MBR den  Bootsektor und startet das OS.

Bei GPT bis zu 128 Partitionen möglich. Bis maximal 8 ZebiB
Global Unique Identification Partition Table es benötigt UEFI
Windows früher als Win 8 nicht mit GBT bootfähig


Vor-/Nachteile von HDD - SDD
Vorteile SSD:
  - Hohe Trafsferraten und kurze Zugriffszeiten
  - Schnelleres Startenn von Programmen und Anwendungen
  - Kürzere Bootzeiten von Notebook und Desktop-PC
  - Raschere Verfügbarkeit von lokalen Daten
  - Optimal für den mobilen Einsatz in Notebooks und Netbooks
  - Keine bewegten mechanischen Komponenten
  - Völlig geräuschloser und vibrationsloser Betrieb
  - Niedriger Energieverbrauch für längere Akkulaufzeit
  - Niedrige Wärmeentwicklung, keine zusätzliche Kühlung notwendig
  - Stoßunempfindlich, funktionsfähig un jeder Einbaulage
  - Geringeres Gewicht
  
 Nachteile SSD:
  - Hoher Preis
  - Begrenzte Kapazität
  - Kürzere Lebensdauer bei häufigen Schreibvorgänge
  
Von Neumann:
Grundlegendes Blockschaltbild eines Computers:
![1_1](https://user-images.githubusercontent.com/109280187/187205133-b80d25b7-1622-41d7-a09b-8279ca45901b.PNG)

Achitektur des Von-Neumann-Rechners:
![2_2](https://user-images.githubusercontent.com/109280187/187205220-ea6df6e1-91df-4e77-88ab-0737ab40a482.PNG)


EVA:
Eingabe - Verarbeitung - Ausgabe

Bauteile:
  - Gehäuse
  - Festplatte
  - Netzteil
  - Mainboard
  - CPU
  - Grafikkarte
  - Arbeitsspeicher
  - Lüfter
  - Laufwerke (CD / DVD /Blueray / Diskette)
  - Kartenlesegerät
  - Soundkarte
  - WLAN Karte
 
 Umwandlung von Dezimalzahlen in Dualzahlen:
 Division:
 ![1_3](https://user-images.githubusercontent.com/109280187/187207208-249d05f2-1862-4100-8b87-f411f085b7c6.PNG)
  
  Subtraktionsmethode:
  Tabelle mit den Stellenwerten anlegen
  Stellenwerte:                  2^9 | 2^8 | ... | 2^0
  Stellenwerte als Dezimalwerte: 512 | 256 | ... | 1
  
  ![1_4](https://user-images.githubusercontent.com/109280187/187207949-f2d9517f-9de7-413a-85b7-323252fb5952.PNG)

  (!) Binärzahlen von rechts nach links schreiben (!)
  
  Netzwerke:
  
  	- Standart-Subnet-mask: 255.255.255.0
	- Domänennamen werden über ein DNS in Adressen (IPv4/IPv6) umgewandelt
	- Den ganzen Kladderadatsch stellt man im Netzwerkadapter ein
	- Und der ist immer aktiv sonst gibt es keine Verbindung!
	
  Windows-Versionen:
  	
	- Home für Home (höh)
	- Home ist eigentlich Kacke, weil du hast kein RDT(RDP eigentlich, aber okay) und so.
  	- Windows Enterprise für Schulen, Behörden, und größere Unternehmen
	- Windows Education für Schüler und Universitäten, Schulen
	- Windows Pro für kleine Firmen (oder prosumer)
	- Windows Pro für Workstations; hat ein robustes Dateisystem (REFS)
		-> Normale Pro hat kein robustes Dateisystem (??)
	- Windows Server für Firmen, Pornoseitenhoster, das Krankenhaus in Meerheim hat Faruk festgestellt 
	  (deshalb funktioniert da auch gar nix).
		-> Die hosten sogar ihre Website über Windows Server
		
	
	-> Es ist Windows, also.
	
	Quelle: Faruk.
	
  Sysprep:
  	
	- Ein Hilfsprogramm von Microsoft für die Ersteinrichtung (bzw. Image-Erstellung)
		-> Im Audit-Modus können Benutzerkonten voreingestellt werden, Bloatware (de-)installiert werden,
		   und diverse Einstellungen am Computer vorgenommen werden.
		-> Anschließend können hardwarebezogene Informationen aus dem Image entfernt werden und der sogenannte OOB
		   (Out of Box-Experience) Modus aktiviert werden, damit Nutzer eine vereinfachte Ersteinrichtung haben.
		
  Ein-/Ausgabegeräte:
  
  	- Joa ein/ausgabegeräte
	- Beispiele für Eingabegeräte:
		- Tastatur
		- Maus
		- Joystick
		- Mikrofon
		- Controller
		- Kamera
		- Scanner 
		- Barcodescanner
		- Touchpad
		- Eitracker
		- Trackballs
		- Fingerabdrucksensor
		- Iris-Scanner
		- USB-Waagen???
		
	- Beispiele für Ausgabegeräte:
		- Monitor
		- Lautsprecher
		- A4-Drucker
		- Wie wär's mit halt dein Maul?
		- Plotter
		- Beamer
		- *Ping*
		- USB-Ventilatoren
		- Ralf seine Heizung
		- Rauschen auf dem Mikrofon
		- 3D-Drucker
		- Laut den Folien von Jim VR-Brillen
		
	VR-Brillen machen keinen Sinn (Quelle: Ich glaube Gian-Marc oder so)
		
  HDD-Sektorengröße zu GB/Gib/Gb:
  
  	- 512 bit oder 4096 bit -> ein Sektor
	
	- Formel für Speicherplatz:
	
	  Sektorengröße * Anzahl Sektoren / ((1000 (GB) oder 1024 (Gib)) * 3 )
	

