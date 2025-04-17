---
{"dg-publish":true,"permalink":"/aufleitungen-von-ln-x/"}
---

## 1. Aufleitung von $\ln(x)$
Die Stammfunktion (oder das unbestimmte Integral) von $\ln(x)$ ist:
$$\int \ln(x)dx = x \cdot \ln(x) - x + C$$
 → $C$ ist dabei die Integrationskonstante.
___
## 2. Aufleitung von $x \cdot \ln(x) - x$ 
$$\int x \ln(x) - x) \, dx$$
Um dies zu berechnen, integrieren wir jeden Teil separat:
1. **Integration von $x \cdot \ln(x)$**:
- Verwenden Sie partielle Integration mit $u = \ln(x)$ und $dv = x \, dx$.
- Dann ist $du = \frac{1}{x} \, dx$ und $v = \frac{1}{2}x^2$.
- Die partielle Integration ergibt:
$$\int x \ln(x) \, dx = \frac{1}{2} x^2 \ln(x) - \int \frac{1}{2} x^2 \cdot \frac{1}{x} \, dx = \frac{1}{2} x^2 \ln(x) - \frac{1}{2} \int x \, dx = \frac{1}{2} x^2 \ln(x) - \frac{1}{4} x^2$$
2. **Integration von $-x$**:
   - Dies ist einfach:
$$\int -x \, dx = -\frac{1}{2} x^2$$
→ Kombinieren wir diese Ergebnisse:
$$\int (x \ln(x) - x) \, dx = \left( \frac{1}{2} x^2 \ln(x) - \frac{1}{4} x^2 \right) - \frac{1}{2} x^2 + C = \frac{1}{2} x^2 \ln(x) - \frac{3}{4} x^2 + C$$
Also ist die Aufleitung von $x \cdot \ln(x) - x$ :
$$\int (x \ln(x) - x) \, dx = \frac{1}{2} x^2 \ln(x) - \frac{3}{4} x^2 + C$$