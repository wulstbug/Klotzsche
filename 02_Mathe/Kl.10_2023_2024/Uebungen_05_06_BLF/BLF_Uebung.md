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

.h4b {
    break-before: column;
}
@end

mode: Presentation

@onload
window.LIA.settings.font_size = 2
@end

-->

# BLF Übung - Ohne Hilfsmittel

1. ![fkt](https://diversewolken.ddns.net/nextcloud/index.php/s/wwzkozKH2Cf6N4P/download) Gib je eine Gleichung der dargestellten Funktionen f und g an.

2. Gegeben ist die Funktion $f$ durch $f(x)=\dfrac{2}{3}\cdot x-2$ $(x\in\mathbb{R})$.

    Der Graph der Funktion $g$ ist eine Gerade, die senkrecht zum Graphen von $f$ verläuft. Die Graphen von $f$ und $g$ schneiden sich in einem Punkt auf der $y$-Achse.

        a)Zeichne die Graphen von $f$ und $g$ in ein Koordinatensystem.

        b)Gib eine Funktionsgleichung von $g$ an.

3. ![see](https://diversewolken.ddns.net/nextcloud/index.php/s/tX94KG9sazQofPk/download) Leon möchte die Breite eines Sees bestimmen und fertigt eine Skizze an. Die gestrichelten Linien verlaufen parallel. Berechne die Breite des Sees.

## Lösung 1

Der Graph von f bildet eine um 2 Einheiten nach oben verschobene Kosinusfunktion ab:<br>

$\hspace{1cm} f(x) = cos(x) + 2$ <br>

Der Graph von g bildet eine gespiegelte und um den Faktor 3 gestreckte Sinusfunktion ab: <br>

$\hspace{1cm} g(x) = -3 \cdot sin(x)$ <br>

## Lösung 2

    a)![lsg2](https://diversewolken.ddns.net/nextcloud/index.php/s/SkjqqABbFHwL5JF/download)

    b) Die Steigung $\dfrac{-3}{2}$ und die Verschiebung um 2 Einheiten nach unten lassen sich aus der Abbildung aus Teilaufgabe a) ablesen. <br>

    Die Funktionsgleichung von $g$ lautet $g(x)=-\dfrac{3}{2}\cdot x - 2$

## Lösung 3

Die Breite x des Sees lässt sich mit dem Strahlensatz berechnen.

![LsgSee](https://diversewolken.ddns.net/nextcloud/index.php/s/8tRikC33bziZGNC/download)

Der See ist 150 Meter breit.

# BLF Übung mit Hilfsmitteln

1. In einem rechtwinkligen Koordinatensystem sind die Punkte $A(-3 \mid 6),$ $B(1 \mid -2)$ und $C(3 \mid 0)$ gegeben.

    a) Zeige rechnerisch, dass das Dreieck ABC rechtwinklig ist.

    b) Berechne den Flächeninhalt des Dreiecks ABC.

    c) Aus den Punkten A, B, C und D soll ein Viereck gebildet werden, dessen Flächeninhalt doppelt so groß ist wie der des Dreiecks ABC. Gib die Koordinaten eines solchen Punktes D an.

    d) Bestimme die Größe aller Winkel des Dreiecks.

    e) Begründe, dass es keine Funktion f mit $f(x) = a\cdot b^x (a, b, x \in \mathbb{R}; a\neq 0, b \gt 0)$ geben kann, deren Graph durch die Punkte A, B und C verläuft.


2. ![Pyramide](https://diversewolken.ddns.net/nextcloud/index.php/s/9nZ33a4KNeKeYzw/download) <!-- style="width: 60%" --> Zur Landesrunde der Mathematikolympiade gab es 2014 für jeden Teilnehmer eine Pyramide mit quadratischer Grundfläche. <br> Alle Kanten sind 10 cm lang. <br> Berechne das Volumen und den Oberflächeninhalt dieser Pyramide.

## Lösungshinweis 1)


 a) Gilt für ein Dreieck der Satz des Pythagoras so ist es rechtwinklig. Wenn du die Gültigkeit dessen nachweisen kannst, so ist das ein rechnerischer Beweis.

 b) $ A = \dfrac{1}{2} \cdot  Grundseite \cdot Höhe $

 c) Ergänze das Dreieck zu einem Rechteck, dann verdoppelt sich der Flächeninhalt.

 d) Nutze die Definition von sin und cos im rechtwinkligen Dreieck.

 e) Überprüfe dir die Anzahl der Nullstellen einer Exponentialfunktion der Form $f(x) = a\cdot b^x $ . Vergleiche deine Erkenntnis nun mit den Punkten A, B und C.

