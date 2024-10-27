### Kepler's Equation

| Equation | Closed-Form (CF) Solution? | CF Solution(s) | A Numeric |
|----------|----------|----------|-------|
| $x - 0.967 \sin{\left(x \right)} - \frac{10 \pi}{19} = 0$ | No? (NotImplementedError) |  | 2.3449 |


### Polynomials

| Equation | Closed-Form (CF) Solution? | CF Solution(s) | A Numeric |
|----------|----------|----------|-------|
| $x^{2} - x - 1 = 0$ | Yes, Elementary | $\{ \frac{1}{2} - \frac{\sqrt{5}}{2}, \frac{1}{2} + \frac{\sqrt{5}}{2} \}$ | -0.6180 |
| $2 x^{3} + x + 1 = 0$ | Yes, Elementary | $\{{ \frac{1}{2 \left(- \frac{1}{2} - \frac{\sqrt{3} i}{2}\right) \sqrt[3]{\frac{27}{4} + \frac{3 \sqrt{87}}{4}}} - \frac{\left(- \frac{1}{2} - \frac{\sqrt{3} i}{2}\right) \sqrt[3]{\frac{27}{4} + \frac{3 \sqrt{87}}{4}}}{3}, \dots \}}$ | 0.2949 + 0.8723i |
| $x^{5} + 1 = 0$ | Yes, Elementary | $\{{ -1, \frac{1}{4} + \frac{\sqrt{5}}{4} + i \sqrt{\frac{5}{8} - \frac{\sqrt{5}}{8}}, \dots \}}$ | -1.0000 |
| $x^{5} - x - 1 = 0$ | No? (CRootOf) |  | 1.1673 |


### Exp, Log and *x*

| Equation | Closed-Form (CF) Solution? | CF Solution(s) | A Numeric |
|----------|----------|----------|-------|
| $x e^{x} = 0$ | Yes, Elementary | $0$ | 0.0000 |
| $x e^{x} + \frac{1}{10} = 0$ | Yes, with W, Exp, Log | $\{ W\left(- \frac{1}{10}\right), W_{-1}\left(- \frac{1}{10}\right) \}$ | -0.1118 |
| $x + e^{x} = 0$ | Yes, with W, Exp, Log | $- W\left(1\right)$ | -0.5671 |
| $x \log{\left(x \right)} + 1 = 0$ | Yes, with W, Exp, Log | $e^{W\left(-1\right)}$ | 0.1684 + 0.7078i |
| $x + \log{\left(x \right)} = 0$ | Yes, with W, Exp, Log | $W\left(1\right)$ | 0.5671 |
| $x^{2} + \log{\left(x \right)} = 0$ | Yes, with W, Exp, Log | $e^{- \frac{W\left(2\right)}{2}}$ | 0.6529 |


### Exp and Log

| Equation | Closed-Form (CF) Solution? | CF Solution(s) | A Numeric |
|----------|----------|----------|-------|
| $e^{x} \log{\left(x \right)} + 1 = 0$ | No? (NotImplementedError) |  | 0.5671 |
| $e^{x} + \log{\left(x \right)} = 0$ | No? (NotImplementedError) |  | 0.2699 |


### Trig and Trig Same Frequency

| Equation | Closed-Form (CF) Solution? | CF Solution(s) | A Numeric |
|----------|----------|----------|-------|
| $\sin{\left(x \right)} + \cos{\left(x \right)} = 0$ | Yes, Elementary | $- \frac{\pi}{4}$ | -0.7854 |
| $\sin{\left(x \right)} \cos{\left(x \right)} + 1 = 0$ | Yes, Elementary | $\{{ - 2 \operatorname{atan}{\left(- \frac{1}{2} + \frac{\sqrt{2} \sqrt{1 - \sqrt{3} i}}{2} + \frac{\sqrt{3} i}{2} \right)}, \dots \}}$ | -0.7854 + -0.6585i |
| $\sin{\left(x \right)} + \sin{\left(x + 1 \right)} = 0$ | Yes, Elementary | $\{ 2 \operatorname{atan}{\left(\frac{1 - \sqrt{\tan^{2}{\left(\frac{1}{2} \right)} + 1}}{\tan{\left(\frac{1}{2} \right)}} \right)}, 2 \operatorname{atan}{\left(\frac{1 + \sqrt{\tan^{2}{\left(\frac{1}{2} \right)} + 1}}{\tan{\left(\frac{1}{2} \right)}} \right)} \}$ | -0.5000 |
| $\sin{\left(x \right)} \sin{\left(x + 1 \right)} + 1 = 0$ | Yes, Elementary | $\{{ - 2 \operatorname{atan}{\left(\frac{- \tan{\left(\frac{1}{2} \right)} + \sqrt{-1 + \tan^{4}{\left(\frac{1}{2} \right)} + 2 \tan^{2}{\left(\frac{1}{2} \right)} - 2 i \sqrt{\tan^{2}{\left(\frac{1}{2} \right)} + 2} \tan{\left(\frac{1}{2} \right)}} + i \sqrt{\tan^{2}{\left(\frac{1}{2} \right)} + 2}}{\tan^{2}{\left(\frac{1}{2} \right)} + 1} \right)}, \dots \}}$ | -0.5000 + -0.7921i |


