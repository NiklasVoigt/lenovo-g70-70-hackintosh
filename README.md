# Lenovo G70-70 Hackintosh
My hackintosh project with Lenovo G70-70 (macOS Mojave 10.14.6)

**Configuration:**
Lenovo G70-70 · i3 4005U · HD4400 · 8GB · 512GB SSD

------------



**My Forum Posts:**  
https://www.hackintosh-forum.de/forum/thread/24361-lenovo-g70-70-macos-high-sierra/

https://www.hackintosh-inc.de/index.php/Thread/1592-Lenovo-G70-70-i3-4005U-mit-HD4400-GPU-Zeitverschwendung/

------------



**Installation:**
· macOS Install/Clover Stick  
· Clover Bootloader  
· KextUtility  
· Mein Clover Bootpack (Auf Dell DW1560 angepasste config.plist)  
· Für DualBoot mit Windows 2 Partitionen erstellen (einmal FAT und einmal OSX Journaled) mit GUID Partitions Tabelle  



**Working:**  
+Clover Installation/Boot  
+Mac OS X 10.11.2 El Capitan  
+Dualboot mit Windows 10 Pro  
+DSDT  
+SSDT  
+Grafik Intel HD4400 1600x900  
+Brightness (Keys müssen nur noch angepasst werden)  
+Battery Management  
+USB 2.0 ports  
+USB 3.0 port (3.0 mode)  
+EasyCamera/Microphone  
+HDMI  
+VGA  
+Dolby Audio (AppleHDA.kext mit neuester KextUtility Version installieren)  
+ELAN Trackpad (Einstellungen - Trackpad - Bedienung des Trackpads -> Regler einmal bewegen damit Scrollen funktioniert)  
+Keyboard (Einstellungen - Tastatur - Sondertasten -> Wahltaste und Befehlstaste tauschen)  
+LAN  
+WLAN (Dell DW1560 + modified BIOS/UEFI)  
+Bluetooth (Dell DW1560 + modified BIOS/UEFI)  
-Sleep  

**Not Working & Known Issues:**  
-HDMI Audio  
-SD Card Reader  

**Modified BIOS:**  
Das auf advanced freigeschaltete (modified) Bios wird benötigt um die bekanntliche Hardware Whitelist die bei Lenovo Laptops vorhanden ist auszuhebeln.
Somit ist in unserem Lenovo G70-70 jede beliebige NGFF M.2 (WLAN/BT Kombi) Karte einsetzbar !  

Der hier beschriebene Vorgang geht auf eigene Gefahr!
1. Backup mit Universal BIOS Backup ToolKit 2.0.exe
2. BIOS Backup (LENOVO-B6CN09WW.rom) hochladen
3. Request in den G70-70 Thread posten
4. Nachdem ein User das BIOS modifiziert hat die zip herunterladen
5. Windows booten und mit dem Sleep Bug flashen
6. Fertig ! Don't touch Video Settings or Disable Video Card It will Brick laptop !!!
