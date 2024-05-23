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

## Einführung in den spezifischen Widerstand


<H4>Erklärung des Begriffs „spezifischer Widerstand“</H4>

{{1}}
*********
Der spezifische Widerstand $\rho$ ist ein Maß für den elektrischen Widerstand R, den ein Material einem elektrischen Strom entgegensetzt.
*********

---

<H4>Formel</H4>

{{2}}
***************
> $\rho = R \cdot \dfrac{A}{l}$

- R .. elektrische Widerstand des Materials

- A .. Querschnittsfläche des Materials

- l .. Länge des Leiters ist.
***************

---

<H4>Einheit</H4>

{{3}}
***************


> $\Big[\Omega \cdot \dfrac{mm^2}{m}\Big]$ 
***************

---

<H4>Praktische Bedeutung</H4>

{{4}}
********
Unterscheidung zwischen guten Leitern (niedriges $\rho$) und schlechten Leitern bzw. Isolatoren (hohes $\rho$).
********


## Demonstrationsexperiment

Wir bestimmen den spezifischen elektrischen Widerstand von einem Eisendraht mit dem Cassy-Messgerät.

---

<H4>Eigenschaften des Drahtes:</H4>

{{1}}
*********
<section class="newspaper">

> Länge: $l=$<input type="number" default="1" min="0" max="10" id="l" size="5"> $m$   <br> <br> Querschnittsfläche: $A=$<input type="number" default="1" min="0" max="10" id="A" size="5"> $mm^2$ 

![Schaltzeichen](https://diversewolken.ddns.net/nextcloud/index.php/s/fxcfX6KcjSPgyJn/download)

</section>
*********

---

<H4>Messungen</H4> 

{{2}}
*********
<section class="newspaper">
> $U = $<input type="number" default="0" min="0" max="10" id="U" size="5"> $V$ <br> <br>  $I= $<input type="number" default="1" min="0" max="10" id="I" size="5"> $A$

![Schaltkreis](https://diversewolken.ddns.net/nextcloud/index.php/s/ST5C8Yi8mXKDxZN/download)

</section>
*********

---

<H4>Berechnung des elektrischen Widerstands R aus den Messwerten</H4>

{{3}}
*********

> $R = \dfrac{U}{I} $ = <script input="button"> let U = document.getElementById("U").value; let I = document.getElementById("I").value; let R=U/I; R </script> $\Omega$
*********

---

<H4>Berechnung des spezifischen elektrischen Widerstands $\rho$</H4>

{{4}}
*********

> $\rho = R \cdot \dfrac{A}{l} = $ <script input="button"> let U = document.getElementById("U").value; let I = document.getElementById("I").value; let l = document.getElementById("l").value; let A = document.getElementById("A").value; U/I*A/l  </script> $\Omega \dfrac{mm^2}{m}$

*********


{{5}}
*****************
<H3> Experimentieraufgabe </H3>

Bestimme den elektrischen Widerstand R und den spezifischen elektrischen Widerstand von einem __Konstantan__-Draht und einem __Kupfer__-Draht

Ergänze dazu die Messwerte:

| Werte   | Eisen | Konstantan   | Kupfer   |
| :--------- | :--------- | :--------- | :--------- |
| Länge l [m]   | <script> let l = document.getElementById("l").value; l </script> |  <script> let l = document.getElementById("l").value; l </script>    |  <script> let l = document.getElementById("l").value; l </script>    |
| Querschnittsfläche A [mm²]    | <script> let A = document.getElementById("A").value; A </script> |   <script> let A = document.getElementById("A").value; A </script>   |   <script> let A = document.getElementById("A").value; A </script>   |
| Spannung U [V]    | <script> let U = document.getElementById("U").value; U </script> |      |      |
| Stromstärke I [A] | <script> let I = document.getElementById("I").value; I </script> | | |
| Widerstand R [$\Omega$] | <script> let U = document.getElementById("U").value; let I = document.getElementById("I").value; let R=U/I; R </script> |  | |
| Spez. elktr. Widerstand $\rho$ [$\Omega \cdot \frac{mm^2}{m}$] | <script input="button"> let U = document.getElementById("U").value; let I = document.getElementById("I").value; let l = document.getElementById("l").value; let A = document.getElementById("A").value; U/I*A/l  </script>  | |

*****************

## Video


<iframe width="800" height="600" src="https://www.youtube.com/embed/5O7Y7NOyrMU?t=1165" title="Telekolleg Physik 19 Verzweigter Stromkreis" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
__Ab 19:25 min__

## Aufgaben

1. Ein Kupferdraht hat eine Länge von 2 Metern und einen Widerstand von 0,34 $\Omega$. Die Querschnittsfläche beträgt 1 mm². Berechne den spezifischen Widerstand von Kupfer.

    {1}{<span style="color:orange">$ \rho = R \cdot \frac{A}{l} = 0,34 \, \Omega \cdot \frac{1 \, mm^2}{2 \, m} = 0,17 \, \Omega \cdot \frac{ mm^2}{m} $</span>}

---

2. Ein Eisenstab hat eine Querschnittsfläche von 2 mm² und einen spezifischen Widerstand von $(1 \cdot 10^{-7} \, \Omega \cdot m)$. Berechne den elektrischen Widerstand R, wenn der Stab eine Länge von 3m hat?

    {2}{<span style="color:orange">$ R = \rho \cdot \frac{l}{A} = 1 \cdot 10^{-7} \, \Omega \cdot m \cdot \frac{3 \, m}{2  \, mm^2} $</span>}

---

3. Welche Materialien eignen sich besonders gut als Leiter und warum? Recherchiere typische spezifische Widerstände von mindestens drei verschiedenen Leitermaterialien und notiere sie.

    | | |
    | Material | Spezifischer Widerstand $\rho\ [\Omega \cdot \frac{m}{mm^2}]$ |
    | Kupfer | |
    | Aluminium | |
    | Gold | |
    | Konstantan | | 

---

4. (ZA) Erkläre, warum der spezifische Widerstand für verschiedene Materialien unterschiedlich ist und welche Faktoren diesen beeinflussen.