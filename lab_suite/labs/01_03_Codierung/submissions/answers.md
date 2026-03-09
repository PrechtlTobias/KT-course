# Fragebogen: Huffman-Codierung (huffman.py)

Nach dem Ausführen des Skripts und **Einfügen der Konsolenausgabe** (Merge-Symbol in der Task-Card):

---

**1. Konsolenausgabe**

*(Wird per „Konsolenausgabe einfügen“ unten eingefügt. Danach bitte kommentieren.)*

Enter the string to compute Huffman Code Tree: ADSIFHSKDAFHLKDSFHDHALFKDSLJFLKDJ
---------------------------------------------------------
Dictionary of Characters with char frequency:       {'A': 3, 'D': 6, 'S': 4, 'I': 1, 'F': 5, 'H': 4, 'K': 4, 'L': 4, 'J': 2}
Dictionary converted into a list:                   dict_items([('A', 3), ('D', 6), ('S', 4), ('I', 1), ('F', 5), ('H', 4), ('K', 4), ('L', 4), ('J', 2)])
List of characters sorted to descending frequency:  [('D', 6), ('F', 5), ('S', 4), ('H', 4), ('K', 4), ('L', 4), ('A', 3), ('J', 2), ('I', 1)]
Huffman Code Dictionary:                            {'D': '00', 'H': '010', 'S': '011', 'L': '100', 'K': '101', 'F': '110', 'I': '11100', 'J': '11101', 'A': '1111'}

 Char | Huffman code
----------------------
 'D'  |          00
 'F'  |         110
 'S'  |         011
 'H'  |         010
 'K'  |         101
 'L'  |         100
 'A'  |        1111
 'J'  |       11101
 'I'  |       11100

---

**2. Deine Kommentierung**

- Was zeigen die ausgegebenen Huffman-Codes?  
  *[kurz beschreiben]*
  In meiner Zeichenkette ist D am häufigsten also hat dieser Buchstabe den kürzesten Code bekommen, weiter I ist nur einmal am Vorkommen, also wurde dem und J welches etwas häufiger vorkommt, einen längeren Codewort angehängt

- Warum haben häufigere Zeichen kürzere Codewörter?  
  *[kurz begründen]*
  Da bei der Komprimierung so ein kürzerer Übertragungscode erstellt werden kann und bei einem längeren Text ersparrt man sich so Übertragungsbits.