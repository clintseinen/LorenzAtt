# Lorenz Attractor

Code to build a lorenz attractor video simulation. Information on the Lorenz Attractor equations
can be found [here](http://mathworld.wolfram.com/LorenzAttractor.html)

## Simplified Equations:

$$
\dot{x} = \sigma (y-x)\\
\dot{y} = -xz + rx - y\\
\dot{z} = xy - bz
$$

where 
$$
\sigma = \frac{\nu}{\kappa}\\
r = \frac{Ra}{Ra_c}\\
b = \frac{4}{1+a^2}
$$
and $\sigma$ is the Prandtl number, $Ra$ is the Rayleigh number, $Ra_c$, is the critical Rayleigh number, and $b$ is the geometric factor.

