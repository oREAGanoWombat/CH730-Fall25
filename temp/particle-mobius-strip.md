---
title: Particle on a Möbius Strip
layout: default
author: Reagan McNeill Womack
nav_exclude: true # excludes file from navigation
---

# Particle on a Möbius Strip
From our discussion of a particle on a ring[^1], we get the following definition of our wave function in terms of a quantum number $$m_l$$ and phase $$\phi$$ in radians

$$\Psi = e^{im_{l}\phi}$$

The wave function must equal itself after travelling once around the ring. Thus we get that the wave function must equal itself when we add $$2\pi$$, or the travel distance around the ring in radians

$$\Psi(\phi) = \Psi(\phi+2\pi)$$

A Möbius strip is much like a ring in that one full pass around the Möbius strip would result in the particle starting and ending in the same location. The main difference between a Möbius strip and a ring is that the particle would need to travel twice the distance of that in a ring when it is on a Möbius strip for the particle to return to the same location. This is because for a particle to travel the full distance of the Möbius strip, it must travel along both sides of the Möbius strip.

<p align="center"><img src="/assets/images/mobius-strip.jpeg">Image Source[^2]</p>

This means that the wave function must equal itself when we add $$4\pi$$ rather than $$2\pi$$ as seen in the particle on a ring.

$$\Psi(\phi) = \Psi(\phi+4\pi)$$

We can use this relationship to find the conditions for our quantum number $$m_l$$ by plugging in our definition for the wave function $$\Psi$$

$$\begin{align}
& e^{im_l\phi} & = e^{im_l(\phi+4\pi)} \\
\implies & 1 & = e^{4\pi i m_l} & = {\left( e^{i\pi} \right)}^{4m_l} \\
& 1 & = {(-1)}^{4m_l}
\end{align}$$

For the above statement to hold true, $$4m_l$$ must always equal an even whole number, thus $$m_l$$ can only be multiples of $$\frac{1}{2}$$

$$m_{l} = \ldots ,\frac{-3}{2},-1,\frac{-1}{2},0,\frac{1}{2},1,\frac{3}{2},\ldots$$

> As a note for future reference: $$^{1}H$$ has spin-1/2 quantum number, which falls in the conditions for the quantum number of a particle on a Möbius strip.

---

*Page Author: {{ page.author }}*

[^1]: PLACEHOLDER, link to particle on a ring page
[^2]: https://medium.com/@shengmorni/1963-88a359d2f68b
