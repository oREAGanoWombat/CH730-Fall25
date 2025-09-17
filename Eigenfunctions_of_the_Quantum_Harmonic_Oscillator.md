---
title: Eigenfunction for a Quantum Harmonic Oscillator
layout: default
author: Natalie Woods
nav_exclude: true # excludes file from navigation
---
For a quantum harmonic oscillator, the Schrodinger equation is $$H\psi + V\psi= E\psi$$, where $$H=$$ $$\frac{-ℏ^2}{2m} ∇^2$$, $$V=$$ $$\frac{1}{2}kx^2$$, and $$\psi$$ is the particle's wave function.

Thus, with these definitions included, the equation is

$$\frac{-ℏ^2}{2m} ∇^2\psi + \frac{1}{2}kx^2\psi= E\psi$$

The solution to this equation is in the form

$$\psi_v(y) = N_vH_v(y)e^\frac{-y^2}{2}$$

where $$y = \frac{x}{\alpha}$$, $$\alpha = (\frac{ℏ^2}{mk_f})^\frac{1}{4}$$, and $$N_v$$ is the normalization constant 

$$N_v =\frac{1}{\alpha\pi^\frac{1}{2}2^vv!}$$

$$e^\frac{-y^2}{2}$$ is the formula for the guassian curve, implying there is a probabilistic nature to the solution of the equation, which we know to be true when describing the position of an electron.

$$H_v$$, however, has multiple expressions based on the frequency $$v$$, shown in the table below:
<p align="center"><img src="/assets/images/Hermite polynomials.jpg"></p>

Thus, depending on the value of $$v$$, the formula of the wave function changes. The image below displays the solutions to $$\frac{-ℏ^2}{2m} ∇^2\psi + \frac{1}{2}kx^2\psi= E\psi$$ with increasing $$v$$.

<p align="center"><img src="/assets/images/quantumharmonic solution.jpg"></p>

The waves with even $$v$$ are symetric with respect to $$y=0$$ and those with odd $$v$$ are antisymmetric with respect to $$y=0$$. Included in this is the potential energy function.

To verify that the solutions are correct we will evaluate it at ground state ($$v=0$$). After substituting $$H_v$$ with the corresponding polynomial at $$v=0$$, 1, and subtituting $$y = \frac{x}{\alpha}$$, the solution becomes

$$\psi_0(x) = N_0(x)e^\frac{-x^2}{2\alpha^2}$$

We then must compute the double derivative of $$\psi_0(x)$$ to easily plug it into the schrodinger equation.

$$\frac{d^2}{dx^2}\psi_0(x) = \frac{d^2}{dx^2}[N_0(x)e^\frac{-x^2}{2\alpha^2}]$$

After the derivation process, we arrive at the following solution:

$$\frac{d^2}{dx^2}\psi_0(x) = \frac{x^2}{\alpha^4}\psi_0 - \frac{1}{\alpha^2}\psi_0$$

(note: $$\psi_0$$ was substituted for $$N_0(x)e^\frac{-x^2}{2\alpha^2}$$.)

As the formula for $$\frac{d^2}{dx^2}\psi_0(x)$$ is now known, we substitute it in schrodinger's equation and obtain

$$\frac{-ℏ^2}{2m} (\frac{x^2}{\alpha^4}\psi_0 - \frac{1}{\alpha^2}\psi_0) + \frac{1}{2}kx^2\psi_0= E_0\psi_0$$

Upon substituting $$\alpha = (\frac{ℏ^2}{mk_f})^\frac{1}{4}$$, we find

$$\frac{1}{2}\sqrt{\frac{k_f}{m}}ℏ\psi_0 = E_0\psi_0$$

And finally, substituting $$\omega=sqrt{\frac{k_f}{m}}$$ provides us with our final result:

$$\frac{1}{2}ℏ\omega\psi_0 = E_0\psi_0$$

As we can see, the eigenvalue, $$E_0$$, is

$$E_0 = \frac{1}{2}ℏ\omega\$$

This agrees with the known scientific observation that the energies permitted by the boundary conditions for Schrodinger's equation for an oscillator are $$E_v = (v + \frac{1}{2})ℏ\omega$$. Thus, it follows that $$\psi_0$$, determined with the usage of hermite polynomials, is a solution to Schrodinger's equation for a harmonic oscillator.





