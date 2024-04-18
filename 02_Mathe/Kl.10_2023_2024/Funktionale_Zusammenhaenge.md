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

 Wertebereich $\mathbb{W_f} = \R^{\geq0}$ $\hspace{0.5cm}$(_Hinweis: $\mathbb{W_f}$ ist die Menge aller Zahlen $y$, die die $y=f(x)$ annehmen kann._)

</span>

{{1}}
*************

<H2>Umkehrfunktion</H2>

Die <span style="color:orange">***Umkehrfunktion zu f(x)***</span> ist genau die Funktion $f^{-1}(x)$ für die gilt:

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

> $ y = log_3(x)$ 

> => Umkehrfunktion: $f^{-1}(x) = log_3(x)$
*************

</span>

## Aufgaben

1. Bilde folgende Umkehrfunktionen. Gib (sofern nicht gegeben) jeweils den maximal möglichen Definitionsbereich $\mathbb{D_f}$ und den Wertebereich $\mathbb{W_f} $ der Funktion $f(x)$ an.

$\hspace{0.5cm}$a) $f(x) = 2 \cdot x$

{1}{$\hspace{0.5cm}$<span style="color:orange">$\mathbb{D_f}=\R$ ; $\mathbb{W_f} = \R $ ; $f^{-1}(x) = \dfrac{1}{2}\cdot x$</span>}

$\hspace{0.5cm}$b) $f(x) = x^2 + 2$ mit $\mathbb{D_f} = \R^{\geq0}$

{2}{$\hspace{0.5cm}$<span style="color:orange">$\mathbb{W_f} = \R^{\geq2} $ ; $f^{-1}(x) = \sqrt{x-2}$</span>}

$\hspace{0.5cm}$c) $f(x) = \Big(\dfrac{1}{3}\Big)^x$

{3}{$\hspace{0.5cm}$<span style="color:orange">$\mathbb{D_f}=\R$ ; $\mathbb{W_f} = \R^{>0} $ ; $f^{-1}(x) = log_\frac{1}{3}(x)$</span>}

$\hspace{0.5cm}$d) $ f(x) = log_4(x) $

{4}{$\hspace{0.5cm}$<span style="color:orange">$\mathbb{D_f}=\R^{>0}$ ; $\mathbb{W_f} = \R $ ; $f^{-1}(x) = 4^x$</span>}

2. Notiere zu den Umkehrfunktionen $f^{-1}$ aus den Aufgaben 1. a) - d) die Definitionsbereiche $\mathbb{D}_{f^{-1}}$ und die Wertebereiche $\mathbb{W}_{f^{-1}}$ und vergleiche diese jeweils mit $\mathbb{D}_{f}$ bzw. $\mathbb{W}_{f}$


## Eigenschaft der Umkehrfunktion

<span style="color:red">
> Existiert zu einer Funktion $f(x)$ die Umkehrfunktion $f^{-1}(x)$ so sind Definitionsbereich $\mathbb{D}$ und Wertebereich jeweils vertauscht, d.h. $\mathbb{D_f}=\mathbb{W}_{f^{-1}}$ und $\mathbb{W_f}=\mathbb{D}_{f^{-1}}$. 
</span>

{{1}}
***********
<iframe src="https://learningapps.org/watch?v=pyw56qt4324" style="border:0px;width:100%;height:500px" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"></iframe>
***********