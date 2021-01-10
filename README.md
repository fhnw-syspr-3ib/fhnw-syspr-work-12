# System-Programmierung
## Hands-on zu Lektion 12
Für Slides und Code Beispiele, siehe [Lektion 12](../../../fhnw-syspr/blob/master/12/README.md)

> *Achtung: Arbeiten Sie nicht direkt auf diesem Repository.*<br/>
> *[Erstellen Sie eine persönliche Kopie, mit diesem GitHub Classroom Link](https://classroom.github.com/a/gngE3Gkg).*

### a) *curses* Library, 15'
* Kompilieren und testen Sie die Beispielprogramme:<pre>
    $ sudo apt-get install libncurses5-dev
    $ gcc -o NAME NAME.c -lcurses</pre>
* Schreiben Sie ein eigenes Programm mit *ncurses*.
* Mehr dazu in diesen Tutorials zur *curses* Bibliothek:<br/>http://heather.cs.ucdavis.edu/~matloff/UnixAndC/CLanguage/Curses.pdf und [Games mit ncurses](https://www.viget.com/articles/game-programming-in-c-with-the-ncurses-library/).

### b) Kilo.c Revisited, 15'
* Analysieren Sie den Source Code dieses Programms: https://github.com/antirez/kilo/blob/master/kilo.c
* Welche Terminal-spezifischen Calls werden im Code verwendet und wozu?
