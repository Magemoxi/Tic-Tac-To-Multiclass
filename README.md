Tic-Tac-To-Multiclass

V.5 Es leuft einigermassen aber nicht so wie ich es deviniert habe.

Ich habe es geschaft den else Teil einer if Verzweigung auszuführen, ohne die if if Bedinung erfüllt zuhaben. 


Klasse Ergebnis:                    Die Variable spieRunde ist wie im Bild derzeit 2 sodas der gesamte if Teil übersprungen werden muss. Wie im Bild "Bild zur README.md .png" zu sehen, geschieht dies nicht...


            if (spielRunde == 9)               // 10 weil das ergebnis ja zuerst aufgerufen wird und dann erst der spieler ! weil sonst die feldeingabe wartet und alle felder besetz sind falls keienr gewinne kann
            {
                Console.WriteLine("Niemand hat das Spiel von euch beiden gewonnen. :-(");
                Console.ReadKey();
                output = "Das Spiel ist zu ende";        // Schleifenabbruch in der Klasse erzeuge
            } 
            else // falls noch spielfelder offen sind, kann weitergespielt werden
            {
                Console.WriteLine("FEHLER DAS DARF NICHT SEIN");
                output = "Es wird noch gespielt";       // muss hier stehen, da im erzeuger den output einliest um zu wissen, ob das spiel beendet ist oder nciht
                Console.ReadLine();
            }
