
# Lösungen zu den Aufgaben - Daten Komprimieren

## Aufgabe 1: Huffman-Algorithmus
- **Andere Anwendungen von Baumstrukturen in der IT:** Dateisysteme mit einem Wurzelverzeichnis und Verästelungen.
- **Unterschied zwischen binären und nicht-binären Bäumen:** In einem binären Baum hat jeder Knoten genau zwei Äste.

## Aufgabe 2: Huffman-Algorithmus (Praktische Übung)
Erstellen Sie ein Wort mit ca. 15 Buchstaben, bilden Sie den Huffman-Code und tauschen Sie diesen mit einem Partner aus, um die Dekomprimierung zu testen.

## Aufgabe 3: RLC-Komprimierung bei Farbbildern
- **Fragestellung:** Wie würde die RLC-Komprimierung bei einem Farbbild aussehen, wenn benachbarte Pixel identische Farben haben?
- **Diskussionsthema:** Optimale Bitbreite bei einem quadratischen Bild mit 20 Pixel Kantenlänge und mögliche Unterschiede bei einfarbigen Bildern.

## Aufgabe 4: RLC-Komprimierung - Grafikdarstellung
- **Aufgabe:** Zeichnen Sie die Grafik aus einem gegebenen RL-Code. Es handelt sich um ein 8x8 Schwarz-Weiß-Bild, das mit Weiß beginnt.
- **Ergebnis:** Das Bild stellt den Großbuchstaben 'A' dar.

## Aufgabe 5: LZW-Komprimierungsverfahren
### a. Codierung für das Wort "ANANAS"
- **LZW-Codierung:** AN«256»AS
### b. Dekomprimierung des LZW-Codes "ERDBE<256>KL<260>"
- **LZW-Dekodierung:** ERDBEERKLEE

## Aufgabe 6: Burrows-Wheeler-Transformation (BWT)
### a. BWT für das Wort ANANAS
- **BWT-Transformation:** SNNAAA1
### b. Rücktransformation für den Code IICRTGH6
- **BWT-Rücktransformation:** RICHTIG

## Aufgabe 7: ZIP-Komprimierung
- **Aufgabe:** Untersuchung der Effizienz von ZIP-Komprimierung durch das Erstellen und Vergleichen verschiedener ZIP-Dateigrößen.
- **Diskussion:** Interpretation der Komprimierungseffizienz basierend auf ASCII-Textdateigrößen im Vergleich zu deren ZIP-Komprimierten Größen.

## Zusatzfragen
- **Verlustlose Komprimierungsverfahren:** Diskutieren Sie die Anwendbarkeit und Folgen verlustbehafteter vs. verlustloser Komprimierung.
