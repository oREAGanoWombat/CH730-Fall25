---
title: Time-Independent Schrodinger Equation
layout: default
author: Natalie Woods
---

# Time-independent Schrodinger Equation
The time-independent variant for Schrodinger’s equation is $$Hψ=Eψ$$ where $$ψ$$ is a wave function, $$E$$ is the energy of the wave, and $$H$$ is the Hamiltonian operator. This equation is an eigenfunction with eigenvalue $$E$$. Below we will derive the value of $$E$$.

## Derivation of constant $$E$$
To derive $$E$$, the energy (or amplitude) of the wave, we first manipulate the classical equation for kinetic energy to get it in terms of momentum $$p$$:

$$E = \frac{1}{2}mv^2 = \frac{(mv)^2}{2m} = \frac{p^2}{2m}$$

Despite the above energy equation being specific to classical mechanics, we can use the particle momentum $$p$$, $$p=\frac{h}{λ}$$ ,in place of classical momentum $$p$$ to get quantized $$E$$.

$$E=\frac{p^2}{2m}=\frac{(\frac{h}{λ})^2}{2m}$$

Where $$h$$ is Planck’s constant and $$λ$$ is the particle’s wavelength.
$$λ=\frac{2π}{k}$$ (where $$k$$ is the spatial frequency of the wave) is then substituted into the equation to achieve

$$E=\frac{h(\frac{k}{2π})^2}{2m}$$

To simplify the appearance of the final equation, we substitute $$ℏ=\frac{h}{2π}$$. Thus the constant, $$E$$, is equal to

$$E=\frac{ℏ^2 k^2}{2m}$$

## Derivation of Hamiltonian Operator $H$
From the (proven) relationship $$∇^2 ψ=-k^2ψ$$, and the constant $$E=\frac{ℏ^2 k^2}{2m}$$, we can derive the expression for the Hamiltonian operator, $$H$$.
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
