# OpenSimulator Statistik Informationen

Edit OpenSim.ini und füge folgendes ein:

     ; Simulator Stats URI
     ; Enable JSON simulator data by setting a URI name (case sensitive)
     Stats_URI = "jsonSimStats"
   
Suche und editiere diese Skript und ändere die Zeilen:
   
     adress = "http://yourhome.net_or_IP:yourPORT";
     time = millisecond; 3000 kann höher eingestellt werden dann ist die last auf dem Server nicht so hoch.


Die einfachste Art die Statistik in euerem OpenSimulator einzufügen ist die Datei in http_404.html umzubenennen und direkt in das /bin Verzeichnis zu kopieren. 

![Title](http://virtual-talk.de/attachment.php?aid=5163)
