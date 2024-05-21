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


# Funktionale Zusammenhänge

## Wiederholung 1. Wachstumsprozesse zuordnen

<iframe src="https://learningapps.org/watch?v=pepzvz6sa24" style="border:0px;width:100%;height:500px" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"></iframe>

## Wiederholung 2. Funktionen zuordnen

Ordne die folgenden Funktionen den zugehörigen Funktionsgraphen zu.

??[FunktionsgraphenZuordnen](https://learningapps.org/2546006)

## Wiederholung Funktion

Eine Funktion $y = f(x)$ ordnet jedem Element x des Definitionsbereiches $\mathbb{D_f}$ einen Wert y des Wertebereiches $\mathbb{W_f}$ zu.

<span style="color:blue">
    Zum Beispiel: $ f(x) = 3^x$

    Dem Wert $ x = 2$ wird $y = 3^2 = 9$ zugeordnet.

 Hier: 

 Definitionsbereich $\mathbb{D_f} = \R$ $\hspace{0.5cm}$(_Hinweis: $\mathbb{D_f}$ ist die Menge aller Zahlen $x$, für die $f(x)$ definiert ist._)

 Wertebereich $\mathbb{W_f} = \R^{>0}$ $\hspace{0.5cm}$(_Hinweis: $\mathbb{W_f}$ ist die Menge aller Zahlen $y$, die die $y=f(x)$ annehmen kann._)

</span>

{{1}}
*************

<H2>Umkehrfunktion</H2>

Die <span style="color:orange">***Umkehrfunktion zu f***</span> ist genau die Funktion $f^{-1}$ für die gilt:

> <span style="color:orange">Wenn $f(x) = y$ dann ist $f^{-1}(y) = x$</span>
*************

<span style="color:blue">

{{2}}
*************

Am Beispiel: $f(x) = 3^x$

*************

{{3}}
*************
1. Notiere die Funktion

> $y = 3^x$
*************

{{4}}
*************
2. Vertausche x und y, d.h.

> $ x = 3^y $
*************

{{5}}
*************
3. Stelle die Gleichung nach y um

> $ y = \log_3(x)$ 

> => Umkehrfunktion: $f^{-1}(x) = \log_3(x)$
*************

</span>

## Aufgaben

1. Bilde folgende Umkehrfunktionen. Gib (sofern nicht gegeben) jeweils den maximal möglichen Definitionsbereich $\mathbb{D_f}$ und den Wertebereich $\mathbb{W_f} $ der Funktion $f(x)$ an.

$\hspace{1cm}$a) $f(x) = 2 \cdot x$

{1}{$\hspace{1cm}$<span style="color:orange">$\mathbb{D_f}=\R$ ; $\mathbb{W_f} = \R $ ; $f^{-1}(x) = \dfrac{1}{2}\cdot x$</span>}

$\hspace{1cm}$b) $f(x) = x^2 + 2$ mit $\mathbb{D_f} = \R^{\geq0}$

{2}{$\hspace{1cm}$<span style="color:orange">$\mathbb{W_f} = \R^{\geq2} $ ; $f^{-1}(x) = \sqrt{x-2}$</span>}

$\hspace{1cm}$c) $f(x) = \Big(\dfrac{1}{3}\Big)^x$

{3}{$\hspace{1cm}$<span style="color:orange">$\mathbb{D_f}=\R$ ; $\mathbb{W_f} = \R^{>0} $ ; $f^{-1}(x) = \log_\frac{1}{3}(x)$</span>}

$\hspace{1cm}$d) $ f(x) = \log_4(x) $

{4}{$\hspace{1cm}$<span style="color:orange">$\mathbb{D_f}=\R^{>0}$ ; $\mathbb{W_f} = \R $ ; $f^{-1}(x) = 4^x$</span>}

$\hspace{1cm}$e*) $ f(x) = e^{2x+3} - \dfrac{1}{2} $

{5}{$\hspace{1cm}$<span style="color:orange">$\mathbb{D_f}=\R$ ; $\mathbb{W_f} = \R^{>\frac{1}{2}} $ ; $f^{-1}(x) = \dfrac{\ln(x+\frac{1}{2})-3}{2}$ $\hspace{0.5cm}$ (_Hinweis: $\ln = \log_e$_)</span>}

$\hspace{1cm}$f*) $ f(x) = 2 \Big( e^{\frac{x}{3}-4} \Big)^3 -1 $

{6}{$\hspace{1cm}$<span style="color:orange">$\mathbb{D_f}=\R$ ; $\mathbb{W_f} = \R$ ; $f^{-1}(x) = 12 + 3 \ln\Big( \sqrt[3]{\frac{x+1}{2}} \Big)$ $\hspace{0.5cm}$</span>}

