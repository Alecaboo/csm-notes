## part a

- Just for the record, this is the one we had an adventure with at the end of three before.
$$y=c_{1}e^{-2t}\cos(3t)+c_{2}e^{-2t}\sin(3t)+2$$
$$y' = e^{-2t}(c_{7}\cos(3t)+c_{8}\sin(3t))$$
$$y(0) = c_{1}+2$$
$$c_{1}= -2$$
---
- I aggressively combined constants back in three, so now I have to... claw those back apart.
$$c_{3}= -2c_{1}$$
$$c_{4}= -3c_{1}$$
$$c_{5}= -2 c_{2}$$
$$c_{6}=3c_{2}$$
$$c_{7}= -2c_{1}+3c_{2}$$
$$c_{8}= -3c_{1}-2c_{2}$$
----
$$c_{8}= 6-2c_{2}$$
$$c_{7}= 4+3c_{2}$$
- That, strictly speaking, isn't relevant, but I kept needing it for this, so I left it here.
$$y' = e^{-2t}(c_{7}\cos(3t)+c_{8}\sin(3t))$$
$$0 = 4+3c_{2}$$
$$c_{2}= \frac{-4}{3}$$
$$y = -2 e^{-2t}\cos(3t)- \frac{4}{3}e^{-2t}\sin(3t)+2
$$
## part b
$$y=c_{1}e^{-2t}\cos(3t)+c_{2}e^{-2t}\sin(3t)+2$$
$$2 = c_{1}+2$$
$$c_{1}= 0$$
$$y' = e^{-2t}((-2c_{1}+3c_{2})\cos(3t)+(-3c_{1}-2c_{2})\sin(3t))$$
$$6 = (3c_{2}), c_{2}= 2$$
$$y(t) = 2e^{-2t}\sin(3t)+2$$
