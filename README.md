Tic-Tac-To-Multiclass

V.4 Vierter Versuch mehere Klassen zu benutzen.

Als ich das Spiel in einer Klasse gestopft habe, hat jede Methode sich selbst oder entsprechend andere aufgerufen.
Das führte zu viel Abhänigkeit und wurde komplizierter wenn man es erweitern möchte wie z.B. den Bot Modus.

Bin nun zu dem Schluss gekommen eine Erzeuger Klasse zu erstellen, die jede Klasse einmal erzeugt und alle 
anderen Klassen aufruft, Parameter entgegennimmt und weiterleitet.

Das mit den get & Set Methoden ist viel zu unübersichtlich (ja es geht einfacher aber bin noch Java gewohnt) scheint aber besser zu funktionieren.

Habe bis jetz auf Schleifen verzichtet und dennoch findet eine eine Rekursion statt ....
