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

# Licht

## Reflexion und Brechung

<iframe src="https://www.geogebra.org/m/j9hcvxk8?embed" width="800" height="600" allowfullscreen style="border: 1px solid #e4e4e4;border-radius: 4px;" frameborder="0"></iframe>

## Totalreflexion

Totalreflexion beschreibt den Effekt, dass der Lichtstrahl zu 100% an einer Grenzfläche reflektiert wird. Lichtbrechung findet nicht statt.

Bedingungen: 

 - Übergang von optisch dichtem zu optisch dünnem Medium

 - Einfallswinkel $\alpha$ überschreitet den Grenzwinkel

{{1}}
**************
<H2>Anwendungsbeispiele Totalreflexion</H2>

![AnwTot1](https://diversewolken.ddns.net/nextcloud/index.php/s/aAr6WdmSty8bRf5/download) 
![AnwTot2](https://diversewolken.ddns.net/nextcloud/index.php/s/ZKxeDQGMGMCKESz/download) 
![AnwTot3](https://diversewolken.ddns.net/nextcloud/index.php/s/mZcbKjoZ6PnAsgg/download)

**************

## Wiederholung Wellen

Eigenschaften von Wellen

 - Amplitude $y_0$ oder $ \hat{y} $ 
 - Wellenlänge $\lambda$
 - Frequenz $f$
 - Schwingungsdauer $T$

## Simulation Wellen

??[Waves2D](https://www.falstad.com/ripple/)

## Aufgabe Welleneigenschaften

??[Aufgabe](https://diversewolken.ddns.net/nextcloud/index.php/s/TsiXGj5WBYiRnxY/download)

# Licht als elektromagnetische Welle

Bei dem <span style="color:orange">Doppelspaltexperiment</span>  beobachten wir, dass ein Laserstrahl, der auf einen sehr kleinen Doppelspalt (Abstand 0,2mm) fällt, auf einem Schirm ein Beugungsmuster hinterlässt.

![Doppelspalt](https://diversewolken.ddns.net/nextcloud/index.php/s/PWMnf2JX4xiXamx/download)<!-- style="width:60%"-->

{1}{Da Beugung und Interferenz Welleneigenschaften sind, betrachten wir das Licht als <span style="color:orange"> elektromagnetische Welle.</span>}

{2}{Bei einer Lichtwelle schwingt das <span style="color:orange">***elektromagnetische Feld***</span>. Eine Lichtwelle benötigt kein Medium (anders als z.B. Schall[Luft], Wasserwellen[Wasser]) zur Ausbreitung. Das elektromagnetische Feld transportiert die Energie.}

{{3}}
***************
Die Ausbreitungsgeschwindigkeit (Lichtgeschwindigkeit) beträgt

> $c = 300.000 \dfrac{km}{s}$.
***************

{{4}}
***************
Die Wellenlänge der Lichtwelle bestimmt die <span style="color:orange">***Lichtfarbe***</span>.

***************

{{5}}
***************
Es gilt die Wellengleichung:

> $c = \lambda \cdot f$
>
> mit 
>
> $\lambda$ .. Wellenlänge
>
> $f$ .. Frequenz

***************

## Wiederholung: Wellen an Grenzflächen

![Aufgabenblatt_Wellenvorgaenge](https://diversewolken.ddns.net/nextcloud/index.php/s/5aPryoFyJL2H95p/download)

### Lösung 1: Wellen an Grenzflächen

{1}{![Lösung1](https://diversewolken.ddns.net/nextcloud/index.php/s/Po9AN47ixmZ2QiY/download)}

{2}{![Lösung2](https://diversewolken.ddns.net/nextcloud/index.php/s/AfAHmaJdXBXnoBj/download)}

{3}{![Lösung3](https://diversewolken.ddns.net/nextcloud/index.php/s/MAicxxorxMa8LRE/download)}

{4}{![Lösung4](https://diversewolken.ddns.net/nextcloud/index.php/s/qJR2ody2GWeeeWg/download)}


## Beugung und Interferenz am Doppelspalt

<iframe src="https://www.geogebra.org/classic/aptkcsex?embed" width="800" height="600" allowfullscreen style="border: 1px solid #e4e4e4;border-radius: 4px;" frameborder="0"></iframe>

## Beugung und Interferenz am Doppelspalt

<section class="newspaper">

{0-1}{![Doppelspalt1](https://diversewolken.ddns.net/nextcloud/index.php/s/k9B2BRzezjccY9b/download)}
{1-2}{![Doppelspalt2](https://diversewolken.ddns.net/nextcloud/index.php/s/o3ETdEtdpLHAWrN/download)}
{2-3}{![Doppelspalt3](https://diversewolken.ddns.net/nextcloud/index.php/s/Sy7HgjwPbEmNG3B/download)}
{3}{![Doppelspalt3](https://diversewolken.ddns.net/nextcloud/index.php/s/6i39C3mY2YFaZX6/download)}

{{4}}
***************
Für das __erste Beugungsmaximum gilt die Formel__:

> $\dfrac{\lambda}{d} = \dfrac{a}{e}$
***************

{{5}}
***************
__Experiment:__

> d = <input type="number" default="0" min="0" max="10" id="d" size="5"> m $ \hspace{0.5cm}$ a = <input type="number" default="0" min="0" max="10" id="a" size="5"> m $\hspace{0.5cm}$ e = <input type="number" default="0" min="0" max="10" id="e" size="5">m />
***************

{{6}}
***************
__Wellenlänge des Lichts berechnen:__

> $\lambda = \dfrac{a \cdot d}{e} = $
<script input="button">

    let d = document.getElementById("d").value;
    let a = document.getElementById("a").value;
    let e = document.getElementById("e").value;

    a*d*e
</script>
m




***************

</section>


{{8}}
***************

<iframe src="https://www.geogebra.org/classic/b79yafcu?embed" width="800" height="600" allowfullscreen style="border: 1px solid #e4e4e4;border-radius: 4px;" frameborder="0"></iframe>

***************

# Kurzprotokoll: Wellenlängenbestimmung am Beugungsgitter

__Aufgabe:__ Bestimme die Wellenlänge $\lambda$ für zwei Laserfarben mit Hilfe eines Beugungsgitters. 

__Material:__ Optische Schiene, Laser, Doppelspalt, Schirm

<section class="newspaper">

__Messwerte:__ Farbe: 

- Abstand Gitter-Schirm $e$ = ...

- Gitterkonstante $d$ = 0,0125 mm = 12,5µm

- Abstand zweier Beugungsmaxima $a_1$ = ..

__Berechnung__

    - Wellenlänge $\lambda_1$ = ...

__Messwerte:__ Farbe: 

- Abstand Gitter-Schirm $e$ = ...

- Gitterkonstante $d$ = 0,0125 mm = 12,5µm

- Abstand zweier Beugungsmaxima $a_2$ = ..

__Berechnung__

- Wellenlänge $\lambda_2$ = ...

</section>

{{1}}
*************
__Mögliche Verbesserungen der Genauigkeit:__

- Vergrößeren Abstand Gitter-Schirm

- Mehr als ein Beugungsmaximum verwenden

- feineres Gitter verwenden

*************

# Reflexion an der Gitterstruktur einer CD-Rom

<section class="newspaper">

{0-1}{![CD-Struktur](https://wkdiscpress.de/assets/components/phpthumbof/cache/abb-5-data-disk-bg.a94fc4dc03f576410f46570ef2d67a18.jpg.webp)}
{1-2}{![Doppelspalt1](https://diversewolken.ddns.net/nextcloud/index.php/s/k9B2BRzezjccY9b/download)}
{2-3}{![Doppelspalt2](https://diversewolken.ddns.net/nextcloud/index.php/s/o3ETdEtdpLHAWrN/download)}
{3-4}{![Doppelspalt3](https://diversewolken.ddns.net/nextcloud/index.php/s/Sy7HgjwPbEmNG3B/download)}
{4-5}{![Doppelspalt3](https://diversewolken.ddns.net/nextcloud/index.php/s/6i39C3mY2YFaZX6/download)}
{5}{![Doppelspalt3](https://diversewolken.ddns.net/nextcloud/index.php/s/cXQ3BBZRACmen8n/download)}

__Beschreibung:__<br>
Auf einer handelsüblichen CD-Rom sind die gespeicherten Daten in eine periodische Struktur (Spuren) gepresst. Diese Struktur ist einem Beugungsgitter sehr ähnlich, d.h. es es existiert eine __Gitterkonstante d (gennant Spurabstand)__. Richtet man einen Laserstrahl auf die CD, kann man in der Relfexion auf einem Schirm ein Beugungsmuster erkennen. 

<span style="color:blue">__Aufgabenstellung:__<br> Bestimme mit Hilfe der Reflexion eines Laserstrahls an einer CD den Spurabstand d (d.h. die Gitterkonstante). Fertige dazu ein Protokoll an (ein Protokoll pro Gruppe [2 Personen])</span>


{{6}}
*************
<span style="color:orange">__Achtung:__<br> Bei diesem Versuch muss die korrekte Trigonometrie betrachtet werden. D.h. </span>
*************

{{7}}
*************
<span style="color:orange"> 
> $\tan(\alpha) = \dfrac{a}{e} \hspace{1cm}$ und $\hspace{1cm} \sin(\alpha) = \dfrac{\lambda}{d}$
</span>
*************


</section>

{{8}}
***Hinweise: Der Laserstahl soll durch eine gelochte Pappschablone auf die CD gerichtet werden. Die Reflexion und damit das Beugungsmuster sind auf der Schablone zu erkennen. Durch Vermessen der Abstände der Beugungsmaxima und des Abstands zwischen CD und Schablone lässt sich mit Hilfe der Formeln der Spurabstand d bestimmen.***

# Test

<script input="number" value="1" output="d">
let d = @input
"d = " + d + "m"
</script>

<script input="number" value="1" output="a">
"a = @input"
</script>

<script>
@input(`a`)
</script>

# Test-Multiply

__Experiment:__

> d = <input type="number" default="0" min="0" max="10" id="d" size="5"> m $ \hspace{0.5cm}$ a = <input type="number" default="0" min="0" max="10" id="a" size="5"> m $\hspace{0.5cm}$ e = <input type="number" default="0" min="0" max="10" id="e" size="5">m

$\lambda = $
<script input="button">

    let d = document.getElementById("d").value;
    let a = document.getElementById("a").value;
    let e = document.getElementById("e").value;

    a*d*e
</script>
m


