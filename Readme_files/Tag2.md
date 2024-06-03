# Aufgaben

## 1. Huffman-Algorithmus
### Aufgabe:
Wir beschäftigen uns hier mit sogenannten Baumstrukturen. Kennen Sie noch andere Gebiete in der IT, wo Baumstrukturen zur Anwendung kommen? Beim Huffman handelt es sich sogar um eine spezielle Baumstruktur, nämlich einen sogenannten binären Baum. Was unterscheidet einen binären Baum von einem nicht-binären Baum?

### binärer Baum vs. !binärer Baum:
Ein binärer Baum hat pro Knoten nur zwei Kinder. Es gibt nur Astgabeln mit zwei abzweigenden Ästen.

### Wo kommen Baumstrukturen zur Anwendung?
- **Datenbanken:** Baumstrukturen wie B-Bäume und B+-Bäume werden verwendet, um Indizes für schnelle Datensuche zu organisieren.
- **Dateisysteme:** Hierarchische Dateisysteme verwenden Baumstrukturen, um Ordner und Dateien zu organisieren.
- **Compilerbau:** Abstrakte Syntaxbäume (AST) werden verwendet, um die Struktur von Quellcode während der Kompilierung darzustellen.

## 2. Huffman-Algorithmus
### Aufgabe:
In dieser Aufgabe arbeiten Sie zu zweit: Jeder denkt sich ein Wort mit ca. 15 Buchstaben aus und erstellt dazu den Huffman-Code inkl. Codetabelle und das entsprechend komprimierte Wort in Binärdarstellung. Tauschen Sie Ihre Codes und Codetabellen gegenseitig aus und vergewissern Sie sich, dass Ihr Partner Ihr gewähltes Wort richtig dekomprimieren kann. Sie haben die Aufgabe dann vollständig gelöst, wenn Sie einen korrekten binären Baum vorweisen können, die Codes herausgelesen und tabellarisch notiert haben und das komprimierte Wort in Huffman-Binärcode nicht fehlt.

## 3. RLC
### Aufgabe:
Wie könnte die Komprimierung ausschauen, wenn es sich anstatt um ein Schwarz/Weißbild, um ein Farbbild handelt? Benachbarte Pixel mit identischer Farbe werden ja bei RLC bekanntlich nicht einzeln genannt, sondern zu einer Anzahl zusammengefasst wie z.B. 11xGrün, 6xBlau, 3xWeiß etc. oder in binärer Schreibweise 1011Grün, 0110Blau, 0011Weiß. Welche Bitbreite (1011Grün ergäbe 4 Bit) wäre bei einem quadratischen Bild mit 20 Pixel Kantenlänge sinnvoll? Was wäre, wenn dieses Bild nur aus einer Farbe besteht?

### Antwort:
Wenn nur eine Farbe im Bild dargestellt wird, würde es Sinn ergeben pro Zeile 5 Bit zu verwenden. Da aber 400 mal die gleiche Farbe vorkommt, können wir dies in einem Code speichern. Die Bitlänge für die Zahl 400 im binären Zahlenraum beträgt: 9 Bit

Wenn aber nun jeder Pixel eine andere Farbe hat, benötigt man zwar nur einen Bit pro Farbe, dafür aber insgesamt viel mehr. Sprich 20 Bit pro Zeile -> 400 Bit für das ganze Bild.

## 4. RLC
### Aufgabe:
Sie erhalten diesen RL-Code: 010100011110010010010010010010010010010110010110010010010010010010010010001. Folgendes ist Ihnen dazu bekannt: Es handelt sich um eine quadratische Schwarz/Weiß-Rastergrafik mit einer Kantenlänge von 8 Pixel. Es wird links oben mit der Farbe Weiß begonnen. Eine Farbe kann sich nicht mehr als siebenmal wiederholen. Zeichnen Sie die Grafik auf. Was stellt sie dar?

### Code-Analyse:

```sh
010 100 011 110 010 010 010 010 010 010 010 010 010 110 010 110 010 010 010 010 010 010 010 010 001
| | | | | | | | | | | | | | | | | | | | | | | | |
2 4 3 6 2 2 2 2 2 2 2 2 2 6 2 6 2 2 2 2 2 2 2 2 1
| | | | | | | | | | | | | | | | | | | | | | | | |
W S W S W S W S W S W S W S W S W S W S W S W S W
```

Es wird ein 'A' dargestellt.

## 5. LZW-Verfahren
### Aufgabe:
a. Erstellen Sie die LZW-Codierung für das Wort „ANANAS“ und überprüfen Sie mit der Dekodierung Ihr Resultat.

### LZW-Codierung:
| Zeichenkette | Gefunden | Gespeichert | Eintrag | Nummer |
|--------------|----------|-------------|---------|--------|
| ananas       | a        | a           | an      | 256    |
| nanas        | n        | n           | na      | 257    |
| anas         | a        | 256         | ana     | 258    |
| as           | a        | a           | as      | -      |

### Resultat:
ANANAS = an256as

### Aufgabe:
b. Versuchen Sie den erhaltenen LZW-Code „ERDBE<256>KL<260>“ zu dekomprimieren.

### LZW-Dekodierung:
| Zeichenkette   | Gefunden | Ausgabe | Eintrag | Nummer |
|----------------|----------|---------|---------|--------|
| erdbe256kl260  | e        | e       | -       | -      |
| rdbe256kl260   | r        | r       | er      | 256    |
| dbe256kl260    | d        | d       | rd      | 257    |
| be256kl260     | b        | b       | db      | 258    |
| e256kl260      | e        | e       | be      | 259    |
| 256kl260       | e        | er      | ee      | 260    |
| kl260          | k        | k       | ek      | 261    |
| l260           | l        | l       | kl      | 262    |
| 260            | e        | ee      | le      | 263    |

### Resultat:
ERDBE<256>KL<260> = erdbeerdklee

## 6. BWT (Burrows-Wheeler-Transformation)
### Aufgabe:
a. Erstellen Sie die BWT-Transformation für das Wort ANANAS und überprüfen Sie mit der Rücktransformation Ihr Resultat.

### b. Aufgabe:
Sie erhalten den Code IICRTGH6 in der Burrows-Wheeler-Transformation. Welches Wort verbirgt sich dahinter?

## 7. ZIP-Komprimierung
### Aufgabe:
Wir wollen die Effizienz bei der ZIP-Komprimierung untersuchen. Dazu sollen Sie ASCII-Textdateien erstellen.

### Schritte:
a. Die erste enthält 10, die zweite 100, die dritte 1000, die vierte 10'000 und die fünfte 100'000 ASCII-Zeichen.
b. Achten Sie darauf, dass die Zeichen möglichst zufällig gewählt werden. Auf dem Internet findet man entsprechende Textgeneratoren.
c. Kopieren Sie jede dieser fünf Textdateien in eine eigene ZIP-Datei. In der Folge erhalten Sie fünf ZIP-Dateien.
d. Werten Sie nun in einer EXCEL-Tabelle die erforderlichen Speichergrößen aus: ASCII-Datei-Größe zu ZIP-Datei-Größe. Versuchen Sie nun, Ihr Resultat zu interpretieren bzw. zu begründen. Tipp: Sie können in EXCEL Zahlenreihen auch grafisch anzeigen.
e. Nun legen wir noch einen drauf: Erstellen Sie eine ASCII-Textdatei mit 100'000 Zeichen. Diesmal aber nicht zufällig (random) befüllt, sondern ausschließlich mit dem Buchstaben A, danach zippen Sie. Vergleichen Sie nun die beiden ZIP-Dateien. Wie erklären Sie sich den Unterschied der Speichergrößen?
f. Zu guter Letzt wollen wir untersuchen, was die ZIP-Komprimierung bringt, wenn die Originaldatei, wie beim JPG-Bildformat, bereits komprimiert (DCT) vorliegt. Dazu erhalten Sie die zwei folgenden Bilder:
  - [Bild 1](https://www.juergarnold.ch/Kompression/ZIPTestHi.jpg)
  - [Bild 2](https://www.juergarnold.ch/Kompression/ZIPTestLo.jpg)