### Trig and Trig, Commensurate Frequencies

| Equation | Closed-Form (CF) Solution? | CF Solution(s) | A Numeric |
|----------|----------|----------|-------|
| $\sin{\left(x \right)} + \sin{\left(3 x \right)} = 0$ | Yes, Elementary | $\{{ 0, - \frac{\pi}{2}, \frac{\pi}{2}, \pi, \dots \}}$ | 0.0000 |
| $\sin{\left(x \right)} + \sin{\left(3 x \right)} + 1 = 0$ | Returns 0 Solutions |  | -0.2730 |
| $\sin{\left(x \right)} \sin{\left(3 x \right)} + 1 = 0$ | Yes, Elementary | $\{{ - \frac{\pi}{2}, \frac{\pi}{2}, i \log{\left(- \frac{1}{2} + \frac{\sqrt{5}}{2} \right)}, i \log{\left(\frac{1}{2} + \frac{\sqrt{5}}{2} \right)}, \dots \}}$ | -1.5708 |
| $\sin{\left(3 x \right)} + \sin{\left(x + 1 \right)} = 0$ | Timeout |  | 1.3208 |
| $\sin{\left(3 x \right)} \sin{\left(x + 1 \right)} + 1 = 0$ | Timeout |  | ValueError |


### Trig and Trig, Non-Commensurate Frequencies

| Equation | Closed-Form (CF) Solution? | CF Solution(s) | A Numeric |
|----------|----------|----------|-------|
| $\sin{\left(x \right)} + \sin{\left(\sqrt{3} x \right)} = 0$ | Yes, Elementary | $\{ 0, - \frac{\pi \left(1 + \sqrt{3}\right)}{2} \}$ | 0.0000 |
| $\sin{\left(x \right)} + \sin{\left(\sqrt{3} x \right)} + 1 = 0$ | No? (NotImplementedError) |  | -0.3876 |
| $\sin{\left(\sqrt{3} x \right)} + \sin{\left(x + 1 \right)} = 0$ | No? (PolynomialDivisionFailed) |  | 1.9338 |
| $\sin{\left(x \right)} \sin{\left(\sqrt{3} x \right)} + 1 = 0$ | No? (NotImplementedError) |  | ValueError |
| $\sin{\left(\sqrt{3} x \right)} \sin{\left(x + 1 \right)} + 1 = 0$ | No? (NotImplementedError) |  | ValueError |


### Trigonometric and *x*, Exp, Log

| Equation | Closed-Form (CF) Solution? | CF Solution(s) | A Numeric |
|----------|----------|----------|-------|
| $x + \sin{\left(x \right)} = 0$ | No? (NotImplementedError) |  | 0.0000 |
| $x \sin{\left(x \right)} + 1 = 0$ | No? (NotImplementedError) |  | 3.4368 |
| $\log{\left(x \right)} + \sin{\left(x \right)} = 0$ | No? (NotImplementedError) |  | 0.5787 |
| $e^{x} + \sin{\left(x \right)} = 0$ | No? (NotImplementedError) |  | -0.5885 |
| $x^{3} + \cos{\left(x \right)} = 0$ | No? (NotImplementedError) |  | -0.8655 |
| $e^{x} + \sin{\left(x \right)} = 0$ | No? (NotImplementedError) |  | -0.5885 |