## Lösungshinweis 2)

Nutze folgende Skizze um die rechtwinkligen Dreiecke der Pyramide zu berechnen.

![LPyr](https://diversewolken.ddns.net/nextcloud/index.php/s/PYfn9SkyfCTEXET/download) <!-- style="width: 60%" -->
## Lösung 1a)

<section class="newspaper">

![Dreieck1](https://diversewolken.ddns.net/nextcloud/index.php/s/nGWso68tmHPCe79/download) <!-- style="margin-left: auto; margin-right: auto; display: block" -->

<H4>Berechnungen:</H4>

a)Wenn das Dreieck rechtwinklig ist, muss nach dem Satz des Pythagoras gelten:<br>

    $\overline{AB}^2=\overline{AC}^2+\overline{BC}^2$ <br>
    
    Die Seitenlängen des Dreiecks können wiederum mit dem Satz des Pythagoras berechnet werden:<br>
    
    $\overline{AB}^2= 8^2+4^2$<br>
    $= 64+16$<br>
    $= 80$<br> <br>

    $\overline{AC}^2= 6^2+6^2$<br>
    $= 36+36 $<br>
    $= 72 $<br><br>

    $\overline{BC}^2= 2^2+2^2$<br>
    $= 4+4 $<br>
    $= 8 $<br><br>
    

    Es gilt:
    $80= 72+8$ <br>
    $\overline{AB}^2=\overline{AC}^2+\overline{BC}^2$<br><br>

    
    Folglich ist das Dreieck rechtwinklig.

</section>

## Lösung 1b)

b) Mit Teilaufgabe a) gilt $\overline{AC}=\sqrt{72}$ und $BC=\sqrt{8}.$<br>
Mit der Formel für den Flächeninhalt eines Dreiecks folgt:<br>
$A_D= \dfrac{1}{2}\cdot \overline{AC}\cdot \overline{BC}$<br>
$= \dfrac{1}{2}\cdot \sqrt{72}\cdot \sqrt{8}$ <br>
$= 12$ <br> <br>

Der Flächeninhalt des Dreiecks beträgt 12 Flächeneinheiten.

## Lösung 1c)

c)Am einfachsten ist es, das Dreieck zu einem Rechteck zu ergänzen. Ein möglicher Punkt dafür ist der Punkt $D(-5\mid 4).$

## Lösung 1d)

<section class="newspaper">

![Dreieck1](https://diversewolken.ddns.net/nextcloud/index.php/s/nGWso68tmHPCe79/download) <!-- style="margin-left: auto; margin-right: auto; display: block" -->

<H4>Berechnungen:</H4>

d) Im gegebenen Dreieck ist der Winkel $\gamma=90^\circ$ da $\overline{AB}$ die längste Seite des Dreiecks darstellt und somit die Hypothenuse ist. <br>

Es gilt:<br>

$sin(\alpha) = \dfrac{\text{Gegenkathete}}{\text{Hypothenuse}} =  \dfrac{\overline{BC}}{\overline{AB}} = \dfrac{\sqrt{8}}{\sqrt{80}}$ <br>

$ \alpha = sin^{-1}\Big(\dfrac{\sqrt{8}}{\sqrt{80}}\Big) = 18,43^\circ$ <br>

Der Winkel $\beta$ ist demzufolge $90^\circ-\alpha=71,57^\circ$

</section>

## Lösung 1e)

