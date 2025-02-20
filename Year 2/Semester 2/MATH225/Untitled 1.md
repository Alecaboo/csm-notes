$$\frac{dy}{dt} - y = - \frac{t}{\sqrt{y}}$$
$$\frac{dy}{dt}+ p(t)y  = -t*y^{\frac{-1}{2}}$$
$$p(t) = -1$$
$$n = \frac{-1}{2}$$
$$u = y^{1 - \frac{-1}{2}}=y^{\frac{3}{2}}$$
$$y = u^{\frac{2}{3}}$$
$$\frac{dy}{dt}= \frac{dy}{du} \frac{du}{dt}$$
$$\frac{dy}{dt}= \frac{2}{3}u^{\frac{2}{3}} \frac{du}{dt}$$

$$\frac{2}{3}u^{\frac{2}{3}} \frac{du}{dt}  - u^{\frac{2}{3}}= -t (u^{\frac{2}{3}})^{\frac{-1}{2}}$$

$$\frac{2}{3}u^{\frac{2}{3}} \frac{du}{dt}- u^{\frac{2}{3}}= -t(u^{\frac{-1}{3}})$$
$$\frac{du}{dt}- \frac{3}{2}= -t (u^{- \frac{1}{3}})(\frac{3}{2}u^{\frac{-2}{3}})$$
$$\frac{du}{dt}- \frac{3}{2}= \frac{-3}{2}t u^{-1}$$
$$\frac{du}{dt}+ \frac{3}{2u}t= \frac{3}{2}$$
$$\mu = e^{\int \frac{3}{2u}}= e^{\frac{3}{2}\ln(u)}=u^{\frac{3}{2}}$$
$$t u^{\frac{3}{2}} = \int u^{\frac{3}{2}} * \frac{3}{2}$$
$$tu^{\frac{3}{2}}= \frac{9}{4}u^{\frac{3}{2}}+C $$
$$t(u)= \frac{9}{4}+ \frac{C}{u^{\frac{3}{2}}}$$
$$t(y) = \frac{9}{4}+ \frac{C}{(y^{\frac{2}{3})^{\frac{3}{2}}}}= $$
$$t(y) = \frac{9}{4}+ \frac{C}{y} \text{I mean, that's *an* explicit form? Right?}$$
