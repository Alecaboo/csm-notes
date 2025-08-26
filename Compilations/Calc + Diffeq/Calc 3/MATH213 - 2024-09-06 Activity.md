#notes #math213 #math #calc


## 1 - Matching Part

d maps to D because... they're both the only circular models.
f maps to F because they're both ellipses (and the only ones present).
c maps to A because it's two "peaks" parallel to x
e maps to C because it's also two "peaks," but oriented the other way
b maps to E because you can see the hyperbolas that form b present in E
leaving a matching to B, both because of process of elimination and the linear looking level curve (when viewed from above) is correct.

| Surface | Level Curve |
| ------- | ----------- |
| a       | B           |
| b       | E           |
| c       | C           |
| d       | D           |
| e       | A           |
| f       | F           |

## 2. Find and Sketch Domain

$$f(x,y) = \frac{\sqrt{x+y+1}}{x-1}$$
- ok so you gotta find where we would have problems
	- Negative sqrts and denominator being 0
	- Dealing with the denominator, $x \neq 1$
	- Now for that numerator component, $x+y+1 \geq 0$
	- $x + y \geq -1$
		- $y \geq -x-1$
		- $$D := \{ (x,y) \mid y \geq -x-1, x\neq 1\}$$
![[x+y geq 1]]

## 3. Level Curves

Level curves for $$f(x,y) = \sqrt{y-x^{2}-1} \text{ for } c=0,1,2.$$
$$c_{0}= \sqrt{y-x^{2}-1}$$
$$c^{2}= y-x^{2}-1$$
$$y = c^{2}+x^{2}+1$$
Alright that's a function with our variables nice and separate, so if we were to plug in our vales

$$c=0, y = x^{2}+1$$
$$c=1, y= x^{2}+2$$
$$c=2, y= x^{2}+5$$
![[root(y-xsq-1) level curves]]
- There are no level curves for $c<0$ because we live under a root

## 4. Level Curves again


$$f(x,y) = 3\cos(2x+y) \text{ for c=-3,0,3}$$
I mean, I might just try ripping the values in.
$$-3 = 3\cos(2x+y)$$
$$-1 = \cos(2x+y)$$
$$2x+y=\pi$$
$$y = -2x+\pi$$
$$0 = 3\cos(2x+y)$$
$$2x +y = +  \frac{\pi}{2}$$
$$y= -2x + \frac{\pi}{2}$$
$$3 = 3\cos(2x+y)$$
$$1 = \cos(2x+y)$$
$$2x+y = 0$$
$$y = -2x$$
Ok that's a bunch of equations, reformatting the final answers out:
$$y = -2x+\pi$$
$$y = -2x + \frac{\pi}{2}$$
$$y= -2x$$
And now, an attempt to sketch.

We can only be between -3 and 3 because there's a 3 floating out in front of our equation, which works as "amplitude," - the normal domain of $\cos(\theta)$ is -1 to 1, so when multiplying by an amplitude of three, our domain is now -3 to 3
