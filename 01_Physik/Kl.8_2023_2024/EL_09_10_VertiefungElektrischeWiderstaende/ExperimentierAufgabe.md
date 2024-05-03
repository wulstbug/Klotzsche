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

# Gliederung

- TÜ Vorbereitung LK

- Experiment Ohmsches Gesetz


## TÜ

<div style="float: right; height: 100px; position: relative; width: 200px; overflow: hidden; top: -80px;"> <div style="overflow: hidden;"> </div> <div> <iframe width="200" height="90" src="https://webuhr.de/embed/timer/#countdown=00:15:00&showbuttons=0&theme=0&ampm=0&sound=xylophone" frameborder="0" allowfullscreen></iframe> </div> </div>

<section class="newspaper">

1. Ergänze folgende Tabelle
| | |
| U   | I   | R   |
| 60 V     | 0,7 A     | <span style="color:orange">{1}{85,7$\Omega$}</span>     |
| 18 V     | <span style="color:orange">{2}{0,036 A = 36 mA}</span>    | 0,5 $k\Omega$     |
| <span style="color:orange">{3}{12,5 V}</span>    | 50 mA    | 250 $\Omega$     |

2. Berechne den Gesamtwiderstand aus einer Parallelschaltung von zwei Widerständen $R_1 = 2 k\Omega$ und $R_2 = 3 k\Omega$

{4}{$\hspace{1cm}$ <span style="color:orange"> $R_{ges} = \dfrac{2k\Omega \cdot 3k\Omega}{2k\Omega+3k\Omega} = 1,2 k\Omega$</span>}

3.1. Bei einer Reihenschaltung ist der Gesamtwiderstand ......... {5}{<span style="color:orange">größer</span>} als jeder einzelne Widerstand.

3.2. Bei einer Parallelschaltung ist der Gesamtwiderstand ......... {6}{<span style="color:orange">kleiner</span>} als jeder einzelne Widerstand.

4. Zeichne eine Schaltung bei welcher ein blauer (<span style="color:blue">$1k\Omega$</span> ) und ein grüner Widerstand (<span style="color:darkgreen">$5k\Omega$</span> ) zueinander in Reihe geschaltet sind und diese Reihenschaltung ist parallel zu einem roten Wiederstand (<span style="color:red">$2k\Omega$</span> ) geschaltet.

{7}{![Loesung_4](https://diversewolken.ddns.net/nextcloud/index.php/s/jYSzH6C2Nz6Z6kJ/download)}

5. Berechne den Gesamtwiderstand zu Aufgabe 4.

{8}{$\hspace{1cm}$ <span style="color:orange">$R_{ges} = \dfrac{(1+5) \cdot 2}{(1+5)+2} k\Omega = 1,5 k\Omega$</span>}

<p class="cb"> 6. Folgendes Widerstandsnetzwerk ist gegeben. </p>

![Netzwerk](https://diversewolken.ddns.net/nextcloud/index.php/s/pMxqnKJ7Tj6dWBX/download)<!-- style="width:80%"-->

6. 1. Erzeuge durch Öffnen und Schließen von (S1-S6) einen Gesamtwiderstand von 
| | |
| $100\Omega$ | $300\Omega$ |  $250 \Omega$ |
| {9}{<span style="color:orange">S1, S6</span>} | {10}{<span style="color:orange">S1, S5</span>} | {11}{<span style="color:orange">S1, S4, S5</span>} |

6. 2. Bestimme den größten Widerstand, welcher mit diesem Netzwerk eingestellt werden kann.

{12}{<span style="color:orange">$1400\Omega$ mit S3, S4</span>}


{{13}}
*************
__Simulation__

https://tinyurl.com/yrp2fely
*************

</section>

## Ohmsches Gesetz

> Für einen <span style="color:orange">ohmschen Widerstand</span> sind abfallende Spannung U und fließende Stromstärke I direkt proportional zueinander, unter der Bedingung, dass die Temperatur konstant ist.

_Hinweis: Jedes elektrische Bauelement besitzt einen elektrischen Widerstand R, aber nicht immer sind Spannung und Stromstärke direkt proportional._

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