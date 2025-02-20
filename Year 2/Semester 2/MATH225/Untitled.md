$$\frac{dP}{dt}= \cos(t)P \left(1 - \frac{P}{100}\right)$$
$$\frac{dP}{P(1- \frac{P}{100})}= \cos(t) dt$$
$$\frac{dP}{P - \frac{P^{2}}{100}}=\cos(t)dt$$
$$\int \cos(t) dt = \sin(t)$$
$$\int \frac{dP}{P - \frac{P^{2}}{100}}= -\ln(\frac{100}{P}-1)+C$$
$$-\ln(\frac{100}{P}-1) = \sin(t)+C$$
$$e^{-\ln(\frac{100}{P}- 1)}= e^{\sin(t) + C}$$
$$\frac{1}{\frac{100}{P}- 1}= e^{\sin(t)+C}$$
$$1 = e^{\sin(t)+C }(\frac{100}{P}-1)$$
$$e^{\sin(t)+C}(\frac{100}{P})= e^{\sin(t)+C}+1$$
$$P(t)=\frac{100e^{\sin(t)+C}}{e^{\sin(t)+C}+1}$$
$$P(0) = 50, 50 = \frac{100e^{C}}{e^{C}+1}$$
$$50(e^{C}+1)=100e^{C}, 50e^{C}+50 = 100e^{C}, 50 = 50e^{C}, e^{C}=1, C=0$$
---
$$P(0)=100$$
$$100 = \frac{100e^{C}}{e^{C}+1}$$
$$100e^{C}+100 = 100e^{C}$$
$$100 = 0 \text{ Uh. That's uh. Not exactly true. No solution?}$$


