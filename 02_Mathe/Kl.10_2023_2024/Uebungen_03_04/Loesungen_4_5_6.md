# Vermischte Aufgaben

## 1. Zerfall von Caesium

Cäsium 137 hat eine Halbwertszeit von 33 Jahren, das heißt die Hälfte der Atomkerne wird nach 33 Jahren zerfallen sein.

    a. Berechne wie viel Prozent der Cäsium-Kerne nach 100 Jahren ca. noch vorhanden sind.

    b. Berechne nach wie viel Jahren noch 70% der Cäsium-Kerne vorhanden sind

### Lösungshinweis: Zerfall von Caesium

Die Anzahl der Caesium-Atome kann durch folgende Gleichung beschrieben werden: 

$ N(t) = N_0 \cdot 0,5^{(\frac{t}{T})} $

wobei 

    $N_0$...Anzahl der Caesium-Atome zu Beginn

    $T$...Halbwertszeit (hier 33 a)

### Lösung: Zerfall von Caesium


a.  

    $$ N(t) = N_0 \cdot 0,5^{(\frac{t}{T})} \hspace{0.5cm}\Big\vert : N_0 $$

    $$ \frac{N(t)}{N_0} = 0,5^{(\frac{t}{T})}$$

    für t = 100 gilt:

    $$ 0,5^{(\frac{100}{33})} = 0,1224 => \underline{12,24\%} $$


b.  Gesucht ist t, sodass $ \dfrac{N(t)}{N_0} = 0,7 $ 

    $$ 0,7 = 0,5^{\frac{t}{33}} $$ d.h.

    $$ log_{0,5}(0,7) = \frac{t}{33} \hspace{0.5cm}\Big\vert \cdot 33 $$

    $$ 33 \cdot log_{0,5}(0,7) = \underline{16,98} $$

    Nach etwa 17 Jahren sind noch 70% vorhanden.

## 2. Bogenmaß

Gib folgende Winkel im Bogenmaß an
   a.    23,5°			b.    258,2°

### Lösungshinweis

Dreisatz nutzen.

$$ \frac{Gradmaß}{360^\circ} = \frac{Bogenmaß}{2\pi} $$

### Lösung

Gib folgende Winkel im Bogenmaß an

a.    $23,5° = \dfrac{23,5}{360}\cdot 2\pi \approx 0,41 $ <br>
<br>
b.    $258,2° = \dfrac{258,2}{360}\cdot 2\pi \approx 4,51 $

## 3. Gleichungen mit sin(x)

Gib für folgende Gleichungen je eine Lösung an

a.  $ sin(x)+2 = 1		$

b.  $ sin(x)+2,5=4      $

### Lösungshinweis

Gleichung zunächt so umstellen, das sin(x) allein auf einer Seite steht. Dann entweder im GTR arcsin verwenden, oder überlegen, für welchen Wert x der Sinus die Gleichung erfüllt.

### Lösung

a.  

$ sin(x)+2 = 1	\hspace{0.5cm}\Big\vert-1 	$

$ sin(x) = -1	$

$ \underline{x = \dfrac{3\pi}{2}} $

b.

$ sin(x)+2,5=4 \hspace{0.5cm}\Big\vert -2.5 $

$ sin(x)+2,5=1.5$

=> keine Lösung möglich, da 1,5 nicht innerhalb des Wertebereiches der Sinus-Funktion liegt.

## 4. Schwingung einer Masse an einer Feder

![Federschwinger](https://www.biancahoegel.de/mechanik/bilder/Simple_harmonic_oscillator.gif)Ein Massestück hängt an einer Feder (Ruheposition). Wird die Masse um 2 cm nach unten gezogen $(s_{max})$ und anschließend losgelassen so schwingt diese nach oben und erreicht den höchsten Punkt nach $0,3s$. Nach weiteren $0,3 s$ erreicht die Masse wieder den Ausgangspunkt an dem sie losgelassen wurde. (Zum Zeitpunkt t=0 bewegt sich die Masse durch die Ruheposition auf dem Weg nach oben). <br> _Hinweis: Dieser Prozess soll ohne Reibung betrachtet werden._ <br> <br>
a. Bestimme eine Funktion der Form $s(t)=a·sin(b·t)$ für diese Schwingung. <br> <br>
b. Errechne an welcher Position s(t) sich die Masse nach $t=1,1 s$ befindet.

###



### Lösung

a.

$ a=2cm$, $b=\frac{2\pi }{0,6\,s}$

$s(t)=2\cdot sin(10,47\cdot t) $

b.

$s(1,1)=2\,cm \cdot sin(10,47 \cdot 1,1) \approx -1,73 cm$

Die Kugel befindet sich bei etwa -1,73 cm

## 5. Luftdruck der Erdatmosphäre

Der Luftdruck der Erdatmosphäre nimmt mit zunehmender Höhe um ca. 13% je 1000 m Höhenunterschied ab. Der Luftdruck in Meereshöhe beträgt durchschnittlich 101,3 kPa (Kilopascal).

a) Gib die zugehörige Funktionsgleichung an und bestimme den Luftdruck auf dem Mount Everest (ca. 8800m).

b) Bestimme den Abnahmefaktor (Wachstumsfaktor) für den Höhenunterschied 1m.

### Lösung a)

a) 

$$ f(h) = p_0 \cdot 0,83^{(\frac{h}{1000})}$$

 - $h$ .. Höhe in Meter

 - $p_0$ .. Luftdruck auf Meeresspiegel (101,3 kPa)

__oder__

$$ f(h) = p_0 \cdot 0,83^{h}$$ 

 - $h$ .. Höhe in km

__Mount Everest:__

$$ f(h) = 101,3 kPa \cdot 0,83^{8,8} = 19,66 kPa $$

### Lösung b)

b) Wachstumsfaktor $q_{1m}$ für $\Delta h = 0,001 km$

      __Achtung: Hier muss mit h in km gerechnet werden, oder mit der ersten Formel (vorherige Seite)__

$$ q_{1m} = \frac{f(h+\Delta h)}{f(h)} $$

$$ q_{1m} = \frac{0,83^{(h+0,001)}}{0,83^{h}} $$

$$ q_{1m} = \frac{0,83^h\cdot 0,83^{0,001}}{0,83^{h}} $$

$$ q_{1m} = 0,83^{0,001} $$ 

$$ q_{1m} = \underline{0,9998} $$