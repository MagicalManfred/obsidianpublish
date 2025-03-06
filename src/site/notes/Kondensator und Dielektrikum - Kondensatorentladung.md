---
{"dg-publish":true,"permalink":"/kondensator-und-dielektrikum-kondensatorentladung/"}
---

# Kondensatorentladung
Die generelle Exponentialfunktion: $\large U(t) = U_0 \cdot \frac{1}{2}^{\frac{t}{t_{H}}}$ → als e-Funktion: $\large U(t) = U_0 \cdot e^{-ln(2) \cdot \frac{t}{t_{H}}}$
___
Folgender Zusammenhang liegt im Experiment am Ende vor:
$\large U_R + U_C = U_{ges} = 0$ (mit $\large U=\frac{Q}{C}$ und $\large U_R = I(t) \cdot R$) → 
$$
\large
\begin{align}
U_R(t) + U_C(t) &= \frac{Q(t)}{C} + R \cdot I(t) = 0 \\
R \cdot I(t) &= -\frac{Q(t)}{C} \\
I(t) &= -\frac{Q(t)}{R \cdot C} \\
\dot{Q} &= -\frac{Q(t)}{R \cdot C}
\end{align}
$$
→ die letzte Zeile stellt eine **Differenzialgleichung** da d.h. verknüpft die Funktion $Q(t)$ zu jedem Zeitpunkt $t$ mit ihrer Ableitung nach der Zeit $\dot{Q}(t)$. Gesucht ist somit eine Funktion $Q(t)$ , die proportional zu ihrer eigenen Ableitung ist. So etwas tritt auch bei der Exponentialfunktion in ihrer Grundform auf $\large y(x) = y_0 \cdot e^{c\cdot x}$. Löst man die Differenzialgleichung nach $Q(t)$ um und schreibt sie als e-Funktion, ergibt sich: $$ \large Q(t) = Q_0 \cdot e^{-\frac{t}{R \cdot C}}$$
→ mit $\large U(t) = \frac{Q(t)}{C}$ ergibt sich insgesamt:
$$
\Huge
U(t) = U_0 \cdot e^{-\frac{t}{R \cdot C}}
$$
___
... mit dieser Formel und $\large U(T_H) = \frac{1}{2} \cdot U_0$ ergibt sich übrigens für die Halbwertszeit:
$$
T_H = R \cdot C \ ln(2)
$$
... womit sich mit der ersten Formel: $\large U(t) = U_0 \cdot e^{-ln(2) \cdot \frac{t}{t_{H}}}$  wieder die finale Gleichung ergibt:
$$
\Huge
U(t) = U_0 \cdot e^{-\frac{t}{R \cdot C}}
$$
(die hier 😉).

Nach dem Buch S. 26.