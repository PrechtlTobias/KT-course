# Fragebogen: Entropie-Analyse (entropy1.py)

Nach dem Ausführen von `entropy1.py` mit eigenem Text in `sampletext.txt`:

**Konsolenausgabe einfügen:** Nutze das Merge-Symbol in der Task-Card, um die Ausgabe aus `console_log.txt` hier einzufügen. Anschließend die Ausgabe **kommentieren**.

---

**1. Konsolenausgabe**

*(Wird per „Konsolenausgabe einfügen“ unten eingefügt. Danach bitte kommentieren.)*

Number of characters: 6409
Character Dictionary: {'*': 278, '\n': 117, ' ': 1463, '-': 407, 'T': 25, 'H': 5, 'E': 25, 'L': 15, 'G': 18, 'N': 21, 'D': 10, 'O': 18, 'F': 28, 'Z': 3, 'A': 45, 'C': 19, 'o': 290, 'm': 93, 'p': 61, 'r': 206, 'e': 383, 'h': 148, 'n': 190, 's': 206, 'i': 196, 'v': 19, 'Q': 24, '/': 36, 'W': 12, 'a': 223, 'l': 137, 'k': 25, 't': 279, 'u': 114, 'g': 68, 'f': 63, 'd': 123, 'S': 17, '|': 24, 'B': 7, 'y': 77, 'M': 15, '(': 11, ')': 30, ':': 8, 'c': 82, '3': 4, '1': 7, '@': 2, '.': 244, '0': 18, '8': 4, ',': 56, '2': 7, 'V': 13, 'I': 52, 'w': 70, 'b': 35, '!': 3, '5': 2, '6': 3, 'P': 6, 'Y': 8, "'": 10, 'j': 2, '>': 1, 'q': 6, '4': 3, '<': 1, '7': 1, '"': 5, 'x': 7, 'X': 12, 'K': 1, 'R': 5, 'U': 1, '\\': 12, '_': 12, '=': 130, 'J': 2}

