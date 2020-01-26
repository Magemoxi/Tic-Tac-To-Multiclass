Tic-Tac-To-Multiclass

V.5 Es leuft einigermassen aber nicht so wie ich es deviniert habe.

Klasse Ergebnis:

Das Spielfeld hat 9 Felder. Erst wenn das 9nte Feld belegt ist, soll das Programm in die Schleife gehen.
(wieOftGespieltWurde == 9)

Wenn man schon vorher gewonnen hat, wird die Schleife nicht ausgeführt was richtig ist.
Aber der else Teil der Schleife wird trozdem ausgeführt !! 
Was nicht sein kann, da die Schleife niemals aufgerufen wird ..... -.-  




            if (wieOftGespieltWurde == 9)               // 10 weil das ergebnis ja zuerst aufgerufen wird und dann erst der spieler ! weil sonst die feldeingabe wartet und alle felder besetz sind falls keienr gewinne kann
            {
                Console.WriteLine("Niemand hat das Spiel von euch beiden gewonnen. :-(");
                Console.ReadKey();
                output = "Das Spiel ist zu ende";        // Schleifenabbruch in der Klasse erzeuge
                Console.WriteLine("verloren. out ->> " + output);

            } else // falls noch spielfelder offen sind, kann weitergespielt werden
            {
                output = "Es w22222222222222222222";       // muss hier stehen, da im erzeuger den output einliest um zu wissen, ob das spiel beendet ist oder nciht
            }
