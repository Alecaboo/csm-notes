#math213 #math #calc

1. Use the differential of $z$ to approximate $\Delta z$ for
	1. $z=e^{x+y}$ when $(x,y)$ changes from $(0,0)$ to $(0.1,-0.05)$
		1. $f_{x} =e^{x+y}$
		2. $f_{y}=e^{x+y}$
	2. $z=\ln(1+x+y)$ when $(x,y)$ changes from $(0,0)$ to $(-0.1,0.03)$
2. Find $dW$ for $w = xy^{2}+ x^{2}z + yz^{2}$
	1. $f_{x}=y^{2}+2xz$
	2. $f_{y}=2xy +z^{2}$
	3. $f_{z}= x^{2}+2yz$
	4. $dW = (y^{2}+2xz)dx + (2xy+z^{2})dy + (x^{2}+2yz)dz$
3. A solid cone of radius $r$ and height $h$, where $r\approx 4$ cm and $h \approx5$ cm
	1. (Where $V= \frac{1}{3}\pi r^{2}h$)
		1. Find $dV$
			1. $$V_{r}= \frac{2}{3}\pi rh=> V_{r}(4,5)= \frac{40\pi}{3}$$
			2. $$V_{h}= \frac{1}{3}\pi r^{2}= \frac{16\pi}{3}$$
			3. $$dV = \left(\frac{40\pi}{3}\right)dr + \left(\frac{16\pi}{3}\right)dh$$
		2. If your error for $r$ and $h$ is at most 0.1, find the upper bound for the volume of the cone
			1. $$dV = \left(\frac{40\pi}{3}\right)(0.1) + \left(\frac{16\pi}{3}\right)(0.1)= \frac{4\pi}{3}+ \frac{1.6\pi}{3}= \frac{(5.6)\pi}{3}$$
			$$V = \frac{1}{3}\pi (16)(5)= \frac{80\pi}{3} + dV = \frac{\pi(85.6)}{3}$$
	2. 