-------Table of characters:----------------
       | cnt=1463    p=0.228   H=2.131 bit/char  H_av=0.486 bit/char
 -     | cnt=407    p=0.064   H=3.977 bit/char  H_av=0.253 bit/char
 e     | cnt=383    p=0.060   H=4.065 bit/char  H_av=0.243 bit/char
 o     | cnt=290    p=0.045   H=4.466 bit/char  H_av=0.202 bit/char
 t     | cnt=279    p=0.044   H=4.522 bit/char  H_av=0.197 bit/char
 *     | cnt=278    p=0.043   H=4.527 bit/char  H_av=0.196 bit/char
 .     | cnt=244    p=0.038   H=4.715 bit/char  H_av=0.180 bit/char
 a     | cnt=223    p=0.035   H=4.845 bit/char  H_av=0.169 bit/char
 r     | cnt=206    p=0.032   H=4.959 bit/char  H_av=0.159 bit/char
 s     | cnt=206    p=0.032   H=4.959 bit/char  H_av=0.159 bit/char
 i     | cnt=196    p=0.031   H=5.031 bit/char  H_av=0.154 bit/char
 n     | cnt=190    p=0.030   H=5.076 bit/char  H_av=0.150 bit/char
 h     | cnt=148    p=0.023   H=5.436 bit/char  H_av=0.126 bit/char
 l     | cnt=137    p=0.021   H=5.548 bit/char  H_av=0.119 bit/char
 =     | cnt=130    p=0.020   H=5.624 bit/char  H_av=0.114 bit/char
 d     | cnt=123    p=0.019   H=5.703 bit/char  H_av=0.109 bit/char
 b'\n' | cnt=117    p=0.018   H=5.776 bit/char  H_av=0.105 bit/char
 u     | cnt=114    p=0.018   H=5.813 bit/char  H_av=0.103 bit/char
 m     | cnt= 93    p=0.015   H=6.107 bit/char  H_av=0.089 bit/char
 c     | cnt= 82    p=0.013   H=6.288 bit/char  H_av=0.080 bit/char
 y     | cnt= 77    p=0.012   H=6.379 bit/char  H_av=0.077 bit/char
 w     | cnt= 70    p=0.011   H=6.517 bit/char  H_av=0.071 bit/char
 g     | cnt= 68    p=0.011   H=6.558 bit/char  H_av=0.070 bit/char
 f     | cnt= 63    p=0.010   H=6.669 bit/char  H_av=0.066 bit/char
 p     | cnt= 61    p=0.010   H=6.715 bit/char  H_av=0.064 bit/char
 ,     | cnt= 56    p=0.009   H=6.839 bit/char  H_av=0.060 bit/char
 I     | cnt= 52    p=0.008   H=6.945 bit/char  H_av=0.056 bit/char
 A     | cnt= 45    p=0.007   H=7.154 bit/char  H_av=0.050 bit/char
 /     | cnt= 36    p=0.006   H=7.476 bit/char  H_av=0.042 bit/char
 b     | cnt= 35    p=0.005   H=7.517 bit/char  H_av=0.041 bit/char
 )     | cnt= 30    p=0.005   H=7.739 bit/char  H_av=0.036 bit/char
 F     | cnt= 28    p=0.004   H=7.839 bit/char  H_av=0.034 bit/char
 T     | cnt= 25    p=0.004   H=8.002 bit/char  H_av=0.031 bit/char
 E     | cnt= 25    p=0.004   H=8.002 bit/char  H_av=0.031 bit/char
 k     | cnt= 25    p=0.004   H=8.002 bit/char  H_av=0.031 bit/char
 Q     | cnt= 24    p=0.004   H=8.061 bit/char  H_av=0.030 bit/char
 |     | cnt= 24    p=0.004   H=8.061 bit/char  H_av=0.030 bit/char
 N     | cnt= 21    p=0.003   H=8.254 bit/char  H_av=0.027 bit/char
 C     | cnt= 19    p=0.003   H=8.398 bit/char  H_av=0.025 bit/char
 v     | cnt= 19    p=0.003   H=8.398 bit/char  H_av=0.025 bit/char
 G     | cnt= 18    p=0.003   H=8.476 bit/char  H_av=0.024 bit/char
 O     | cnt= 18    p=0.003   H=8.476 bit/char  H_av=0.024 bit/char
 0     | cnt= 18    p=0.003   H=8.476 bit/char  H_av=0.024 bit/char
 S     | cnt= 17    p=0.003   H=8.558 bit/char  H_av=0.023 bit/char
 L     | cnt= 15    p=0.002   H=8.739 bit/char  H_av=0.020 bit/char
 M     | cnt= 15    p=0.002   H=8.739 bit/char  H_av=0.020 bit/char
 V     | cnt= 13    p=0.002   H=8.945 bit/char  H_av=0.018 bit/char
 W     | cnt= 12    p=0.002   H=9.061 bit/char  H_av=0.017 bit/char
 X     | cnt= 12    p=0.002   H=9.061 bit/char  H_av=0.017 bit/char
 \     | cnt= 12    p=0.002   H=9.061 bit/char  H_av=0.017 bit/char
 _     | cnt= 12    p=0.002   H=9.061 bit/char  H_av=0.017 bit/char
 (     | cnt= 11    p=0.002   H=9.186 bit/char  H_av=0.016 bit/char
 D     | cnt= 10    p=0.002   H=9.324 bit/char  H_av=0.015 bit/char
 '     | cnt= 10    p=0.002   H=9.324 bit/char  H_av=0.015 bit/char
 :     | cnt=  8    p=0.001   H=9.646 bit/char  H_av=0.012 bit/char
 Y     | cnt=  8    p=0.001   H=9.646 bit/char  H_av=0.012 bit/char
 B     | cnt=  7    p=0.001   H=9.839 bit/char  H_av=0.011 bit/char
 1     | cnt=  7    p=0.001   H=9.839 bit/char  H_av=0.011 bit/char
 2     | cnt=  7    p=0.001   H=9.839 bit/char  H_av=0.011 bit/char
 x     | cnt=  7    p=0.001   H=9.839 bit/char  H_av=0.011 bit/char
 P     | cnt=  6    p=0.001   H=10.061 bit/char  H_av=0.009 bit/char
 q     | cnt=  6    p=0.001   H=10.061 bit/char  H_av=0.009 bit/char
 H     | cnt=  5    p=0.001   H=10.324 bit/char  H_av=0.008 bit/char
 "     | cnt=  5    p=0.001   H=10.324 bit/char  H_av=0.008 bit/char
 R     | cnt=  5    p=0.001   H=10.324 bit/char  H_av=0.008 bit/char
 3     | cnt=  4    p=0.001   H=10.646 bit/char  H_av=0.007 bit/char
 8     | cnt=  4    p=0.001   H=10.646 bit/char  H_av=0.007 bit/char
 Z     | cnt=  3    p=0.000   H=11.061 bit/char  H_av=0.005 bit/char
 !     | cnt=  3    p=0.000   H=11.061 bit/char  H_av=0.005 bit/char
 6     | cnt=  3    p=0.000   H=11.061 bit/char  H_av=0.005 bit/char
 4     | cnt=  3    p=0.000   H=11.061 bit/char  H_av=0.005 bit/char
 @     | cnt=  2    p=0.000   H=11.646 bit/char  H_av=0.004 bit/char
 5     | cnt=  2    p=0.000   H=11.646 bit/char  H_av=0.004 bit/char
 j     | cnt=  2    p=0.000   H=11.646 bit/char  H_av=0.004 bit/char
 J     | cnt=  2    p=0.000   H=11.646 bit/char  H_av=0.004 bit/char
 >     | cnt=  1    p=0.000   H=12.646 bit/char  H_av=0.002 bit/char
 <     | cnt=  1    p=0.000   H=12.646 bit/char  H_av=0.002 bit/char
 7     | cnt=  1    p=0.000   H=12.646 bit/char  H_av=0.002 bit/char
 K     | cnt=  1    p=0.000   H=12.646 bit/char  H_av=0.002 bit/char
 U     | cnt=  1    p=0.000   H=12.646 bit/char  H_av=0.002 bit/char
-------------------------------------------

Average Entropy H = 4.726 bit/char
Total Entropy of 6409 characters H=30288.78 bit = 3787.00 byte
---

**2. Deine Kommentierung:**

- Was fällt dir bei der Entropie deines Textes auf?  
  *[z. B. Vergleich mit anderen Texten, Zeichenverteilung, Redundanz]*

wikipediatextvergleich:

Average Entropy H = 4.743 bit/char
Total Entropy of 1006 characters H=4770.96 bit = 597.00 byte

Die Average Entropy ist bei Texten ca gleich.
Das häufigste zeichen ist ein Leerzeichen und die Verteilung ist sehr angewiesen ob es eine Deutscher text oder englicher ist und so sind selbstlaute oder Buchstaben die häufig in der jeweiligen sprache vorkommen öfters am vorkommen.