2. Überprüfe zu den Umkehrfunktionen $f^{-1}$ aus den Aufgaben 1. a) - f) die Definitionsbereiche $\mathbb{D}_{f^{-1}}$ und die Wertebereiche $\mathbb{W}_{f^{-1}}$ und vergleiche diese jeweils mit $\mathbb{D}_{f}$ bzw. $\mathbb{W}_{f}$


## Eigenschaft der Umkehrfunktion

<span style="color:red">
> Existiert zu einer Funktion $f(x)$ die Umkehrfunktion $f^{-1}(x)$ so sind Definitionsbereich $\mathbb{D}$ und Wertebereich jeweils vertauscht, d.h. $\mathbb{D_f}=\mathbb{W}_{f^{-1}}$ und $\mathbb{W_f}=\mathbb{D}_{f^{-1}}$. 
</span>

{{1}}
***********
<iframe src="https://learningapps.org/watch?v=pyw56qt4324" style="border:0px;width:100%;height:500px" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"></iframe>
***********

## Eigenschaften von Funktionen (Allgemein)

Wiederholung:

{{1}}
***********
> <span style="color:red">Definitionsbereich $\mathbb{D_f}$</span> ist die Menge aller Zahlen $x$, für die $f(x)$ definiert ist.
***********

{{2}}
***********
> <span style="color:red">Wertebereich $\mathbb{W_f}$</span> ist die Menge aller Zahlen $y$, die die $y=f(x)$ annehmen kann
***********

{{3}}
***********
> <span style="color:red">Montonie:</span>

>> Eine Funktion heißt <span style="color:blue">***streng monoton wachsend***</span>, wenn bei größer werdendem Argument x der Funktionswert f(x) ebenfalls größer wird, d.h. wenn $x_1 < x2$ => $f(x_1) < f(x_2)$