d)Eine Funktion der Form $f(x)=a\cdot b^x$ hat keine Nullstelle. Der Punkt $C$ liegt jedoch auf der $x$-Achse und würde deshalb einer Nullstelle einer möglichen Funktion entsprechen. Daher kann es keine Funktion dieser Form geben, die durch alle Punkte $A,$ $B$ und $C$ geht.


## Lösung 2 (Oberflächeninhalt)


<section class="newspaper">

__Oberflächeninhalt berechnen: Skizze__

![LPyr](https://diversewolken.ddns.net/nextcloud/index.php/s/PYfn9SkyfCTEXET/download) <!-- style="margin-left: auto; margin-right: auto; display: block" -->

<H4>Berechnungen</H4>

Der Oberflächeninhalt einer Pyramide setzt sich zusammen aus dem Flächeninhalt der Grundfläche und dem Flächeninhalt der Seitenflächen. Der Flächeninhalt der quadratischen Grundfläche lässt sich wie folgt berechnen:<br>
$A_G= a\cdot a $ <br>
$= 10\,\text{cm}\cdot 10\,\text{cm} $ <br>
$= 100\,\text{cm}^2 $ <br>

Um den Flächeninhalt der dreieckigen Seitenflächen zu berechnen, muss zunächst die Höhe $h_D$ eines solchen Dreiecks berechnet werden. Dazu wird der Satz des Pythagoras verwendet:<br>
$a^2= \left(\dfrac{a}{2}\right)^2+h_D^2 $ <br>
$(10\,\text{cm})^2=(5\,\text{cm})^2+h_D^2 $ <br>
$100\,\text{cm}^2= 25\,\text{cm}^2+h_D^2 \quad \scriptsize \mid\;-25\,\text{cm}^2 $ <br>
$75\,\text{cm}^2= h_D^2 \quad \scriptsize \mid\;\sqrt{\;} $ <br>
$8,7\,\text{cm}\approx h_D$ <br> <br>

Damit kann der Flächeninhalt eines Dreiecks berechnet werden:<br>
$A_D=\dfrac{1}{2}\cdot a \cdot h_D $ <br>
$\approx\dfrac{1}{2}\cdot 10\,\text{cm}\cdot 8,7\,\text{cm} $ <br>
$\approx 43,5\,\text{cm}^2 $ <br><br>

Nun kann der Oberflächeninhalt der Pyramide berechnet werden:

$A_O=A_G+4\cdot A_D $ <br>
$ \approx100\,\text{cm}^2+4\cdot 43,5\,\text{cm}^2$ <br>
$ = 274\,\text{cm}^2$ <br><br>

Der Oberflächeninhalt der Pyramide beträgt $274\,\text{cm}^2.$

</section>

## Lösung 2 (Volumen)

<section class="newspaper">

__Volumen berechnen: Skizze__

![LPyr3](https://diversewolken.ddns.net/nextcloud/index.php/s/3ZZRZakNesSpBxm/download)<!-- style="margin-left: auto; margin-right: auto; display: block" -->

<H4>Berechnungen</H4>

Um das Volumen der Pyramide berechnen zu können, wird die Höhe $h$ benötigt. Diese lässt sich wieder mit dem Satz des Pythagoras berechnen:
$h_D^2= \left(\dfrac{a}{2}\right)^2+h^2 $ <br>
$(8,7\,\text{cm})^2=(5\,\text{cm})^2+h^2 $ <br>
$75\,\text{cm}^2= 25\,\text{cm}^2+h^2 \quad \scriptsize \mid\;-25\,\text{cm}^2 $ <br>
$50\,\text{cm}^2= h^2 \quad \scriptsize \mid \sqrt{\;} $ <br>
$7,1\,\text{cm}= h $ <br> <br>

Damit lässt sich das Volumen der Pyramide wie folgt berechnen:<br>
$V_P=\dfrac{1}{3}\cdot A_G\cdot h $ <br>
$=\dfrac{1}{3}\cdot 100\,\text{cm}^2\cdot 7,1\,\text{cm} $ <br>
$ = 236,7\,\text{cm}^3 $ <br> <br>

Das Volumen der Pyramide beträgt $236,7\,\text{cm}^3.$

</section>