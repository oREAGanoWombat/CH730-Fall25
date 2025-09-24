---
title: Harmonic Oscillator
layout: default
author: Logan Grady
nav_exclude: true
---

#The Harmonic Oscillator

The Harmonic Oscillator is the second quantum model we will see which can be solved exactlly. As a rationalization for creating this model, we can determine what is oscillating in a chemical system. The answer is bond between atoms, so we can model vibrations of chemical bonds using the Harmonic Oscillator model.

##Classical Harmonic Oscillator

First, imagine a mass, $$m$$ , connected to a spring, lying along the x-axis, with the other end of the spring connected to an immovable wall. At equillibrium, the mass will be at a constant value of x, we can set this arbitraily to be the point x=0. However, by pulling the mass in one direction, the spring can be displaced by some amount, $$x$$. The 'restoring' force to return the spring to equilibrium after displacement, $$F_1$$ , is proportional to the displacement, $$x$$, where the proportionality factor is known as the spring constant, $$k_f$$.Also, the restoring force is in the opposite direction of the displacement, so it is negative. We now have:

$$F_{1}=-k_{f}x$$

In the absence of any other external forces, Newton's second law states that this force must be equal to the mass, $$m$$, times its acceleration, $$a$$.

$$\begin{align}
F_{1} &= -k_{f}x = ma \\
-k_{f}x &= ma \\
\end{align}$$

Rewriting acceleration as the second derivative of position, with respect to time, yields a linear second order differential equation:

$$\begin{align}
-k_{f}x &= m \frac{d^{2}x}{dt^{2}} \\
m \frac{d^{2}x}{dt^{2}} + k_{f}x = 0 \\
\end{align}$$

We can employ the same method for solving linear second order differential equation that we have been using so far. We will take the trial wave function $$x(t)$$ and substitute it into our differential equation.

Note:

$$\begin{align}
x(t) &= Nsin(2 \pi \nu t) \hspace{1cm} \nu = \frac{1}{2\pi} \sqrt{\frac{k_{f}}{m}} \\
\frac{d^{2}x(t)}{dt^{2}} &= N \frac{d}{dt} \frac{2\pi}{2\pi} \sqrt{\frac{k_{f}}{m}} cos(2 \pi \frac{1}{2\pi} \sqrt{k_{f}}{m} t) \\
&= \frac{-k_{f}}{m} N sin(2 \pi \nu t) \\
\end{align}$$

Where $$N$$ is the normailzation constant and $$\nu$$ is the frequency of oscillation.

Substituting into our differential equation yields:

$$\begin{align}
m \frac{d^{2}x(t)}{dt^{2}} + k_{f}x(t) &= 0 \\
m (\frac{-k_{f}}{m} N sin (2 \pi \nu t)) + k_{f} (Nsin(2 \pi \nu t)) &= 0 \\
-k_{f}N sin(2 \pi \nu t) + k_{f}N sin(2 \pi \nu t) &= 0 \\
0 &= 0
\end{align}$$

So our trial wavefunction holds for the conditions we have created so far.

We can now move on the defining the potential energy, $$V(x)$$ , for this system. 

For a constant force, the kinetic energy is given by:

$$E_{k}=Fx$$

For differential forces, the energy is given by the integral of the force with respect to x:

$$E_{k}=\int_{0}^{x_1}Fdx$$

Now, taking potential energy, $$V(x)$$, to be negative kinetic energy:

$$V(x)=-\int_{0}^{x_{1}}Fdx$$

Substituting $$F_{1}$$ for $$F$$,

$$\begin{align}
V(x)&=-\int_{0}^{x_{1}} -\frac{1}{2}k_{f}x \\
&=\frac{1}{2}k_{f}x_{1}^{2}
\end{align}$$

## Quantum Mechanical Harmonic Oscillator

To make the quantum mechanical model, we need to solve the Schrödinger Equation. Recall the full form of the Schrödinger Equation:

$$\frac{-\hbar^{2}}{2m}\nabla^{2} \Psi (x) + V(x) \Psi (x) = E \Psi (x)$$

We have already sovled for the potential energy, so now we need to determine what our wavefunctions are. Utilizing the power series method for solving differential equations and the postulates of quantum mechanics, the eigenfunctions of the hamiltonian (wavefunctions) are given by:

$$\psi_{v}(x)=N_{v}H{v}(y)e^{\frac{-y^{2}}{2}}&&

Where &&v&& is a new quantum number that can be any whole number (ie. 0,1,2,3,...), $$N_{v}$$ is a normalization constant given by $$N_{v}=(\alpha \sqrt{\pi}2^{v}v!)^{\frac{-1}{2}}$$ , $$y=\frac{x}{\alpha}, $$H_{v}$$ is the Hermite Polynomial for a give value of $$v$$, and, finally, $$\alpha=(\frac{\hbar^{2}}{mk_{f}})^{\frac{1}{4}}$$

The quantized energy is given by:

$$\begin{align}
E_{v}&=h \nu (v + \frac{1}{2}) \\
&=\hbar \omega (v+\frac{1}{2})
\end{align}$$

Where $$\omega=\sqrt{\frac{k_{f}}{m}}$$

Here, we see that when the quantum number $$v$$ is equal to zero, the system still has energy; this is known as the zero-point energy and it is a stark contrast to the Particle in a Box quantized energy, wherein the quantum number $$n$$ could not be equal to zero. Additionally, we can see that the spacing between energy levels is constant, since as $$v$$ increases, $$E_{v}$$ will increase linearly. This is also different than the PIB energy, where there was a square dependence on the quantum number $$n$$ and the spacing between energy levels increased. 