>> Beispiele: ![streng_monoton_wachsend](https://diversewolken.ddns.net/nextcloud/index.php/s/86ppsBmXA4gZzXr/download)

***********


{{4}}
***********
>> Eine Funktion heißt <span style="color:orange">***streng monoton fallend***</span>, wenn bei größer werdendem Argument x der Funktionswert f(x) kleiner wird, d.h. wenn $x_1 < x2$ => $f(x_1) > f(x_2)$

>> Beispiele: ![streng_monoton_fallend](https://diversewolken.ddns.net/nextcloud/index.php/s/BqyPBHtRxppAmgz/download)

***********

{{5}}
***********
>> <span style="color:blue">***monton wachsend***</span>: $\forall x_1,x_2 \in \mathbb{D_f}: x_1 < x_2 ⇒ f(x_1) \leq f(x_2)$

>> <span style="color:orange">***monton fallend***</span>: $\forall x_1,x_2 \in \mathbb{D_f}: x_1 < x_2 ⇒ f(x_1) \geq f(x_2)$
***********

{{6}}
***********
>> <span style="color:red">Nullstellen:</span>  Schnittpunkte mit der x-Achse, d.h. $f(x) = 0$.
***********

{{7}}
***********
>> Extremstellen: Ein Maximum oder Minimum der Funktion.
***********

## Aufgaben Learningsapps

<H4> Ziel: Probiere verschiedene Learning-Apps zum Thema "Zuordnung von Funktionen und Funktionstermen" auf den folgenden Seiten aus. Erstelle dann eine eigene Learning-App.

Nutze folgende Typen von Funktionen:

| | 
| Name der Funktion | Beispielfunktion |
| Lineare Funktionen       | $f(x) = 2x+3$                       |
| Quadratische Funktionen  | $f(x) = 3(x-2)^2$                   |
| Exponentialfunktionen    | $f(x) = \Big(\dfrac{1}{3}\Big)^x+1$ |
| Wurzelfunktion           | $f(x) = \sqrt{(x)+2}$               |
| Hyperbelfunktion         | $f(x) = \dfrac{2}{x} $               |
| Trigonometrische Funktionen         | $f(x) = 2\sin(x) $               |
| Logarithmische Funktionen         | $f(x) = log_3(x) $               |


</H4>

### Beispiele

<iframe src="https://learningapps.org/watch?v=pr54a4yck24" style="border:0px;width:100%;height:500px" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"></iframe>

<H4>
| | |
| Funktionsterm darstellen | App Erstellen |
| > https://geogebra.org/classic | > https://learningapps.org/createApp.php |

<span style="color:blue">***Vergleiche LB S. 148 Beispiel 2 und 3***</span> 

</H4>

### Beispiel Zusatz

??[Funktionsterme3](https://learningapps.org/23796583)

# Funktionenbingo

![FunktionenBingo1](https://diversewolken.ddns.net/nextcloud/index.php/s/FaYzmL7KoHZcsCy/download) 

{1}{![FunktionenBingo2](https://diversewolken.ddns.net/nextcloud/index.php/s/bT9Gd63Mfm8yXrk/download)}

# LearningApps SchülerInnen

??[LearningAppsSuS](https://learningapps.org/watch?v=pw8uj8m8324)

??[Ergebnisse](https://forms.microsoft.com/Pages/AnalysisPage.aspx?AnalyzerToken=8BimoVD8prVnxH3rFqdUgF6wuwXsfE6i&id=OYkUKbuZEE6zqVVLeyuod-N98JNwJnhAr0ZoZo5y2cdUQUE1NFhNTEI5MTEyM1YyWjZRSUFST1VHNy4u)

# Übungen zu Eigenschaften von Funktionen

![ABlatt1](https://diversewolken.ddns.net/nextcloud/index.php/s/sdRY4qYzNpjcAe8/download)
![ABlatt2](https://diversewolken.ddns.net/nextcloud/index.php/s/7yR9GgEbgMtEc8q/download)

# Übungen zur LK

Löse folgende Aufgaben. Lösungen können jeweils aufgeklappt werden

<section class="newspaper">

__Zum selbstständig Üben und Vergleichen__

- LB S. 142 A3 (mind. 3 Bsp.)

    -  <details> <summary>Lsg.142.3</summary> <p>![Lsg_142_3](https://diversewolken.ddns.net/nextcloud/index.php/s/AQsZo3Wn3KaSr6S/download)</p></details> 

- LB S. 142 A6 (a, b, f, g, j)

    -  <details> <summary>Lsg.142.6</summary> <p>![Lsg_142_6](https://diversewolken.ddns.net/nextcloud/index.php/s/cHsxA6KwwFR9wsB/download)</p></details> 

- LB. S. 142 A7

    - <details> <summary>Lsg.142.7</summary> <p>![Lsg_142_7](https://diversewolken.ddns.net/nextcloud/index.php/s/9n5QYPwgMPAqXKX/download)</p></details> 

- LB. S. 143 A11

    - <details> <summary>Lsg.143.11</summary> <p>![Lsg_143_11](https://diversewolken.ddns.net/nextcloud/index.php/s/gP4J9rqjTbowys5/download)</p></details> 

<section class="cb"> __In Partnerarbeit__

- LB. S. 149 A3

- LB. S. 150 A9

- .

- .

- .

- .

</section>

</section>

# Verknüpfung und Verkettung von Funktionen

## Beispiel 1: Fadenpendel

??[SimulationFadenpendel](https://www.physik.gym-wst.de/localhtml/suw/01_pendelsinus/pendelsinus.html)

## Beispiel 2: Federschwinger

<iframe src="https://www.geogebra.org/classic/g5vm3e2r?embed" width="1200" height="800" allowfullscreen style="border: 1px solid #e4e4e4;border-radius: 4px;" frameborder="0"></iframe>

## Verknüfung und Verkettung von Funktionen

<H4>Verknüfung</H4>

Gegeben seien die Funktionen $u(x)$ und $v(x)$. Die __neuen__ Funktionen 

> ${u(x)+v(x)}$ $\hspace{1cm}$ $u(x)-v(x)$ $\hspace{1cm}$ $u(x) \cdot v(x)$ $\hspace{1cm}$ $\dfrac{u(x)}{v(x)}$

heißen __Verknüfpung__ von $u(x)$ und $v(x)$

{{1}}
*************
Beispiele: 

- Quadratische Funktionen: $u(x) = x^2$ und $v(x)=2x$ => $\hspace{1cm}$ $u(x)+v(x)=x^2+2x$
*************

{{2}}
*************
- Trigonometrie: $u(x) = sin(x)$ und $v(x)=cos(x)$  => $\hspace{1cm}$ $ \dfrac{u(x)}{v(x)}=\dfrac{sin(x)}{cos(x)}$ {3}{$=tan(x)$}
*************

{{4}}
*************
- gedämpfte Schwingung: $u(x) = e^{-x}$ und $v(x)=cos(x)$ => $\hspace{1cm}$ $u(x)\cdot v(x) = e^{-x} \cdot cos(x)$
*************

{{5}}
*************
<H4> Verkettung </H4>

Gegeben seien die Funktionen $u(x)$ und $v(x)$. Die __neue__ Funktion

> $u \circ v$ mit $(u \circ v)(x) = u(v(x))$ heißt Verkettung von $u(x)$ und $v(x)$. <br> <br> Dabei wird im Funktionsterm von $u$ jedes $x$ durch $v(x)$ ersetzt.
*************

{{6}}
*************
Beispiele: 

- Wurzelfunktion: $u(x) = \sqrt(x)$ und $v(x)=x+2$ => $\hspace{1cm}$ $u(x)+v(x)=x^2+2x$
*************

# Zeitvertreib

## Milchkannenrätsel

??[Milchkannenrätsel](https://www.walter-fendt.de/html5/mde/threejugsproblem_de.htm)




## Hashiwokakero

??[Hashi](https://spiele.zeit.de/hashiwokakero/)