# Grep-Tool

## Einstieg

Musstest du jemals irgendwas in einer Datei finden? Wenn nicht, musst du dies wahrscheinlich irgendwann machen. Hier kommt Grep ins Spiel. Grep kann aus Dateien einzelne Wörter und Buchstaben finden, wie man das macht und wo man es benutzen kann, werdet ihr hier erfahren.

## Tech Beschreibung

Global regular expression print, kurz gesagt Grep. ist ein Tool um Zeichen Muster zu finden. Dies kann es auf verschiedene Arten machen. man kann in die konsole “grep hello text.txt” dann kriegt man alle Zeilen in text.txt die hello darin haben. Mit Grep kann man auch mehr als nur eine Datei durchsuchen. Dies macht man wenn man einen `*.` vor dem Namen des Ordner machen und damit durchsucht Grep alle Dateien in den Ordner und sagt auch, welche Zeile von welcher Datei ist. Man kann es auch spezifischer machen, dass es nur gewisse Sachen zurück gibt. Man kann zum Beispiel sagen, es soll nur das ganze Wort suchen, also wenn hell gesucht wird, das auch nur die Zeilen mit dem Wort hell zurückgibt und nicht Zeilen, in denen hello steht. Dies kann man mit `-w` machen und es gibt noch viel mehr. Etwas, was auch viel mit Grep benutzt wird, ist ein Regex. Regex kann gebraucht werden, um etwas Ungefähres zu suchen, von dem man noch nicht ganz weiss wie es heisst. Kurz gesagt, wenn man etwas in Dateien suchen muss, ist Grep sehr gut für dies ausgestattet.

## Beispiele

1. `grep "Fehler" logfile.txt`  
   => Sucht nach dem Wort in angezeigter Datei und gibt die Zeilen aus

2. `grep -i "warnung" logfile.txt`  
   => Gross- und Kleinschreibung ignoriere beim Suchen des Worts in dem File

3. `grep -r "TODO:"`  
   => Durchsucht alle Verzeichnisse und Unterverzeichnisse für dem Wort

4. `grep -c "Fehler" logfile.txt`  
   => Gibt die Anzahl aller Zeilen die diesen Wort enthalten

5. `grep -v "DEBUG" logfile.txt`  
   => Zeigt alle Zeilen ohne dem angezeigten Wort

## Referenzen

1. [https://www.youtube.com/watch?v=crFZOrlqao](https://www.youtube.com/watch?v=crFZOrlqao)  
   Hier ist ein gutes YouTube-Video, das die verschiedenen Dinge erklärt, die man mit Grep machen kann.

2. [https://www.powergrep.com/](https://www.powergrep.com/)  
   Das ist eine coole kleine Seite, auf der du nachschauen kannst, wie man Grep verwenden kann oder wie manche Leute darüber denken.
