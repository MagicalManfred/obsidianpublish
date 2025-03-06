---
{"dg-publish":true,"permalink":"/kondensator-und-dielektrikum-kondensatorentladung/"}
---

# Kondensatorentladung
Die generelle Exponentialfunktion: $U(t) = U_0 \cdot \frac{1}{2}^{\frac{t}{t_{H}}}$ → als e-Funktion: $U(t) = U_0 \cdot e^{-ln(2) \cdot \frac{t}{t_{H}}}$
___
Folgender Zusammenhang liegt im Experiment am Ende vor:
$U_R + U_C = U_{ges} = 0$ (mit $U=\frac{Q}{C}$ und $U_R = I(t) \cdot R$) → 
$$
\begin{align}
U_R(t) + U_C(t) &= \frac{Q(t)}{C} + R \cdot I(t) = 0 \\
R \cdot I(t) &= -\frac{Q(t)}{C} \\
I(t) &= -\frac{Q(t)}{R \cdot C} \\
\dot{Q} &= -\frac{Q(t)}{R \cdot C}
\end{align}
$$
→ die letzte Zeile stellt eine **Differenzialgleichung** da d.h. verknüpft die Funktion $Q(t)$ zu jedem Zeitpunkt $t$ mit ihrer Ableitung nach der Zeit $\dot{Q}(t)$. Gesucht ist somit eine Funktion $Q(t)$ , die proportional zu ihrer eigenen Ableitung ist. So etwas tritt auch bei der Exponentialfunktion in ihrer Grundform auf $y(x) = y_0 \cdot e^{c\cdot x}$. Löst man die Differenzialgleichung nach $Q(t)$ um und schreibt sie als e-Funktion, ergibt sich:
$$
Q(t) = Q_0 \cdot e^{-\frac{t}{R \cdot C}}
$$
→ mit $U(t) = \frac{Q(t)}{C}$ ergibt sich insgesamt:
$$
U(t) = U_0 \cdot e^{-\frac{t}{R \cdot C}}
$$
___
... mit dieser Formel und $U(T_H) = \frac{1}{2} \cdot U_0$ ergibt sich übrigens für die Halbwertszeit:
$$
\begin{align}
U(T_H) &= 2 \cdot U(T_H) \cdot e^{-\frac{T_H}{R \cdot C}}\\
1 &= 2 \cdot e^{-\frac{T_H}{R \cdot C}}\\
\frac{1}{2} &= e^{-\frac{T_H}{R \cdot C}}\\
-ln(2) &= -\frac{T_H}{R \cdot C}\\
-ln(2) \cdot R \cdot C &= -T_H\\
T_H &= R \cdot C \cdot ln(2)
\end{align}
$$
... womit sich mit der ersten Formel: $U(t) = U_0 \cdot e^{-ln(2) \cdot \frac{t}{t_{H}}}$  wieder die finale Gleichung ergibt:
$$
U(t) = U_0 \cdot e^{-\frac{t}{R \cdot C}}
$$
(die hier 😉).