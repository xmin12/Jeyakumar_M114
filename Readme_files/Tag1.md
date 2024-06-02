# Aufgaben

## 1. Erstellen sie eine leere Tabelle mit 6 Kolonnen und 16 Zeilen. Füllen sie diese wie folgt aus:

Kolonne 1: Dezimalzahlen von 0 bis 15  
Kolonne 2: Hexadezimalzahlen von 0 bis F  
Kolonne 3, 4, 5, und 6: die entsprechenden Binärzahlen

| Dezimal | Hexadezimal | Binär | Binär | Binär | Binär |
|---------|-------------|-------|-------|-------|-------|
| 0       | 0           | 0000  | 0000  | 0000  | 0000  |
| 1       | 1           | 0001  | 0001  | 0001  | 0001  |
| 2       | 2           | 0010  | 0010  | 0010  | 0010  |
| 3       | 3           | 0011  | 0011  | 0011  | 0011  |
| 4       | 4           | 0100  | 0100  | 0100  | 0100  |
| 5       | 5           | 0101  | 0101  | 0101  | 0101  |
| 6       | 6           | 0110  | 0110  | 0110  | 0110  |
| 7       | 7           | 0111  | 0111  | 0111  | 0111  |
| 8       | 8           | 1000  | 1000  | 1000  | 1000  |
| 9       | 9           | 1001  | 1001  | 1001  | 1001  |
| 10      | A           | 1010  | 1010  | 1010  | 1010  |
| 11      | B           | 1011  | 1011  | 1011  | 1011  |
| 12      | C           | 1100  | 1100  | 1100  | 1100  |
| 13      | D           | 1101  | 1101  | 1101  | 1101  |
| 14      | E           | 1110  | 1110  | 1110  | 1110  |
| 15      | F           | 1111  | 1111  | 1111  | 1111  |

### Beobachtung:
Die Kolonnen mit den Binärzahlen sind identisch, was zeigt, dass vier Kolonnen für dieselbe Information redundant sind.

## 2. Wandeln sie die folgende Dezimalzahl ohne Taschenrechner in die entsprechende Binärzahl um: 911

### Rechenweg:
911 = 512 + 256 + 128 + 8 + 4 + 2 + 1

### Lösung:
911 = 0011 1000 1111

## 3. Wandeln sie die folgende Binärzahl ohne Taschenrechner in die entsprechende Dezimalzahl um: 1011'0110

### Rechenweg:
1011 0110 = 2 + 4 + 16 + 32 + 128

### Lösung:
1011 0110 = 182

## 4. Wandeln sie die folgende Binärzahl ohne Taschenrechner in die entsprechende Hexadezimalzahl um: 1110'0010'1010'0101

### Rechenweg:
1110 0010 1010 0101

1110 = E  
0010 = 2  
1010 = A  
0101 = 5  

### Lösung:
1110 0010 1010 0101 = E2A5

## 5. Was ergibt die Addition der beiden binären Zahlen 1101'1001 und 0111'0101?

### Rechenweg:
1101 1001 + 0111 0101 = 0001 0100 1110 (inkl. Übertrag)

### Lösung:
Da nur 8 Binärstellen für das Ergebnis zur Verfügung stehen, wird der Übertrag ignoriert. Die Lösung lautet also: 0100 1110

## 6. Was könnten die beiden folgenden binären Wert für eine Bedeutung haben?

### a. 1100’0000.1010’1000.0100’1100.1101’0011

### Rechenweg:
1100'0000 -> 192  
1010'1000 -> 168  
0100'1100 -> 76  
1101'0011 -> 211  

### Lösung:
192.168.76.211 sieht aus wie eine IP-Adresse.

### b. 1011’1110-1000’0011-1000’0101-1101’0101-1110’0100-1111’1110

### Rechenweg:
1011'1110 -> BE  
1000'0011 -> 83  
1000'0101 -> 85  
1101'0101 -> D5  
1110'0100 -> E4  
1111'1110 -> FE  

### Lösung:
BE-83-85-D5-E4-FE sieht aus wie eine MAC-Adresse.

## 8. Dimensionieren sie für den Matterhorn-Express die Codebreite des Binärcodes für die Kabinenzählung bei 107 Gondeln.

### Rechenweg:
107 = 0110 1011

### Lösung:
Es werden 7 Stellen für den Binärcode benötigt.

## 9. Sie untersuchen einen Arbeitsspeicher mit 12-Bit-Adress- bzw. 16-Bit-Datenbus. Welche Speicherkapazität in kiB besitzt dieser?

### Rechenweg + Lösung:
2^12 = 4'096 Adressen  
4096 * 16-Bit-Datenbus = 65'536 Bits  
65'536 / 8 = 8'192 Bytes  
8'192 / 1024 = 8 KiB

## 10. Zwei Geräte sind mit einer seriellen Leitung und zusätzlichem Taktsignal verbunden. Das Taktsignal beträgt 1MHz.

### a. Wie viele Bytes können damit pro Sekunde übertragen werden?
1MHz / Byte (8 Bits) = 1 MByte

### b. Wie viele Bytes pro Sekunde könnten übertragen werden, wenn die Verbindung der beiden Geräte nicht seriell, sondern 8 Bit-parallel wäre?
Genau gleich, da 8 Bit gesendet werden, also ein Byte pro Takt. Bei 1MHz sind das 1 MByte.

## 13. Erstellen sie die Wahrheitstabellen für die folgenden Funktionen:

### a. Logisch UND/AND (mit zwei Eingangs- und einer Ausgangsvariablen)
| Eingang A | Eingang B | Ausgang |
|-----------|-----------|---------|
| 0         | 0         | 0       |
| 0         | 1         | 0       |
| 1         | 0         | 0       |
| 1         | 1         | 1       |

### b. Logisch ODER/OR (mit zwei Eingangs- und einer Ausgangsvariablen)
| Eingang A | Eingang B | Ausgang |
|-----------|-----------|---------|
| 0         | 0         | 0       |
| 0         | 1         | 1       |
| 1         | 0         | 1       |
| 1         | 1         | 1       |

### c. Logisch NICHT/NOT (mit einer Eingangs- und einer Ausgangsvariablen)
| Eingang | Ausgang |
|---------|---------|
| 0       | 1       |
| 1       | 0       |

### d. Logisch EXOR (mit zwei Eingangs- und einer Ausgangsvariablen)
| Eingang A | Eingang B | Ausgang |
|-----------|-----------|---------|
| 0         | 0         | 0       |
| 0         | 1         | 1       |
| 1         | 0         | 1       |
| 1         | 1         | 0       |

## 14. Versuchen sie die folgende Berechnungen auszuführen:

### a. 11 % 2 = 1
### b. 10 % 2 = 0
### c. 10 % 3 = 1
### d. 10 % 5 = 0
### e. 10 % 9 = 1

### Antwort:
Die Modulo-Operation (%) berechnet den Rest einer Division der ersten Zahl durch die zweite. Wenn der Rest 0 ist, bedeutet dies, dass die erste Zahl ohne Rest durch die zweite teilbar ist. Ansonsten ergibt sich der Rest der Division als Ergebnis der Modulo-Operation.
