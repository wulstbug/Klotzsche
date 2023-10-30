<!--
author: Christian Golnik

language: de

link: https://gist.githubusercontent.com/andre-dietrich/3c69f68b2c4d80c8c6eb177229ae1ae8/raw/31cde15c4a7f3c2eda7d5ebdea440205f366acad/hideCircle.css

narrator: Ukrainian Female
-->

# Aufgabe zur Kombination von Exponential- und Sinusfunktion

## Schwingung einer Masse an einer Feder

![Federschwinger](https://www.biancahoegel.de/mechanik/bilder/Simple_harmonic_oscillator.gif)Ein Massestück hängt an einer Feder (Ruheposition). Wird die Masse um 5 cm nach unten gezogen $(s_{max})$ und anschließend losgelassen so schwingt diese nach oben und erreicht den höchsten Punkt nach $1s$. Nach weiteren $1s$ erreicht die Masse wieder den Ausgangspunkt an dem sie losgelassen wurde. (Zum Zeitpunkt t=0 bewegt sich die Masse durch die Ruheposition auf dem Weg nach oben). 

a. Bestimme eine Funktion der Form $s(t)=a·sin(b·t)$ für diese Schwingung. <br> <br>
b. Notiere die Periodendauer T für diese Schwingung. Errechne an welcher Position s(t) sich die Masse nach $t=2,5s$ befindet.
c. Berechne, nach welcher Zeit sich die Masse zum ersten und zum zweiten Mal bei s=1cm befindet.

Erweiterung: Dämpfung

Aufgrund der Reibung wird die Schwingung der Masse nun langsam abgedämpft. D.h. dass die Amplitude hier immer weiter abnimmt. <span style="color:orange">Die Periodenlänge verändert sich nicht.</span>

> _Hinweis: Als Amplitude bezeichnet man die Hälfte des Abstands zwischen Maximum und Minimum. Da angenommen wird, dass die Feder um die Ruhelage $s=0$ schwingt, kann hier das Maximum der Funktion als Amplitude betrachtet werden._

Da die Amplitude (in der Sinusfunktion der Paramter a) abnimmt, ist dieser Parameter nun zeitabhängig.

Wir nehmen nun an, dass die Amplitude a der Schwingung nach jeder Periodenlänge um 30% des vorherigen Wertes abnimmt.

d. Notiere eine explizite Berechnungsvorschrift für die Amplitude a(t) der Schwingung.

e. Zeichne ein Diagramm in welches du die Funktion a(t) und die Funktion -a(t) als BLeistift-Linie einzeichnest. Nutze für die Zeit t mindestens 10s.

f. Die Funktionsgleichung der Schwingung ist nun ein Produkt aus der Amplitudenfunktion a(t) und der Sinus-Schwingung aus Aufgabe a. Notiere diese neue gedämpfte Schwingung s(t).

g. Markiere dir nun in deinem Diagramm aus Aufgabe die Maxima und die Minima der Funktion s(t) entlang der Funktionen a(t) und -a(t). Markiere die ebenso die Nulldurchgänge der Sinusfunktion.

h. Zeichne mit Hilfe der Stützstellen die gedämpfte Schwingung der Feder.

i. Berechne, nach welcher Zeit der Federausschlag noch 10% bzw. 1% des ursprünglichen Ausschlags beträgt.

### Lösungshinweis a) und b)

Die Ausdehnung der Feder gibt einen Hinweis auf den Parameter a der Sinusfunktionen.

Die Zeit, bis der Federschwinger in seine ursprüngliche Position zurückgekehrt ist (Periodendauer T), gibt einen Hinweis auf den Parameter b.

 - Für b ist zu beachten, dass wenn t gleich der Periodendauer T ist, muss der Wert innerhalb der Sinusklammer genau $2\pi$ ergeben.

 - D.h. für $sin(b\cdot t)$ muss gelten: wenn t=T, dann ist $b\cdot T = 2\pi$.

### Lösung a) und b)

a.

$ a=5cm$, $b=\frac{2\pi }{4\,s}=\frac{\pi}{2}$

__Ab jetzt ohne Einheiten (Strecke in cm und Zeit in Sekunden):__

$s(t)=2\cdot sin(\frac{\pi}{2}\cdot t) $

b.

Die Periodendauer beträgt T=4s.

$s(2,5)= 5 \cdot sin(\frac{\pi}{2} \cdot 2,5) \approx -3,54$

Die Kugel befindet sich bei etwa -1,73 cm

### Lösungshinweis c)

Damit die Forderung erfüllt ist muss gelten:

$ s(t) = 1 $

Dies muss nach t aufgelöst werden.

### Lösung c)

$ s(t) = 1 $

Einsetzen und umstellen:

$ 1 = 5 \cdot sin(\frac{\pi}{2} \cdot t) \hspace{0.5cm} \Big\vert :5 $

$ \dfrac{1}{5} = sin(\frac{\pi}{2} \cdot t) \hspace{0.5cm} \Big\vert sin^{-1} $

$ sin^{-1}(\dfrac{1}{5}) = \frac{\pi}{2} \cdot t \hspace{0.5cm} \Big\vert \cdot \frac{2}{\pi} $

$ t =  \frac{2}{\pi} \cdot sin^{-1}(\dfrac{1}{5}) $

$ t_1 \approx 0,13 $ und $ t_2 = 2 - t_1 = 1,87$

Die Masse ist nach 0,13s und nach 1,87s bei einer Auslenkung von 1 cm.

![Loesung_c.png](https://diversewolken.ddns.net/nextcloud/index.php/s/DEidEgcbRY7CNzo/download)

### Lösungshinweise d)

Eine prozentuale Abnahme von 10% deutet auf einen exponentiellen Verlauf des Parameters a hin.

Die zeitabhängige Gleichung des Parameters a sollte demzufolge lauten:

$ a(t) = a_0 \cdot q^{t/T} $ 

mit <br>
    
$\hspace{1cm}$ T..Periodendauer der Schwingung

$\hspace{1cm}$ q..Wachstums-/Abnahmefaktor je Periode

$\hspace{1cm}$ $a_0$.. Anfangswert der Auslenkung

$\hspace{1cm}$ t..Zeit in Sekunden

Ermittle die Werte der Paramter und stelle die Gleichung auf.

### Lösung d)

Parameterbestimmung:

T..Periodendauer der Schwingung

$\hspace{1cm}$ _Die Periodendauer der Schwinung ist bereits bestimmt worden und beträgt 4s. Ohne Einheiten ist T = 4._

q..Wachstums-/Abnahmefaktor je Periode

$\hspace{1cm}$ _Der Wachstumsfaktor q ist durch die Dämpfung in der Aufgabe beschrieben. Je Periode nimmt die Amplitude um 10% ab. D.h. q = 0,7 (70%)._

$a_0$.. Anfangswert der Auslenkung

$\hspace{1cm}$ _Der Anfangswert $a_0$ entspricht dem ursprünglichen Wert a ohne Dämpfung, hier 5 (5cm)._

Die Funktionsgleichung der exponentiellen Dämpfung der Amplitude a(t) lautet somit

$$ a(t) = 5 \cdot 0,7^{t/4} $$

mit 

$\hspace{1cm}$ t..Zeit in  Sekunden

### Lösungshinweis e) 

Hier kann sicherlich eine Wertetabelle helfen.

| | |
| t | a(t) |
| 0 | .. |
| 1 | .. |
..
| | |
| 10 | .. |

wo die fehlenden Werte ergänzt werden. Im Anschluss zeichnet man das Diagramm.

### Lösung e)

| | |
| t | a(t) |
| 0 | 0|
| 1 | 4.57 |
| 2 | 4.18 |
| 3 | 3.83 |
| 4 | 3.50 |
| 5 | 3.20 |
| 6 | 2.93 |
| 7 | 2.68 |
| 8 | 2.45 |
| 9 | 2.24 |
| 10 | 2.05 |

### Lösung f)

$$ s(t) = a_0 \cdot q^{t/T} \cdot sin(\frac{\pi}{2} \cdot t) $$

d.h mit eingesetzten Parametern

$$ s(t) = 5 \cdot 0,7^{t/4} \cdot sin(\frac{\pi}{2} \cdot t) $$

### Lösung g)

![GedampfteSchwingung_Seite_2.jpg](https://diversewolken.ddns.net/nextcloud/index.php/s/kBptes9QawBmrXe/download)

### Lösung h)

![GedampfteSchwingung_Seite_3.jpg](https://diversewolken.ddns.net/nextcloud/index.php/s/sGCojZFNDmCoMpX/download)

### Lösung i)

Für 10% - Löse: $0,1 = 0,7^{t/4}$ -> $ t = 4 \cdot log_{0,7}(0,1) = 25,8$ -> nach 25,8s ist die Amplitude 10%.

Für 1% - Löse: $0,01 = 0,7^{t/4}$ -> $ t = 4 \cdot log_{0,7}(00,1) = 51,6$ -> nach 51,6s ist die Amplitude 1%.