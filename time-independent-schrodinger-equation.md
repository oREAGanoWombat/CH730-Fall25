---
title: Time-Independent Schrodinger Equation
layout: default
author: Natalie Woods
nav_order: 4
---

# Time-independent Schrodinger Equation
In classical mechanics, an object moving through space possesses characteristics (acceleration, momentum, position, etc) that can be accurately and precisely calculated. For example, if the initial conditions are known, a ball being thrown in the air can have its exact energy or momentum calculated at any position. However, in quantum mechanics, such precise models simply break down. Rather than a particle being localized like a classical object such as a ball, its position at any one point in time is spread out in space.  Although it is fundamentally impossible to accurately determine every attribute of a particle simultaneously, we can use Schrodinger's Equation to develop probabilistic predictions on the state (including the probability distribution and energy) of the particle.

The time-independent Schrodinger’s equation for a freely-moving particle is $$Hψ=Eψ$$ where $$ψ$$ is a wave function describing the particle's state, $$E$$ is the corresponding energy eigenvalue of the state, and $$H$$ is the Hamiltonian operator. This variant is the simplest form of Schrodinger's Equation as the state of the particle is stationary (i.e does not change with time). The Hamiltonian Operator is used on $$\psi$$ to receive the energy of the state, $$E$$, making it an essential tool in determining the particle's energy.

## Kinetic Energy $$E$$ of a Wave
Given that $$V=0$$, $$E$$ in $$Hψ=Eψ$$ encompasses the kinetic energy of the system. Thus, to determine what $$E$$ represents for a particle, we must reinterpret the classical formula for kinetic energy in quantum terms. Firstly, we must get $$E$$ in terms of momentum $$p$$.

$$E = \frac{1}{2}mv^2 = \frac{(mv)^2}{2m} = \frac{p^2}{2m}$$

Now that the kinetic energy is expressed with momentum, we can use De Broglie's relation ($$p=\frac{h}{λ}$$) to obtain the kinetic energy of a particle in terms of quantum properies.

$$E=\frac{p^2}{2m}=\frac{(\frac{h}{λ})^2}{2m}$$

Where $$h$$ is Planck’s constant and $$λ$$ is the particle’s wavelength.
$$λ=\frac{2π}{k}$$ [^1] (where $$k$$ is the spatial frequency of the wave) is then substituted into the equation to achieve

$$E=\frac{h(\frac{k}{2π})^2}{2m}$$

To simplify the appearance of the final equation, we substitute $$ℏ=\frac{h}{2π}$$. Thus the constant, $$E$$, is equal to

$$E=\frac{ℏ^2 k^2}{2m}$$

## Determination of Hamiltonian Operator $$H$$
From the (proven) relationship $$∇^2 ψ=-k^2ψ$$ [^2], and the constant $$E=\frac{ℏ^2 k^2}{2m}$$, we can determine the expression for the Hamiltonian operator, $$H$$.
Starting with $$Hψ=Eψ$$, the known constant $$\frac{ℏ^2 k^2}{2m}$$ for $$E$$ is plugged in, as shown below:

$$Hψ=\frac{ℏ^2 k^2}{2m} ψ$$

By slightly manipulating the equation, we obtain the following equivalent expression:

$$Hψ=-\frac{ℏ^2}{2m} (-k^2ψ)$$

The relationship $$∇^2 ψ=-k^2 ψ$$ can then be clearly used to obtain the final equation:

$$Hψ=-\frac{ℏ^2}{2m} (∇^2 ψ)$$

Thus, the final expression for the Hamiltonian operator $$H$$ for $$Hψ=Eψ$$ is equal to

$$H=\frac{-ℏ^2}{2m} ∇^2$$

---

Page Author: *{{ page.author }}*

[^1]: Link to broccoli
[^2]: Link to Eigenfunction and Eigenvalues webpage
