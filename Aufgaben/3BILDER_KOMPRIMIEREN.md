# Lösung zu BILDER_KOMPRIMIEREN

### 1. Bestimme die Farben

- **RGB 255/255/255** entspricht **Weiß** und ergibt in **YCbCr**: 1-0-0
- **RGB 0/0/0** entspricht **Schwarz** und ergibt in **YCbCr**: 0-0-0
- **Y:0, Cb:0.5, Cr:0** entspricht der Farbe: **Rot**
- **Y:0, Cb:-0.5, Cr:0** entspricht der Farbe: **Grün**
- **Y:0, Cb:0, Cr:0.5** entspricht der Farbe: **Blau**
- **Y:0, Cb:0, Cr:-0.5** entspricht der Farbe: **Grün**
- **Y:0.3, Cb:0.5, Cr:-0.17** entspricht der Farbe: **Rot**

### 2. Umwandlung von RGB in Graustufen

- **RGB-Werte (Hellblau):** R=33, G=121, B=239
- **Graustufenwert:** 106

### 3. Berechnen Sie, wieviel Speicher eingespart wird, wenn ein Bild mit Subsampling 4:1:1 komprimiert wird

- **Speichereinsparung:** 50%
  - **Original:** 300% Farbinformation (RGB)
  - **Subsampling 4:1:1:** 150% Farbinformation

### 4. RGB und YCrCb

- **a. Kann man durch die Bildumwandlung vom RGB- in den YCbCr-Farbraum Speicherplatz einsparen?**
  - Ja, die Umwandlung von RGB zu YCbCr ermöglicht durch effizientere Farbkompression Speicherplatzersparnis.

- **b. Kann ein Beamer ein Bild im YCbCr-Farbraum darstellen?**
  - Nein, ein Beamer kann Bilder im YCbCr-Farbraum nicht direkt anzeigen, sondern wandelt sie in RGB um.

- **c. Wie rechnet man ein Farbbild in ein Graustufenbild um?**
  - Ein Farbbild wird in ein Graustufenbild umgerechnet, indem die RGB-Werte jedes Pixels entsprechend ihrer Helligkeit gewichtet werden.

- **d. Warum hat bei der Umwandlung eines Farbbildes in ein Graustufenbild der Grünanteil am meisten Gewicht?**
  - Der Grünanteil hat bei der Umwandlung in ein Graustufenbild das meiste Gewicht, da das menschliche Auge empfindlicher auf grünes Licht reagiert.

### 5. Chroma-Subsampling

- **a. Warum verschlechtert sich die Bildschärfe von 4:1:1-Subsampling gegenüber 4:4:4-Subsampling nicht?**
  - Die Bildschärfe verschlechtert sich nicht, weil der Luminanzkanal unverändert bleibt und das menschliche Auge weniger empfindlich auf Farbinformationen reagiert.

- **b. Ein quadratisches 24-Bit-RGB-Bild mit einer Kantenlänge von 1000 Pixel soll mit 4:1:1 komprimiert werden.**
  - **Speichereinsparung:** 50%

### 6. JPEG-Komprimierung

- **a. Was ist der erste Schritt bei der JPEG-Komprimierung?**
  - Umwandlung von RGB in YCbCr, gefolgt von Chroma-Subsampling.

- **b. Führt die DCT-Transformation zu einer Datenreduktion?**
  - Die DCT-Transformation führt nicht direkt zu einer Datenreduktion, sondern stellt die Grundlage für die Quantisierung, die dann zur Datenreduktion führt.

- **c. Warum erhält man bei einer sehr starken Bildkomprimierung sogenannte Block-Artefakte?**
  - Durch die Quantisierung und die 8x8 Block-Transformation entstehen Differenzen zwischen den Blöcken, die sich in sichtbaren Block-Artefakten manifestieren.

### 7. Codecs und Container

- **a. Was ist der Unterschied zwischen Intraframe- und Interframe-Komprimierung?**
  - **Intraframe:** Komprimiert Daten innerhalb eines einzelnen Bildes.
  - **Interframe:** Komprimiert Daten über eine Serie von Bildern hinweg.

- **b. Bei welcher Filmsequenz bietet die Interframekomprimierung mehr Potential zur Datenreduzierung:**
  - **i. 30 Sekunden-Szene mit Faultier auf Nahrungssuche?**
    - Wenig Bewegung, daher hohes Potential zur Datenreduzierung.
  - **ii. 30 Sekunden-Szene mit Zieleinfahrt beim Formel-1-Rennen?**
    - Viele und schnelle Bewegungen, daher weniger Potential zur Datenreduzierung.

- **c. Sehen Sie Parallelen zwischen Datenbackupkonzepten und Interframe-Komprimierung?**
  - **Full Backup:** Alle Daten werden vollständig gesichert (ähnlich Intraframe).
  - **Incremental Backup:** Nur die Änderungen seit dem letzten Backup werden gesichert (ähnlich Interframe).
  - **Differential Backup:** Alle Änderungen seit dem letzten vollständigen Backup werden gesichert.

- **d. Was versteht man unter GOP25?**
  - **GOP (Group of Pictures):** Eine Struktur, in der jedes 25. Bild ein vollständiges Bild ist und die dazwischen liegenden Bilder nur die Differenzen zum vorherigen Bild speichern.
