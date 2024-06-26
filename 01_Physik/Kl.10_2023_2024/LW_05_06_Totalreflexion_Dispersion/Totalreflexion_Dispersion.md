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

> d = <input type="number" default="0" min="0" max="10" id="d" size="5"> m $ \hspace{0.5cm}$ a = <input type="number" default="0" min="0" max="10" id="a" size="5"> m $\hspace{0.5cm}$ e = <input type="number" default="0" min="0" max="10" id="e" size="5">m
***************

{{6}}
***************
__Wellenlänge des Lichts berechnen:__

> $\lambda = \dfrac{a \cdot d}{e} = $ <script input="button">
    let d = document.getElementById("d").value;
    let a = document.getElementById("a").value;
    let e = document.getElementById("e").value;
    a*d*e
</script> m
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

## Ablauf

- Klassenfahrt Infos

- 20min Selbstständiges bearbeiten der Aufgaben (Stillarbeit)

- 15min Vergleichen der Lösungen (mit Partner), Probleme diskutieren

- 20min Klassengespräch, Fragen, einzelne Aufgaben

## Aufgaben zum Thema Licht als Welle

__1. Grundlagen der Wellen__

Erkläre den Unterschied zwischen longitudinalen und transversalen Wellen. 
    
    Notiere die Art, zu welcher das Licht gehört das Licht und warum?

__2. Welleneigenschaften__

Licht breitet sich in Form von Wellen aus. 

- a) Nenne die grundlegenden Eigenschaften (physikalische Größen) von Wellen.

- b) Notiere eine Gleichung welche den Zusammenhang zwischen diesen Größen darstellt.

__3. Lichtgeschwindigkeit__

Die Lichtgeschwindigkeit im Vakuum beträgt etwa $3 \cdot 10^8 \, \text{m/s}$. Berechne die Frequenz von grünem Licht mit einer Wellenlänge von 500 nm (1 nm = $10^{-9} \, \text{m}$).

__4. Brechung und Brechungsindex__

Erkläre das Phänomen der Lichtbrechung. Wie verändert sich die Richtung eines Lichtstrahls, wenn er von Luft in Wasser übergeht? Geh auf die Lichtgeschwindigkeit in beiden Medien ein. Nenne das Brechungsgesetz.

__5. Beugung__

Beschreibe, was passiert, wenn Licht auf einen sehr kleinen Spalt trifft, dessen Breite vergleichbar mit der Wellenlänge des Lichtes ist. Was versteht man unter Beugung?

__6. Interferenz__

Zwei kohärente Lichtquellen erzeugen auf einem Schirm ein Interferenzmuster. Zeichne ein mögliches Interferenzmuster. Erkläre die Begriffe konstruktive und destruktive Interferenz.


__7. Doppelspaltexperiment__

Beschreibe das Doppelspaltexperiment. Beschreibe, wie man mit diesem Experiment die Wellennatur des Lichts begründen kann?

__8. Berechnungen des Spurabstands einer DVD__

Auf einer DVD sind die Daten in sehr kleinen periodischen Strukturen gespeichert. Diese Gitter-Struktur der DVD wird mit einem blauen Laser der Wellenlänge $\lambda=450\,nm$ beleuchtet. Auf einem Schirm, welche $10\,cm$ von der DVD entfernt ist, wird das erste Beugungsmaximum im Abstand von $7,6\,cm$ der direkten Reflexion (Maximum 0.ter Ordnung) beobachtet. Berechne den Spurabstand (d.h. die Gitterkonstante) der DVD in der Einheit $\mu m$.

- <details> <summary>Hinweis 1</summary> <p>![Doppelspalt3](https://diversewolken.ddns.net/nextcloud/index.php/s/cXQ3BBZRACmen8n/download)</p></details> 

- <details> <summary>Hinweis 2</summary> <p>geg.: $\lambda = 450\,nm$, a = 7,6 cm, e = 10 cm</p></details> 

## Lösungen zum Thema Licht als Welle


### Lösungen

__1. Grundlagen der Wellen__

Erkläre den Unterschied zwischen longitudinalen und transversalen Wellen. 
    
    Notiere die Art, zu welcher das Licht gehört das Licht und warum?

    {1}{<span style="color:orange">Licht ist eine Transversalwelle. Hier schwingt das elektromagnetische und das elektrische Feld senkrecht zur Ausbreitungsrichtung.</span>}

__2. Welleneigenschaften__

Licht breitet sich in Form von Wellen aus. 
    
    a) Nenne die grundlegenden Eigenschaften (physikalische Größen) von Wellen.

    {2}{<span style="color:orange">Amplitude, Wellenlänge $\lambda$, Frequenz $f$, Ausbreitungsgeschwindigkeit $c$ </span>}

    b) Notiere eine Gleichung welche den Zusammenhang zwischen diesen Größen darstellt.

    {3}{<span style="color:orange">$c = \lambda \cdot f$</span>}

