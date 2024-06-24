# Lösung zu BILDER_CODIEREN AUFGABEN

### 1. Bestimme die Farben:

- RGB(255, 255, 255) entspricht Farbe: Weiss
- RGB(0,0,0) entspricht Farbe: Schwarz
- RGB(252,178,91) entspricht Farbe: Safrangelb
- #FF0000 entspricht Farbe: Rot
- #00FF00 entspricht Farbe: Grün
- #0000FF entspricht Farbe: Blau
- #FFFF00 entspricht Farbe: Gelb
- #00FFFF entspricht Farbe: Cyan
- #FF00FF entspricht Farbe: Magenta
- #000000 entspricht Farbe: Schwarz
- #FFFFFF entspricht Farbe: Weiss
- #00BC00 entspricht Farbe: Dunkelgrün

### 2. Bestimmen sie die Farben für die folgenden prozentualen CMYK-Angaben

- C:0%, M:100%, Y:100%, K:0% entspricht Farbe: Rot
- C:100%, M:0%, Y:100%, K:0% entspricht Farbe: Grün
- C:100%, M:100%, Y:0%, K:0% entspricht Farbe: Blau
- C:0%, M:0%, Y:100%, K:0% entspricht Farbe: Gelb
- C:100%, M:0%, Y:0%, K:0% entspricht Farbe: Cyan
- C:0%, M:100%, Y:0%, K:0% entspricht Farbe: Magenta
- C:100%, M:100%, Y:100%, K:0% entspricht Farbe: Schwarz
- C:0%, M:0%, Y:0%, K:100% entspricht Farbe: Schwarz
- C:0%, M:0%, Y:0%, K:0% entspricht Farbe: Weiss
- C:0%, M:46%, Y:38%, K:22% entspricht Farbe: Dunkelrosa

### 3. Berechnen sie den theoretischen Speicherbedarf in Bit und in Byte eines unkomprimierten RGB-Bildes mit der Grösse 640 x 480 und 8Bit Auflösung pro Farbkanal.

- **Bildgröße (Pixel):** 640 x 480 = 307200 Pixel
- **Speicherbedarf pro Pixel:** 8 Bit pro Farbkanal × 3 (RGB) = 24 Bit pro Pixel
- **Gesamtspeicherbedarf in Bit:** 307200 Pixel × 24 Bit pro Pixel = 7372800 Bit
- **Gesamtspeicherbedarf in Byte:** 7372800 Bit / 8 = 921600 Byte

### 4. Webseitengestaltung

Die empfohlenen Bildformate sind JPG für den Hintergrund und SVG oder PNG für das Logo.

### 5. Was ist die Pixelauflösung horizontal und vertikal?

- Horizontale Auflösung: 2546 Pixel
- Vertikale Auflösung: 1591 Pixel

### 6. Sie drucken ein quadratisches Foto mit einer Kantenlänge von 2000 Pixel mit 600dpi. Wie groß in cm wird dieses?

Größe in cm: 2000 Pixel / 600 dpi = 3.33 Zoll = 8.47 cm

### 7. Berechnen sie den Speicherbedarf für ein unkomprimiertes Einzelbild im HD1080p50-Format bei einer True-Color-Farbauflösung.

- **Anzahl der Pixel:** 1920 × 1080 = 2.073.600 Pixel
- **Speicherbedarf pro Pixel:** 24 Bit / Pixel = 3 Byte / Pixel
- **Gesamtspeicherbedarf für ein Bild:** 2.073.600 Pixel × 3 Byte/Pixel = 6.220.800 Byte = 49.766.400 Bit

### 8. Welchen Speicherbedarf hat das Video aus der vorangegangenen Aufgabe bei einer Spieldauer von 3 Minuten in GB?

- Berechneter Speicherbedarf: 52.14 GiB

### 9. Unterschiede zwischen RAW und JPEG?

**RAW:**
- Speichert alle Bildinformationen
- Größerer Speicherbedarf
- Für professionelle Fotografie und Nachbearbeitung

**JPEG:**
- Verwendet verlustbehaftete Kompression
- Kleinere Dateigröße
- Geeignet für den Alltagsgebrauch

### 10. Technische Vorgaben für YouTube-Uploads

- **Container:** MP4
- **Bildrate:** 24, 25, 30, 48, 50, 60 fps
- **Farbauflösung:** 4:2:0
- **Videocodec:** H.264
- **Audiocodec:** AAC-LC
- **Maximale Bitrate:**
  - 1080p: 8 Mbps (SDR), 10-12 Mbps (HDR)
- **Urheberrechtliche Einschränkungen:** Urheberrechtlich geschützte Inhalte dürfen nicht ohne Genehmigung verwendet werden.

### 11. Unterschied zwischen Interlaced Mode und Progressive Mode?

- **Interlaced:** Halbbilder (ungerade Zeilen, gerade Zeilen)
- **Progressive:** Vollständige Bilder

### 12. Was sind Artefakte und kennen Sie Beispiele?

Artefakte sind Störungen oder Verzerrungen in einem Bild oder Video aufgrund von Komprimierung oder anderen Faktoren. Beispiele sind Moiré-Effekte und Blocking-Artefakte.

### 13. Datenrate für HD1080i50 Video?

- 1.24416 Gbps

### 14. Nach wie vielen Minuten wäre eine DVD-5 (Single-Layer DVD mit 4.7GB) voll mit unkomprimiertem HD1080i50 Video?

- Nach 30 Sekunden (0.5 Minuten)

### 15. Unterschied zwischen Codec und Mediencontainer?

- **Codec:** Komprimiert und dekomprimiert Audio- und Videodaten.
- **Mediencontainer:** Enthält verschiedene Datenströme (Video, Audio, Untertitel) in einer Datei.

### 16. Fragen zum AD-Wandler-Video

- **a. Warum benötigt man AD-Wandler?**
  Um analoge Signale in digitale umzuwandeln, damit sie von Computern verarbeitet werden können.

- **b. Warum geht eine A/D-Wandlung immer mit einem Datenverlust einher?**
  Durch Diskretisierung und Quantisierung gehen Details des analogen Signals verloren.

- **c. Gibt eine höhere oder niedrigere Samplingrate eine präzisere Abbildung des Originals? Begründen Sie!**
  Eine höhere Samplingrate bietet eine präzisere Abbildung, da mehr Datenpunkte pro Sekunde erfasst werden und somit feinere Details wiedergegeben werden können.
