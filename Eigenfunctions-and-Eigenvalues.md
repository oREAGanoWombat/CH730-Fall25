---
title: Eigenfunctions and Eigenvalues
layout: default
author: Hans Kindstedt
nav_order: 3
---

# Eigenfunctions and Eigenvalues

## Double Derivative of Wave Functions
If we have a wave function with the formula $$\psi=\sin(kx)$$ and we take the first derivative of it, we find the following:

$$\frac{d}{dx}\psi(kx) = \frac{d}{dx}\sin(kx) = k\cos(kx)$$

Taking the first derivative of a sine function yields a cosine function as shown above. When we take the derivative again (which is identical to taking the double derivative of the original wave function), we find the following:

$$\frac{d^{2}}{dx^{2}}\psi(kx) = \frac{d}{dx}k\cos(kx) = -k^{2}\sin(kx)$$

When we take the double derivative, the original wave function returns with the coefficient $$-k^{2}$$. This behavior is characteristic of eigenfunctions: a function that when an operator is applied to it returns the same function multiplied by a constant, an eigenvalue. In these examples, the eigenfunction is $$\sin(kx)$$, the eigenvalues are multiples of $$-k^{2}$$, and the operator is the double derivative ($$\nabla^2$$). 

We can do the same process with the our other wavefunction derived from Euler's formula ($$e^{ikx}$$):

$$\frac{d^{2}}{dx^{2}}\psi(kx) = \frac{d^{2}}{dx^{2}}e^{ikx} = \frac{d}{dx}ike^{ikx} = -k^{2}e^{ikx}$$

Just as before, the original function returns when the double derivative operator is applied as well as the same $$-k^{2}$$ constant. Note that while both equations are eigenfunctions with respect to the double derivative operator, only the second is an eigenfunction with respect to the single derivative operator as well. The derivatives of sine alternate between sine and cosine so the original function only returns after a double derivative while the $$e^{ikx}$$ term is conserved after each derivative in the second wave function.


---

*Page Author: {{ page.author }}*
