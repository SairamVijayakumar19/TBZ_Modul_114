
# Lösungen zu den Aufgaben - Bilder Komprimieren

## Aufgabe 1: Luminanz-Chrominanz-Beschreibung von Farben
- **RGB 255/255/255 (Weiß):** YCbCr: 1-0-0
- **RGB 0/0/0 (Schwarz):** YCbCr: 0-0-0
- **YCbCr Werte und deren Farbentsprechungen:**
  - Y:0, Cb:0.5, Cr:0: Rot
  - Y:0, Cb:-0.5, Cr:0: Grün
  - Y:0, Cb:0, Cr:0.5: Blau
  - Y:0, Cb:0, Cr:-0.5: Ebenfalls Grün
  - Y:0.3, Cb:0.5, Cr:-0.17: Ebenfalls Rot

## Aufgabe 2: Umwandlung von RGB in Graustufen
- **RGB-Werte (Hellblau):** R=33, G=121, B=239
- **Graustufenwert:** 106 (Berechnung: Rot: 33 x 0.3 + Grün: 121 x 0.6 + Blau: 239 x 0.1)

## Aufgabe 3: Speichereinsparung durch Subsampling 4:1:1
- **Speichereinsparung:** 50% (Original: 300% Farbinformation, Subsampling: 150%)

## Aufgabe 4: RGB und YCbCr im Videokontext
- **Speicherplatzeinsparung:** Nein, gleich viele Kanäle mit gleichbleibender Bitauflösung.
- **Darstellung durch Beamer:** Nein, RGB benötigt aufgrund des additiven Farbsystems.

## Aufgabe 5: Chroma-Subsampling und Bildschärfe
- **Bildschärfe bei 4:1:1 vs. 4:4:4:** Keine Verschlechterung, da Luminanzkanal unverändert bleibt.
- **Speicherplatzeinsparung bei 1000x1000 Pixel RGB-Bild:** 50%

## Aufgabe 6: JPG-Komprimierung
- **Erster Schritt:** Umwandlung von RGB in YCbCr, gefolgt von Subsampling.
- **DCT-Transformation:** Keine direkte Datenreduktion, Quantisierung benötigt.
- **Block-Artefakte:** Durch 8x8 Block-Quantisierung und anschließende Angleichung der Farbwerte innerhalb der Blöcke.

## Aufgabe 7: Codecs und Container
- **Intraframe vs. Interframe Komprimierung:**
  - Intraframe: Innerhalb eines Bildes.
  - Interframe: Über eine Bildserie.
- **GOP25:** Group of Pictures, wo jedes 25. Bild ein vollständiges Bild ist.

## Optional: Erstellen eines vertonten Videoclips
- **Verwendete Software:** Shotcut, OpenShot, Any Video Converter.
- **Aufgabe:** Bearbeitung von Videosequenzen mit Effekten und Text, Zielmedien-Anpassungen.
