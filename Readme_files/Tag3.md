# Aufgaben

## 1. Bestimmen Sie die Farben für die folgenden RGB-Farbcodes (in Dezimal und Hexadezimal)

Nutzen Sie dazu die beiden Online-Tools:

- [Color Picker Hexa](https://www.colorpicker.com/)
- [Color Picker RGB](https://www.rapidtables.com/web/color/RGB_Color.html)

### Codes übersetzen

- **RGB(255, 255, 255)** entspricht Farbe: **Weiß**
- **RGB(0,0,0)** entspricht Farbe: **Schwarz**
- **RGB(252,178,91)** entspricht Farbe: **komisches Orange**
- **#FF0000** entspricht Farbe: **Rot**
- **#00FF00** entspricht Farbe: **Grün**
- **#0000FF** entspricht Farbe: **Blau**
- **#FFFF00** entspricht Farbe: **Gelb**
- **#00FFFF** entspricht Farbe: **Cyan**
- **#FF00FF** entspricht Farbe: **Magenta**
- **#000000** entspricht Farbe: **Schwarz**
- **#FFFFFF** entspricht Farbe: **Weiß**
- **#00BC00** entspricht Farbe: **Grün**

## 2. Bestimmen Sie die Farben für die folgenden prozentualen CMYK-Angaben

Nutzen Sie den CMYK-Farbenmixer bzw. das folgende Online-Tool:

- [Color Picker CMYK](https://www.rapidtables.com/web/color/CMYK_Color.html)

### Codes übersetzen

- **C:0%, M:100%, Y:100%, K:0%** entspricht Farbe: **Rot**
- **C:100%, M:0%, Y:100%, K:0%** entspricht Farbe: **Grün**
- **C:100%, M:100%, Y:0%, K:0%** entspricht Farbe: **Blau**
- **C:0%, M:0%, Y:100%, K:0%** entspricht Farbe: **Gelb**
- **C:100%, M:0%, Y:0%, K:0%** entspricht Farbe: **Cyan**
- **C:0%, M:100%, Y:0%, K:0%** entspricht Farbe: **Magenta**
- **C:100%, M:100%, Y:100%, K:0%** entspricht Farbe: **Weiß**
- **C:0%, M:0%, Y:0%, K:100%** entspricht Farbe: **Schwarz**
- **C:0%, M:0%, Y:0%, K:0%** entspricht Farbe: **Weiß**
- **C:0%, M:46%, Y:38%, K:22%** entspricht Farbe: **komisches Pink**

## 3. Berechnen Sie den theoretischen Speicherbedarf eines unkomprimierten RGB-Bildes

Ein unkomprimiertes RGB-Bild mit der Größe 640 x 480 und 8-Bit Auflösung pro Farbkanal benötigt etwa 7.37 Megabyte Speicherplatz.

### Lösungsweg:

- Bildgröße: **640 x 480** = **307'200 Pixel**
- 8 Bit (pro Farbkanal) × 3 Farben = **24 Bit (pro Pixel)**
- **307'200 × 24 Bit** = **7'372'800 Bits**
- **7'372'800 / 8** = **921’600 Bytes**

**Antwort:** Theoretischer Speicherbedarf: **7.37 Megabyte**

## 4. Wahl des Bildformats für eine Webseite

Ich würde mich für das **PNG-Format** entscheiden, da dieses Format Transparenz erlaubt und verlustfrei komprimiert. Es ist außerdem eines der gängigsten Formate.

## 5. Pixelauflösung eines 30-Zoll-Displays

Ein 30-Zoll-Display im Format 16:10 und 100 ppi hat die folgende Pixelauflösung:

### Lösungsweg:

- Diagonale: **30 inches** = **76.2 cm**
- Seitenverhältnis: **16:10**
- \(a^2 + b^2 = c^2\) 
  - \((16x)^2 + (10x)^2 = 356x^2\)
  - **356x^2 = 76.2^2**
  - **x^2 = 16.3**
  - **x = 4.04**

- Höhe: **10 × 4.04** = **40.4 cm**
- Breite: **16 × 4.04** = **64.64 cm**

- Höhe in inches: **40.4 / 2.54** = **15.9 inches**
- Breite in inches: **64.64 / 2.54** = **25.4 inches**

- Höhe in Pixel: **15.9 × 100** = **1590 Pixel**
- Breite in Pixel: **25.4 × 100** = **2540 Pixel**

**Antwort:** 
- **Vertikal:** 1590 Pixel
- **Horizontal:** 2540 Pixel

## 6. Größe eines gedruckten Fotos

Ein Foto mit einer Kantenlänge von 2000 Pixel bei 600 dpi hat die folgende Größe:

### Lösungsweg:

- **600 dpi / 2.54** = **236 Pixel pro cm**
- **2000 Pixel / 236** = **8.48 cm**

**Antwort:** Die Kantenlänge ist **8.48 cm**

## 7. Speicherbedarf eines unkomprimierten Einzelbildes

Der Speicherbedarf eines unkomprimierten Einzelbildes im HD1080p50-Format beträgt:

### Lösungsweg:

- Auflösung: **1'080 Höhe × 1'920 Breite**
- **1'080 Höhe × 1'920 Breite × 3 Byte** = **6'220'800 Bytes**

### Für ein Video (90 Minuten)

- **6'220'800 Bytes × 25 Bilder pro Sekunde** = **155'520'000 Bytes pro Sekunde**
- **155'520'000 Bytes × (90 min × 60 Sekunden)** = **839'808'000'000 Bytes**

### Umrechnung

- **839'808'000'000 Bytes** = **820'125'000 Kilobytes**
- **820'125'000 Kilobytes** = **800'903,3 Megabytes**
- **800'903,3 Megabytes** = **782,13 Gigabytes**

**Antwort:** Der Speicherbedarf beträgt **782,13 GB**

## 8. Speicherbedarf eines Videos bei 3 Minuten Spieldauer

Der Speicherbedarf eines HD-Videos bei einer Spieldauer von 3 Minuten beträgt:

### Lösungsweg:

- **155'520'000 Bytes × 180 Sekunden** = **27'993'600'000 Bytes**
- **27'993'600'000 Bytes** = **27'337'500 Kilobytes**
- **27'337'500 Kilobytes** = **26'696,78 Megabytes**
- **26'696,78 Megabytes** = **26.07 Gigabytes**

**Antwort:** Der Speicherbedarf beträgt **26.07 Gigabytes**

## 14. Maximale Aufnahmedauer für eine DVD-5

Eine DVD-5 (Single-Layer DVD mit 4.7 GB) bietet Platz für:

### Lösungsweg:

- **155'520'000 Bytes** = **151'875 Kilobytes** = **148,315 Megabytes** = **0.145 Gigabytes** pro Minute
- **4.7 GB / 0.145 GB pro Minute** = **32.4 Minuten pro Single-Layer DVD**

**Antwort:** Auf einer Single-Layer DVD hat es für **32.4 Minuten** unkomprimierte Film-Daten Platz.
