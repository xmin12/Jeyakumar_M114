# Lösung zu BILDER_CODIEREN AUFGABEN

### 1. Bestimme die Farben

- **RGB(255, 255, 255)** entspricht Farbe: **Weiß**
- **RGB(0,0,0)** entspricht Farbe: **Schwarz**
- **RGB(252,178,91)** entspricht Farbe: **Safrangelb**
- **#FF0000** entspricht Farbe: **Rot**
- **#00FF00** entspricht Farbe: **Grün**
- **#0000FF** entspricht Farbe: **Blau**
- **#FFFF00** entspricht Farbe: **Gelb**
- **#00FFFF** entspricht Farbe: **Cyan**
- **#FF00FF** entspricht Farbe: **Magenta**
- **#000000** entspricht Farbe: **Schwarz**
- **#FFFFFF** entspricht Farbe: **Weiß**
- **#00BC00** entspricht Farbe: **Dunkelgrün**

### 2. Bestimmen Sie die Farben für die folgenden prozentualen CMYK-Angaben

- **C:0%, M:100%, Y:100%, K:0%** entspricht Farbe: **Rot**
- **C:100%, M:0%, Y:100%, K:0%** entspricht Farbe: **Grün**
- **C:100%, M:100%, Y:0%, K:0%** entspricht Farbe: **Blau**
- **C:0%, M:0%, Y:100%, K:0%** entspricht Farbe: **Gelb**
- **C:100%, M:0%, Y:0%, K:0%** entspricht Farbe: **Cyan**
- **C:0%, M:100%, Y:0%, K:0%** entspricht Farbe: **Magenta**
- **C:100%, M:100%, Y:100%, K:0%** entspricht Farbe: **Schwarz**
- **C:0%, M:0%, Y:0%, K:100%** entspricht Farbe: **Schwarz**
- **C:0%, M:0%, Y:0%, K:0%** entspricht Farbe: **Weiß**
- **C:0%, M:46%, Y:38%, K:22%** entspricht Farbe: **Dunkelrosa**

### 3. Berechnen Sie den theoretischen Speicherbedarf in Bit und in Byte eines unkomprimierten RGB-Bildes mit der Größe 640 x 480 und 8 Bit Auflösung pro Farbkanal

Um den Speicherbedarf eines unkomprimierten RGB-Bildes zu berechnen, benötigen wir die Bildgröße, die Anzahl der Farbkanäle und die Auflösung pro Farbkanal.

- **Bildgröße (Pixel):** 640 x 480 = 307.200 Pixel
- **Speicherbedarf pro Pixel:** 8 Bit × 3 = 24 Bit pro Pixel (Ein Pixel besteht aus drei Farbkanälen (RGB) und jeder Kanal hat eine Auflösung von 8 Bit)
- **Gesamtspeicherbedarf in Bit:** 307.200 Pixel × 24 Bit / Pixel = 7.372.800 Bit
- **Gesamtspeicherbedarf in Byte:** 7.372.800 Bit / 8 = 921.600 Byte

### 4. Webseitengestaltung

Die empfohlenen Bildformate sind **JPG** für den Hintergrund und **SVG** oder **PNG** für das Logo.

### 5. Was ist die Pixelauflösung horizontal und vertikal?

- **Horizontale Auflösung:** 2.546 Pixel
- **Vertikale Auflösung:** 1.591 Pixel

### 6. Sie drucken ein quadratisches Foto mit einer Kantenlänge von 2000 Pixel mit 600 dpi. Wie groß in cm wird dieses?

**Größe in Zoll:** Anzahl der Pixel / DPI

2000 / 600 = 3,33 Zoll ≈ 8,47 cm

### 7. Berechnen Sie den Speicherbedarf für ein unkomprimiertes Einzelbild im HD1080p50-Format bei einer True-Color-Farbauflösung

- **Anzahl der Pixel:** 1920 × 1080 = 2.073.600 Pixel
- **Speicherbedarf pro Pixel:** 24 Bit / Pixel = 3 Byte / Pixel
- **Gesamtspeicherbedarf für ein Bild:** 2.073.600 Pixel × 3 Byte / Pixel = 6.220.800 Byte

6.220.800 Byte = 6.220.800 × 8 Bit = 49.766.400 Bit

### 8. Welchen Speicherbedarf hat das Video aus der vorangegangenen Aufgabe bei einer Spieldauer von 3 Minuten?

Speicherbedarf: **52,14 GiB**

### 9. Ihre Digitalkamera bietet für die Speicherung ihrer Bilder die beiden Formate RAW und JPG an. Wo liegen die Unterschiede und was sind die Verwendungszwecke?

**RAW:**

- Speichert alle Bildinformationen, die vom Sensor erfasst werden
- Mehr Speicherbedarf
- Verwendungszweck: Professionelle Fotografie, Nachbearbeitung

**JPEG:**

- Verwendet verlustbehaftete Kompression
- Weniger Speicherbedarf
- Verwendungszweck: Alltag, schnelle Speicherung und Verteilung

### 10. Technische Vorgaben für YouTube-Uploads

- **Container:** MP4
- **Bildrate:** 24, 25, 30, 48, 50, 60 fps (Frames per Second)
- **Farbauflösung:** 4:2:0
- **Videocodec:** H.264
- **Audiocodec:** AAC-LC
- **Maximale Bitrate:** 
  - 1080p: 8 Mbps für SDR, 10-12 Mbps für HDR
- **Rechtliche Einschränkungen:**
  Urheberrechtlich geschützte Inhalte dürfen nicht ohne Genehmigung verwendet werden.

### 11. Was ist der Unterschied zwischen dem Interlaced Mode und dem Progressive Mode?

- **Interlaced:** Halbbilder (es werden abwechselnd ungerade und gerade Zeilen angezeigt)
- **Progressiv:** Ganze Bilder (alle Zeilen werden gleichzeitig angezeigt)

### 12. Was versteht man unter Artefakten und welche kennen Sie?

Artefakte sind unerwünschte Strukturen oder Fehler in Bildern, die durch Komprimierungen entstehen. Bekannte Artefakte sind der **Moiré-Effekt** und **Blockingartefakte**.

### 13. Datenrate für HD1080i50 Video

1,24416 Gbps

### 14. Nach wie vielen Minuten unkomprimierten HD1080i50 Video wäre eine DVD-5 (Single-Layer DVD mit 4,7 GB) voll?

Nach 30 Sekunden, also 0,5 Minuten.

### 15. Was ist der Unterschied zwischen einem Codec und einem Mediencontainer?

- **Codec:** Komprimiert und dekomprimiert Audio- und Videodaten.
- **Mediencontainer:** Beinhaltet verschiedene Datenströme (Video, Audio, Untertitel) in einer Datei.

### 16. Fragen zum AD-Wandler-Video

- **a. Warum benötigt man AD-Wandler?**
  Um analoge Signale (z.B. Ton, Licht) in digitale Signale zu konvertieren, die von Computern verarbeitet und gespeichert werden können.

- **b. Warum geht eine A/D-Wandlung immer mit einem Datenverlust einher?**
  Aufgrund der Diskretisierung und Quantisierung, bei denen kontinuierliche Werte in diskrete Werte umgewandelt werden, was zu einem Verlust von Detailinformationen führt.

- **c. Gibt eine höhere oder eine niedrigere Samplingrate eine präzisere Abbildung des Originals? Begründen Sie!**
  Eine höhere Samplingrate gibt eine präzisere Abbildung des Originals, da sie mehr Datenpunkte pro Sekunde erfasst und somit feinere Details und höhere Frequenzen des analogen Signals genauer wiedergeben kann.
