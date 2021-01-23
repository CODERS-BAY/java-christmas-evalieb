# Christmas Exercise :santa:
## Wiederholung der Vererbung und der Objektorientierung

Bitte versuche als Übung alles in Markdown zu beantworten. Hier ist ein [Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

1. Was ist das Ziel der Objektorientierung?
 * komplexe Programme werden in Teilprogramme zerlegt. Objekte werden in Klassen zusammengefasst. 
 durch das zerlegen in Teilprogramme
2. Gibt es OOP nur in Java?
 * Nein!
3. Was ist der Unterschied zwischen Objekt und Klasse?
 * Objekte können unterschiedliche Atributte haben. Sie werden in Klassen zusammengefasst. Dh. eine Klasse beherbergt mehrere - auch unterschiedliche Objekte. 
 zB. können in der Klasse Animal verschiede Objekte angelegt sein. Dh. sowohl Fische als auch Säugetiere.
 Die Klasse beschreibt somit die Struktur der Objekte. 
 Die Konstruktoren werden zur Initialisierung der Objekte benötig. 
 Ein Objekt ist immer nur Instanz von genau einer Klasse. 
 Die Klasse wiederum hat ihre eigenen Methoden. 
 Ein Programm kann unendlich viele Klassen haben
4. Wie erzeuge ich eine neue Instanz? (Welches Schlüsselwort gibt es dafür)
 * das Schlüsselwort hierfür ist *new* 
 MeinTier neuesTier = new MeinTier();
5. Was bedeutet das Schlüsselwort `static` und wo kann es überall verwendet werden?
 * static bedeutet *statisch* und steht im Gegensatz zu dynamischen Programmen
 static wird zB bei Methoden verwendet, wie hier bei der Main: public static void main(String [] args){} -> kann aufgerufen werden, ohne davor ein Objekt erzeugt zu haben
 aber auch Variablen können static sein. 
6. Wozu dient die Vererbung?
 * Ich kann eine Super Klasse anlegen, meine Sub Klassen erben dann die Eigenschaften der Super Klasse
 zB.: Überklasse Auto: ein Auto besteht immer aus: *wheels* und *motor* alle meine Subklassen (zB. verschiedene
 Antriebsmethoden) erben dann die Atributte *motor* und *wheels*
7. Kann in Java von mehreren Klassen geerbt werden? Wenn ja wie?
 * Nein!
8. Welche Vererbungshierarchien kennst du? (Ein Bild reicht aus)
  * siehe Bild
9. Was beudeted Casten und wie ist die Syntax in Java dafür?
  * beim Casten soll ein Datentyp in einen anderen umgewandelt werden
10. Was ist der Unterschied zwischen explizieten und implizieten Typecasting?
 * 
11. Erkläre die folgenden Schlüsselwörter: `super`, `this`
 * 
12. Für was dient der `instanceof` Operator. Gib ein sinnvolles Beispiel.
 * 
 ---
 Eclipse bietet auch Markdown unterstützung inklusive Preview. Für die Verwendung muss kein Plugin installiert werden.
