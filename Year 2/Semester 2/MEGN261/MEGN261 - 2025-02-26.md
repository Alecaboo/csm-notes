#notes #meche #megn261

- Remember to do the thermo homework, dumbass.
#### The Big Topics from Chapter 7/8
- COE, COM, and Entropy of H2O/R-134a, and that's really it.

## Real Notes
$$
\frac{ds}{dt}=\overbrace{ \dot{m}\Delta  s}^{ \text{Mass transfer} }+ \underbrace{ \frac{\dot{Q}}{T_{b}} }_{ \text{Heat transfer} }+\overbrace{ \dot{S_{gen}} }^{ \text{Disordered Universe} }
$$
- To cover some of the general statements into what's actually real
- Entropy is always increasing in the universe
	- This is $\dot{S_{gen}}$
- Entropy is always increasing (which means it cannot decrease)
	- if $\dot{S_{gen}}=0$, that's the ideal case
	- If $\dot{S_{gen}}<0$, you did something wrong and are drunk. Go home.
- $\frac{ds}{dt}$ is zero since we're steady state and there's no change over time.
- If we're closed then $\dot{m}\Delta s$ is zero since no $\dot{m}$.
- If we're adiabatic $\frac{\dot{Q}}{T_{b}}$ is zero since adiabatic.
## Now we need to deal with ideal gas
- This really should've been in chapter 3, but, w/e
- We're still using constant specific heats because we're doing this shit by hand. 
	- Do not EES ideal gas problems because they're based on constant specific heats
		- At a job you will absolutely be using EES
- We get two equations, based on cp and cv respectively
	- Where do they come from, exactly?
	- Gibbs (free energy) or Tds
- Closed - COE
$$
\underbrace{ Q }_{ Tds }-\underbrace{ w }_{ Pdv }=\underbrace{ \Delta u }_{ Cv\ dT }
$$
$$
TdS-Pd\forall=Cv\ dT
$$
$$
dS-\frac{Pd\forall}{T}=\frac{Cv\ dT}{T}
$$
$$
dS=\frac{Pd\forall}{T}+\frac{CvdT}{T}
$$
$$
ds=\frac{Pdv}{T}-\frac{CvdT}{T}
$$
$$
\boxed{
\underbrace{ s_{2}-s_{1}=C_{v}\ln \frac{T_{2}}{T_{1}}+R\ln \frac{v_{2}}{v_{1}} }_{ \text{Closed system equation} }
}
$$
- The fuck did that R come from?
	- Blatant fucking wizardry, in short.
		- $c_{p}=c_{v}+R$, yadayadayada, the math works. I swear.
- Equation (7-33) in the book, for record's sake
- Now for open systems, which we're going to go into even less detail on, somehow.
$$
Tds=dh-vdP
$$
- We tossed out boundary work somewhere along the way.
$$
Tds=c_pdT-v(dP)
$$
$$
ds = \frac{c_{p}dT}{T}-\frac{v(dP)}{T}
$$
$$
\boxed{
s_{2}-s_{1}=c_{p}\ln\left( \frac{T_{2}}{T_{1}} \right)-R\ln\left( \frac{P_{2}}{P_{1}} \right)
}
$$
-----
### Isentropic Efficiency
$\neq 100$, $s_{1}=s_{2}$
- What ol' Derrick calls "k-equations", k-specific heat ratio which is $\frac{c_{p}}{c_{v}}$, which is just 1.4. Unitless.
- What happens to 7-33 when you say isentropic? Left hand side goes to zero, that's what
$$
0=c_{v}\ln \frac{T_{2}}{T_{1}}+R\ln \frac{v_{2}}{v_{1}}
$$
$$
cv\ln T_{2}T_{1}=-R\ln \frac{v_{2}}{v_{1}}
$$
- You can use $c_{p}=c_{v}+R$ and $=\frac{c_{p}}{c_{v}}$ and a bit of handwaving and a smidge of exponentiating
$$
\left( \frac{T_{2}}{T_{1}} \right)=\left( \frac{v_{1}}{v_{2}} \right)^{k-1}
$$
- This is (one of many) k-equations.
- Used for $\boxed{T_{2s}=T_{1}\left( \frac{v_{1}}{v_{2}} \right)^{k-1}}$
	- We don't solve for $T_{1}$ because that's the start so we don't really care.
- Now we need to figure out pressures
$$
\frac{T_{2}}{T_{1}}=\left( \frac{P_{2}}{P_{1}} \right)^{\frac{k-1}{k}}
$$
$$
\boxed{
T_{2s}=T_{1}\left( \frac{P_{2}}{P_{1}} \right)^{\frac{k-1}{k}}
}
$$
- Next EES (and Friday) we're going to be dealing with $\eta_{th}$ and other such fun.
