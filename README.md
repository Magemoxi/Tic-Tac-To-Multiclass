Tic-Tac-To-Multiclass

V.3 3 Versuch 3 mehere Klassen zu benutzen, unfertig, verbuggt und unschön. 

Klasse 1 ruft Klasse 2 auf, diese KLasse 3 usw. dabei wurde jedesmal eine neue Instanz erzeugt.
Problem war das die letze Klasse nicht die erste aufrufen konnte ohne diese neu zu erzeugen und
somit alle Werte Resetet waren.

Ich habe jetz eine einer Erzeuger Klasse ersetllt, welche einmal alle Klassen neu erzeugt und entsprechend 
Methoden dafür geschrieben, welche ich aus den Restlichen Klassen aufrufen kann.

Jedoch bekomm ich wenn ich das Spiel mit der 1 im Hauptmenü starte in der Klasse Erzeuger eine 
System.StackOverflowException wo ich die Klasse  Spielfeld erzeuge.

Zeile: 13   Spielfeld spielfeld = new Spielfeld("x");