__3. Lichtgeschwindigkeit__

Die Lichtgeschwindigkeit im Vakuum beträgt etwa $3 \cdot 10^8 \, \text{m/s}$. Berechne die Frequenz von grünem Licht mit einer Wellenlänge von 500 nm (1 nm = $10^{-9} \, \text{m}$).

    {4}{<span style="color:orange">$f=\dfrac{c}{\lambda}=\dfrac{3\cdot10^8 \frac{m}{s}}{500\cdot10^-9\,m}=6\cdot10^{14} Hz$</span>}

__4. Brechung und Brechungsindex__

Erkläre das Phänomen der Lichtbrechung. Wie verändert sich die Richtung eines Lichtstrahls, wenn er von Luft in Wasser übergeht? Geh auf die Lichtgeschwindigkeit in beiden Medien ein. Nenne das Brechungsgesetz.

    {5}{<span style="color:orange">Lichtbrechung: Der Lichtstrahl verändert beim Übergang von einem Medium in ein anderes Medium seine Ausbreitungsrichtung. Beim Übergang von Luft zu Wasser erhöht sich die optische Dichte. Im Wasser ist die Lichtgeschwindigkeit kleiner als in Luft ($c_{Luft}>c_{Wasser}$).</span>}

    {6}{<span style="color:orange">$\dfrac{sin(\alpha)}{\sin(\beta)} = \dfrac{c_1}{c_2}$</span>}

__5. Beugung__

Beschreibe, was passiert, wenn Licht auf einen sehr kleinen Spalt trifft, dessen Breite vergleichbar mit der Wellenlänge des Lichtes ist. Was versteht man unter Beugung?

    {7}{<span style="color:orange">Die Lichtwelle breitet sich hinter dem Spalt als Kugelwelle aus. Diesen Effekt bezeichnet man als Beugung.</span>}

__6. Interferenz__

Zwei kohärente Lichtquellen erzeugen auf einem Schirm ein Interferenzmuster. Zeichne ein mögliches Interferenzmuster. Erkläre die Begriffe konstruktive und destruktive Interferenz.

    {8}{<span style="color:orange">Interferenzmuster mit Maxima und Minima zeichnen. (siehe Hefter).</span>}

    {9}{<span style="color:orange">Konstruktive Interferenz ist die gegenseitige Verstärkung zweier Lichtwellen. Dabei sind die Maxima jeweils übereinander. Bei der destruktiven Interferenz löschen sich Minima und Maxima der beiden Wellen gegenseitig aus.</span>}

__7. Doppelspaltexperiment__

Beschreibe das Doppelspaltexperiment. Beschreibe, wie man mit diesem Experiment die Wellennatur des Lichts begründen kann?

    {10}{<span style="color:orange">Hinter einem Doppelspalt erkennt man ein Interferenzmuster auf einem Schirm mit Minima und Maxima. Dabei treten Maxima auch an Stellen auf, welche nach dem Lichtstrahl-Modell kein Licht erreichen kann. Das Interferenzmuster kann mit der Welleneigenschaft und den Effekten von __Beugung__ und __Interferenz__ erklärt werden.</span>}

__8. Berechnungen an einer DVD__

Auf einer DVD sind die Daten in sehr kleinen periodischen Strukturen gespeichert. Diese Gitter-Struktur der DVD wird mit einem blauen Laser der Wellenlänge $\lambda=450\,nm$ beleuchtet. Auf einem Schirm, welche $10\,cm$ von der DVD entfernt ist, wird das erste Beugungsmaximum im Abstand von $7,6\,cm$ der direkten Reflexion (Maximum 0.ter Ordnung) beobachtet. Berechne den Spurabstand (d.h. die Gitterkonstante) der DVD in der Einheit $\mu m$.

- <details> <summary>Hinweis 1</summary> <p>![Doppelspalt3](https://diversewolken.ddns.net/nextcloud/index.php/s/cXQ3BBZRACmen8n/download)</p></details> 

- <details> <summary>Hinweis 2</summary> <p>geg.: $\lambda = 450\,nm$, a = 7,6 cm, e = 10 cm</p></details> 

{{11}}
**********
<span style="color:orange">
Lsg.:

-   $\tan(\alpha) = \dfrac{a}{e}$

-   $\alpha = \tan^{-1}(\dfrac{a}{e}) = 37,23^\circ$

- $\sin(\alpha) = \dfrac{\lambda}{d}$ -> $d = \dfrac{\lambda}{\sin(\alpha)}=7,43\cdot10^-7\,m=0,740\,\mu m$

</span>
*********
