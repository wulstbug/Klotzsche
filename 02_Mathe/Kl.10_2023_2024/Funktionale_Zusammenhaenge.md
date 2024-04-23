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

<H3> Ziel: Probiere verschiedene Learning-Apps zum Thema "Zuordnung von Funktionen und Funktionstermen" auf den folgenden Seiten aus. Erstelle dann eine eigene Learning-App.

Nutze folgende Typen von Funktionen:

| | 
| Name der Funktion | Beispielfunktion |
---------------------
| Lineare Funktionen: Bsp: $f(x) = 2x+3$
| Quadratische Funktionen: Bsp: $f(x) = 3(x-2)^2$
| Exponentialfunktionen: Bsp: $f(x) = \Big(\dfrac{1}{3}\Big)^x+1$
| Wurzelfunktion: Bsp: $f(x) = \sqrt{(x)+2}$
| Hyperbelfunktion: Bsp: 




</H3>



### Beispiel 1

??[Funktionsterme1](https://learningapps.org/18796976)

### Beispiel 2

??[Funktionsterme2](https://learningapps.org/3897439)

### Beispiel 3

??[Funktionsterme3](https://learningapps.org/23796583)

# Rätsel

## Milchkannenrätsel

??[Milchkannenrätsel](https://www.walter-fendt.de/html5/mde/threejugsproblem_de.htm)


## Hashiwokakero

??[Hashi](https://spiele.zeit.de/hashiwokakero/)