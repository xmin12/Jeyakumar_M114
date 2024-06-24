# Lösung zu DATEN KOMPRIMIEREN AUFGABEN

### 1. Huffman-Algorithmus

1. **Andere Gebiete in der IT, wo Baumstrukturen zur Anwendung kommen:**

   - **Dateisysteme:** Die Hierarchie von Dateien und Verzeichnissen wird durch Baumstrukturen organisiert.
   - **Datenbanken:** In hierarchischen Datenbanken werden Baumstrukturen verwendet, um Beziehungen zwischen Datensätzen darzustellen.
   - **Parser und Compiler:** Baumstrukturen (z.B. Syntaxbäume) werden verwendet, um den Quellcode zu analysieren und zu verarbeiten.
   - **Netzwerk-Routing:** Baumstrukturen helfen bei der Organisation von Routing-Tabellen.
   - **Spiele:** Baumstrukturen werden zur Organisation von Spielobjekten und Spielereignissen verwendet.

2. Unterschiede zwischen **binären** und **nicht-binären** Bäumen:

   - **Binärer Baum:** Jeder Knoten hat höchstens zwei Kinderknoten oder Äste. Dies ist typisch für Strukturen wie binäre Suchbäume und Heap-Bäume.
   - **Nicht-binärer Baum:** Jeder Knoten kann mehr als zwei Kinderknoten oder Äste haben. Diese Bäume können eine beliebige Anzahl von Kinderknoten haben und sind flexibler in der Darstellung komplexer Hierarchien.

### 2. Huffman-Algorithmus

Der Huffman-Algorithmus wird zur verlustlosen Datenkomprimierung verwendet. Er erstellt einen binären Baum, um die am häufigsten auftretenden Zeichen kürzer zu kodieren und seltener vorkommende Zeichen länger. Dies ermöglicht eine effizientere Speicherung von Daten, indem die Gesamtbitlänge der kodierten Zeichenfolge reduziert wird.

### 3. RLC (Run-Length Coding)

Run-Length Coding ist eine einfache Methode der verlustlosen Datenkomprimierung, die sich wiederholende Zeichen oder Muster durch ein Paar von Symbol und Zähler darstellt. In der Unterrichtsdiskussion wurde erörtert, wie RLC verwendet wird, um Datenmuster effizient zu kodieren, indem Wiederholungen komprimiert werden.

### 4. Beispiel für RLC

Wenn eine Zeichenkette wie `"AAAA"` mit RLC kodiert wird, stellt sie `A` dar. Dies bedeutet, dass das Symbol `A` mehrfach vorkommt und durch einen einzigen Eintrag im komprimierten Format dargestellt wird.

### 8. Weitere verlustlose Komprimierungsverfahren/Daten

1. **Weitere verlustlose Komprimierungsverfahren/Daten:**
   
   Verlustlose Komprimierung ist wichtig, wenn die Daten nach der Dekomprimierung vollständig wiederhergestellt werden müssen. Sie wird häufig für folgende Datentypen verwendet:

   - **Bilder:** Formate wie PNG und GIF verwenden verlustlose Komprimierung, um die Bildqualität zu erhalten.
   - **Ton:** FLAC ist ein Beispiel für verlustlose Audiokomprimierung, die die ursprüngliche Audioqualität bewahrt.
   - **Video:** Einige Formate und Techniken können verlustlos komprimierte Videos erstellen, obwohl sie weniger verbreitet sind.
   - **Textdokumente:** ZIP- und RAR-Dateien komprimieren Textdateien verlustlos.
   - **Quellcode:** Komprimierungstools wie GZIP können Quellcode verlustlos komprimieren, ohne Informationen zu verlieren.

3. **Komprimieren von verlustbehafteten Briefen oder Java-Sourcecode:**

   Verlustbehaftete Komprimierung bedeutet, dass einige Informationen dauerhaft entfernt werden, um Platz zu sparen. Wenn ein Brief oder Java-Sourcecode verlustbehaftet komprimiert wird, könnten folgende Probleme auftreten:

   - **Verlust von Informationen:** Wichtige Daten könnten entfernt werden, was zu unvollständigen oder sinnlosen Informationen führt.
   - **Fehlende oder falsche Daten:** Der Text eines Briefes könnte unlesbar werden oder wichtige Inhalte verlieren.
   - **Fehler im Quellcode:** Ein Java-Sourcecode könnte nach der Komprimie
