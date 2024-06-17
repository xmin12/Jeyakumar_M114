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



# Aufgaben

## 1. Luminanz-Chrominanz-Beschreibung von Farben

Verwenden Sie das Online-Tool: [Colorizer](https://colorizer.org/)

### Codes übersetzen:

- **RGB 255/255/255** entspricht **Weiß** und ergibt in YCbCr: **100**
- **RGB 0/0/0** entspricht **Schwarz** und ergibt in YCbCr: **000**
- **Y:0, Cb:0.5, Cr:0** entspricht der Farbe: **Rot**
- **Y:0, Cb:-0.5, Cr:0** entspricht der Farbe: **Grün**
- **Y:0, Cb:0, Cr:0.5** entspricht der Farbe: **Blau**
- **Y:0, Cb:0, Cr:-0.5** entspricht der Farbe: **Dunkelgrün**
- **Y:0.3, Cb:0.5, Cr:-0.17** entspricht der Farbe: **Hellrot**

## 2. Grauwertberechnung eines RGB-Farbbildes

Für ein RGB-Farbbild, das nur die Farbe Weiß als Hintergrund und ein Hellblau mit den Werten R=33, G=121, B=239 (8 Bit pro Farbkanal) verwendet, soll der entsprechende Grauwert berechnet werden. 

### Lösung:

Der Grauwert für Hellblau (R=33, G=121, B=239) wird wie folgt berechnet:

\[ \text{Grauwert} = ((R \times 0.3) + (G \times 0.6) + (B \times 0.1)) \]

1. Ersetzen Sie die Werte:

\[ \text{Grauwert} = ((33 \times 0.3) + (121 \times 0.6) + (239 \times 0.1)) \]

2. Berechnen Sie jeden Teil:

\[ 33 \times 0.3 = 9.9 \]
\[ 121 \times 0.6 = 72.6 \]
\[ 239 \times 0.1 = 23.9 \]

3. Addieren Sie die Ergebnisse:

\[ 9.9 + 72.6 + 23.9 = 106.4 \]

**Antwort:** Der Grauwert für das Hellblau beträgt **106.4**.

## 3. Speicherersparnis bei Subsampling 4:1:1

Subsampling ist eine Technik zur Reduzierung der Datenmenge bei der Bildkompression, indem Farbkanäle weniger häufig abgetastet werden als die Luminanzkanäle. Beim 4:1:1 Subsampling wird die chromatische Abtastung stark reduziert.

### Lösung:

- Bei 4:1:1 Subsampling wird die chromatische Information um den Faktor 4 reduziert, was bedeutet, dass für jede Gruppe von 4 Pixeln nur eine chromatische Information gespeichert wird.

- Die ursprüngliche Speicheranforderung für die vollständige Abtastung (4:4:4) wäre:

  \[ 4 \times (\text{Luminanz} + \text{Chrominanz} \text{(Cb)} + \text{Chrominanz} \text{(Cr)}) = 12 \text{ Einheiten} \]

- Mit 4:1:1 Subsampling werden die chromatischen Kanäle (Cb und Cr) nur einmal pro 4 Pixel gespeichert:

  \[ 4 \times \text{Luminanz} + 1 \times \text{Chrominanz (Cb)} + 1 \times \text{Chrominanz (Cr)} = 6 \text{ Einheiten} \]

- Speicherersparnis:

  \[ \frac{12 - 6}{12} = \frac{6}{12} = \frac{1}{2} = 50\% \]

**Antwort:** Die Einsparung beträgt **50%**.

