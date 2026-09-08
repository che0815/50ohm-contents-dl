## Formeln umstellen

* In Klasse N: zwei fertige zugeschnittene Größengleichungen
  * $f[[\unit{\mega\hertz}]] = \dfrac{300}{\lambda[[\unit{\meter}]]}$
  * $\lambda[[\unit{\meter}]] = \dfrac{300}{f[[\unit{\mega\hertz}]]}$
* Das ist nur *eine* Gleichung – einmal nach $f$, einmal nach $\lambda$ umgestellt

<note>
* Vertiefung auf der Webseite: Definition "zugeschnittene Größengleichung" und der Zusammenhang $\lambda = c_0 / f$ in Grundeinheiten
</note>

---

* In Klasse E und A gibt die Formelsammlung nur noch die Grundform an
  * Umstellen ist dort zwingend erforderlich
* Vorgehen: nötige Operation ($\cdot$, $:$, $+$, $-$, …) auf *beide* Seiten gleichzeitig anwenden

---

Wir hatten bereits $\lambda = \dfrac{c_0}{f}$

Doch wie kommt man zu $c_0 = f \cdot \lambda$ und $f = \dfrac{c_0}{\lambda}$?

---
## Mathematischer Ansatz

$\lambda = \dfrac{c_0}{f}$ soll nach $f$ umgestellt werden.

* $|~\cdot f$ bzw. $|~: \lambda$: Operation auf *beiden* Seiten durchführen
* Größe in Zähler *und* Nenner kürzt sich weg ($\frac{f}{f} = 1$)

---
#### 1. Schritt
Multiplikation auf beiden Seiten mit $f$, um es nach links zu bekommen.

<fragment>
$\lambda = \dfrac{c_0}{f} \quad\quad\quad | \cdot f$
</fragment>
<fragment>
$\lambda\cdot f = \dfrac{c_0 \cdot f}{f}$
</fragment>
<fragment>
Nach Kürzen
$\lambda \cdot f = c_0$
</fragment>

---
#### 2. Schritt
Dividieren auf beiden Seiten mit $\lambda$, um es nach rechts zu bekommen.

<fragment>
$\lambda \cdot f = c_0 \quad\quad\quad |: \lambda$
</fragment>
<fragment>
$\frac{\lambda\cdot f}{\lambda} = \frac{c_0}{\lambda}$
</fragment>
<fragment>
$f = \dfrac{c_0}{\lambda}$
</fragment>

---
## Zahlenbeispiel

Welche Frequenz entspricht $\lambda = \qty{2,069}{\meter}$?

* Grundeinheiten einsetzen ($\unit{\meter}$, $\unit{\second}$)
  * es gilt $\frac{1}{\unit{\second}} = \qty{1}{\hertz}$

$f = \dfrac{c_0}{\lambda} = \dfrac{\qty{3e8}{\meter\per\second}}{\qty{2,069}{\meter}} \approx \qty{145}{\mega\hertz}$

---
## Ausblick

* Umstellen mit Multiplikation und Division können wir jetzt
* Klasse E: zusätzlich Addition, Subtraktion, Potenzen, Wurzeln
* Klasse A: zusätzlich Logarithmen
* Wird jeweils an Ort und Stelle Schritt für Schritt erklärt
