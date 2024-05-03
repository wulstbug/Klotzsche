<!--
author: Christian Golnik

language: de

@style
.lia-effect__circle {
    display: none !important;
}

@media (min-width: 600px) {
    .newspaper {
        column-count: 2;
        column-gap: 40px;
        column-rule: 1px solid lightblue;
    }
}

h1, h2, h3, h4, h5, h6 {
  column-span: all;
}

.cb {
    break-before: column;
}
@end

mode: Presentation

@onload
window.LIA.settings.font_size = 2
@end

-->

# Ohmsches Gesetz

> Für einen <span style="color:orange">ohmschen Widerstand</span> sind abfallende Spannung U und fließende Stromstärke I direkt proportional zueinander, unter der Bedingung, dass die Temperatur konstant ist.

_Hinweis: Jedes elektrische Bauelement besitzt einen Widerstand, aber nicht immer sind Spannung und Stromstärke direkt proportional._

{{1}}
*********************
<span style="color:blue">
Aufgabe: 

- Ermittle mit Hilfe des Cassy-Messgerätes die U-I-Kennlinie eines ohmschen Widerstandes und einer Glühlampe (U 0..10 V, Schrittweite 1V). 
- Übertrage die Messkurven in ein Diagramm
- Diskutiere den Zusammenhang von Glühlampe und dem ohmschen Gesetz

</span>
*********************

{2}{__U-I-Kennlinien verschiedener elektrischer Bauelemente__:}

<section class="newspaper">

{{2}}
*********************
Messwerte:

| | | |
| | $100\Omega$-Widerstand | Glühlampe|  
| Spannung in V | Stromstärke in mA | Stromstärke in mA |
| 0     |   |   |
| 1     |   |   |
| 2     |   |   |
| ..    |   |   |
| 9     |   |   |
| 10    |   |   |

<p class="cb">Diagramm</p>
*********************

{{3}}
*********************

![Kennlinien](https://diversewolken.ddns.net/nextcloud/index.php/s/msazyCEbW7Tb5ga/download)
*********************

</section>

{{4}}
***************
Merke: Für eine Glühlampe gilt <span style="color:red">das ohmsche Gesetz nicht</span> , da sich mit wachsender Spannung die Temperatur des Glühdrates ändert (er leuchtet). 
***************