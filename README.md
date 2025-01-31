# Netzwerk_Dokumentation

**IP-Adressen:** 192.168.1.1 - 192.168.1.254
**Subnetz:** 255.255.255.0
**Gateway:** 192.168.1.1

### Geräte
- **192.168.1.1**: Router
- **192.168.1.3**: Switch
- **192.168.1.6**: Windows AD
- **192.168.1.10**: Linux Server
- **192.168.1.xxx**: WS-xxx

## Switch Einrichtung
1. **Switch resetten:** Mit einer Büroklammer den Reset-Knopf drücken und 10 Sekunden warten.  
2. **IP & Subnetz anpassen:** Die IP-Adresse und das Subnetz deines PCs ändern, um im gleichen Subnetz wie der Switch zu sein (IP des Switches steht auf der Rückseite).  
3. **Benutzeroberfläche aufrufen:** Die IP des Switches im Browser eingeben, dann unten rechts klicken und das Passwort eingeben (steht auf der Rückseite). Anschließend das Passwort ändern, z. B. auf "Zli12345".  
4. **IP & Name des Switches ändern:** Nach dem Login kann die IP-Adresse und der Name des Switches geändert werden.  
5. **Eigene IP-Adresse wieder anpassen:** Nach der Änderung der Switch-IP muss die eigene IP wieder angepasst werden, um im gleichen Subnetz zu sein.  
6. **Einstellungen übernehmen:** Immer auf "Übernehmen" klicken, um die Änderungen zu bestätigen!

### Betriebssystem Installieren
- Betriebssystem überschreiben-Um ein anderes Betriebssystem auf einem PC zu laufen, muss man das alte überschreiben. Das macht man, indem man auf dem Browser rufus sucht und dann die Version „rufus-4.6“ herunterlädt und laufen lässt. Nachher muss man das Laufwerk, am besten ein USB-Stick, auswählen, wie auch das gewünschte ISO-Image. Nachher muss man nur noch den Stick in den anderen PC machen und richtig booten.
- ![image](https://github.com/user-attachments/assets/a852f25d-3854-4010-9b57-5fefefdee54b)

### FTP Installieren
- Zum Installieren vom FTP muss man nur "sudo apt update" und "sudo apt install vsftpd -y" in das Terminal schreiben und bei den Clients schauen ob es funktioniert.

### Wo wir Probleme hatten
- Wir hatten sehr schlimme Probleme mit dem Linux-Server. Wir konnten am anfang das Betriebsystem nicht richtig überschreiben. Bei dem AD hatten wir auch Probleme, wir wussten nicht ganz genau was wir am anfang machen mussten daher haben wir auch sehr viel zeit verloren. Bevor Stevan wieder gekommen ist hatten wir Probleme mit dem konfigurieren vom Router.
### Fazit Stevan Medic
- Das Konfigurieren des Switches und des Routers hat mir sehr gefallen, da ich dabei mein Wissen über Netzwerktechnik vertiefen konnte. Besonders spannend fand ich das Einrichten der verschiedenen Einstellungen und das Testen der Verbindung. Solche praktischen Arbeiten machen mir sehr Spass, da ich gerne an technischen Systemen arbeite und dabei direkt die Auswirkungen meiner Konfigurationen sehe.

### Fazit Aaron Benesch
- Ich fand den heutigen Tag interessant, vor allem weil man gesehen hat, was einem noch geblieben ist und das man alles noch einmal repetiert hat. Wir sind nicht sehr weit gekommen, weil wir am Morgen nur zu zweit waren und einige Probleme hatten. Ich habe hauptsächlich an dem Windows Server, an den Windows und Linux Clients und an dem Überschreiben von den alten Betriebssystemen. Wir hatten bei dem Linux Server die meisten Probleme, da wir das alte Betriebssystem nicht richtig überschreiben hatte, da wir beide es vergessen haben zu machen.

### Fazit Joris Brunold
- Ich habe diese Arbeit spannend gefunden, doch leider kamen wir nicht so schnell vorwärts, wie wir gehofft haben. Vor allem beim Linux Server hatten wir länger gebraucht als ich erwartet habe. Leider hatten wir Probleme beim Überschreiben des Betriebssystems und brauchten dadurch um einiges länger dafür. Das Konfigurieren des Windows Servers lief dafür perfekt und schnell. Das Installieren des FTP-Servers konnte ich ohne Probleme machen. Beim active directory brauchten wir auch etwas länger doch als wir einigermassen wussten was zu tun war konnten wir wieder besser arbeiten. Trotzdem habe ich heute so einiges repetieren können, dazu gehöhrten Linux, konfigurieren des Switch und Routers und FTP.
