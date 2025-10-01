---
title: Eigenfunction for a Quantum Harmonic Oscillator
layout: default
author: Natalie Woods
nav_order: 9
---

# Eigenfunction for a Quantum Harmonic Oscillator
In this section, we will state and discuss the solution of wave function for the quantum harmonic oscillator. Afterwards, it will be proven by applying the solution to Schrodinger's equation and prove that the associated eigenvalue, $$E$$, is in accordance with the well-known and established energy values of the system. We will begin by declaring Schrodinger's equation.

### Schrodinger Equation for a Quantum Harmonic Oscillator
Mentioned previously in the Harmonic Oscillator section [^1], Schrodinger's equation for a quantum harmonic oscillator is $$H\psi + V\psi= E\psi$$, where $$H=$$ $$\frac{-ℏ^2}{2m} ∇^2$$, $$V=$$ $$\frac{1}{2}kx^2$$, and $$\psi$$ is the particle's wave function. Note $$V$$ is the potential energy function of a harmonic oscillator.

Thus, with these definitions included, Schrodinger's equation is

$$\frac{-ℏ^2}{2m} ∇^2\psi + \frac{1}{2}kx^2\psi= E\psi$$

### Definition and Discussion of the Eigenfunction for Harmonic Oscillator

It has been determined that the energies permitted by the boundary conditions for Schrodinger's equation for an oscillator are $$E_v = (v + \frac{1}{2})ℏ\omega$$ [^1], where $$\omega=\sqrt{\frac{k_f}{m}}$$. We will later use this fact to prove that the precise solution to Schrodinger's Equation for a quantum harmonic oscillator is

$$\psi_v(y) = N_vH_v(y)e^\frac{-y^2}{2}$$

where $$y = \frac{x}{\alpha}$$, $$\alpha = (\frac{ℏ^2}{mk_f})^\frac{1}{4}$$, and $$N_v$$ is the normalization constant $$N_v =\frac{1}{\alpha\pi^\frac{1}{2}2^vv!}$$

There are several oddities in this solution that set it apart from the other discussed wave functions, particularly with the presence of $$H_v$$ and $$e^\frac{-y^2}{2}.$$ The exact development of this model will not be discussed, but we will elaborate on the meanings of $$H_v$$ and $$e^\frac{-y^2}{2}$$.
The term $$e^\frac{-y^2}{2}$$ represents the Gaussian curve, reflecting the probabilistic nature to the solution of the equation. $$H_v$$, however, has multiple expressions based on the frequency $$v$$, shown in the table below:

<p align="center"><img src="/assets/images/Hermite polynomials.jpg"></p>

Depending on the value of $$v$$, the order of $$H_v$$ changes accordingly to $$v$$. Specifically, the degree of $$H_v$$ is equal to $$v$$. The image below displays the solutions to $$\psi_v(y) = N_vH_v(y)e^\frac{-y^2}{2}$$ with discretely increasing $$v$$.

<p align="center"><img src="/assets/images/quantumharmonic solution.jpg"></p>

Plotted along with the solutions is the potential energy curve (blue parabola). The wave functions corresponding to even $$v$$ are symmetric with respect to $$y=0$$ and those corresponding to odd $$v$$ are antisymmetric with respect to $$y=0$$. As x approaches 0, the Guassian function approaches 1, and so $$H_v$$ dominates the behavior of the wave funtion near the origin. However, as x approaches infinity, the dampening effect of the Gaussian funtion is dominant, forcing the function to approach zero. 

### Proof of the Eigenfunction Solution
To verify that the solutions are correct we will evaluate the solution at ground state ($$v=0$$). Afterwards, we can determine the eigenvalue $$E_0$$ and evaluate its consistency with the expected energy level for a quantum harmon oscillator $$E_v = (v + \frac{1}{2})ℏ\omega$$.

Upon substituting $$H_v$$ with the corresponding polynomial at $$v=0$$, $$H_0 = 1$$, and subtituting $$y = \frac{x}{\alpha}$$, the solution $$\psi_v(y) = N_vH_v(y)e^\frac{-y^2}{2}$$ becomes

$$\psi_0(x) = N_0(x)e^\frac{-x^2}{2\alpha^2}$$

To apply the solution to the Hamiltonian of the Schrodinger's equation, we then must compute $$\frac{d^2}{dx^2}\psi_0(x)$$

$$\frac{d^2}{dx^2}\psi_0(x) = \frac{d^2}{dx^2}[N_0(x)e^\frac{-x^2}{2\alpha^2}]$$

After the derivation process, we arrive at the following solution:

$$\frac{d^2}{dx^2}\psi_0(x) = \frac{x^2}{\alpha^4}\psi_0 - \frac{1}{\alpha^2}\psi_0$$

(note: $$\psi_0$$ was substituted for $$N_0(x)e^\frac{-x^2}{2\alpha^2}$$.)

As the formula for $$\frac{d^2}{dx^2}\psi_0(x)$$ is now known, we substitute it in schrodinger's equation and obtain

$$\frac{-ℏ^2}{2m} (\frac{x^2}{\alpha^4}\psi_0 - \frac{1}{\alpha^2}\psi_0) + \frac{1}{2}kx^2\psi_0= E_0\psi_0$$

After substituting $$\alpha = (\frac{ℏ^2}{mk_f})^\frac{1}{4}$$ and simplifying the expression, we receive

$$\frac{1}{2}\sqrt{\frac{k_f}{m}}ℏ\psi_0 = E_0\psi_0$$

And finally, substituting $$\omega=\sqrt{\frac{k_f}{m}}$$ provides us with our final result:

$$\frac{1}{2}ℏ\omega\psi_0 = E_0\psi_0$$

As we can see, the eigenvalue, $$E_0$$, is

$$E_0 = \frac{1}{2} \hslash \omega$$

This result is consistent with the permissable energy levels of a quantum harmonic oscillator, delineated by $$E_v = (v + \frac{1}{2})ℏ\omega$$. Thus, it follows that $$\psi_0$$, determined with the usage of hermite polynomials, is a solution to Schrodinger's equation for a harmonic oscillator.

---

[^1]: https://oreaganowombat.github.io/CH730-Fall25/Harmonic-Oscillator.html
