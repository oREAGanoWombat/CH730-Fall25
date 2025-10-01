---
title: Free Particle and Momentum Operator
layout: default
author: Juliette
nav_order: 5
---

# Summary Notes of Free Particle and Momentum Operator  

## Free Particle  

Function of a standing wave is: 

$$\Psi(x) = A * e^{i k x} + B * e^{-i k x}$$  

Solve for the energy of the wave by applying the hamiltonian to Ψ  

Apply the operator on the wavefunction  

$$H\Psi = -\frac{\hbar^2}{2m} \nabla^2(A e^{i k x} + B e^{-i k x})$$  

$$= -\frac{\hbar^2}{2m}(A(i k)^2 e^{i k x} + B(-i k)^2 e^{-i k x})$$  

$$= -\frac{\hbar^2}{2m}(-A k^2 e^{i k x} - B k^2 e^{-i k x})$$  

$$E\Psi = -\frac{\hbar^2}{2m}(-k^2)(A e^{i k x} + B e^{-i k x})$$  

where $$E$$ is the Energy (eigenvalue) and the wavefunction is returned (eigenfunction)  

$$E = \frac{\hbar^2 k^2}{2m}(A e^{i k x} + B e^{-i k x})$$  

The free particle has no boundaries and is not confined in space, the spatial frequency, $$k$$,  and $$E$$ values are not restricted and can be any number. Therefore, since they are not restricted, the system is not quantized.  

---

## Momentum Operator  

Define momentum ($$\rho$$) via the de Broglie relation where $$\lambda = \frac{2\pi}{k}$$ relating the wavelength ($$\lambda$$) to the spatial frequency ($$k$$).  

$$\rho = \frac{h}{\lambda}$$  

$$\rho = \frac{h}{\lambda} = h*k$$  

$$\frac{2\pi}{\lambda} = \hbar * k$$  

$$\rho = \hbar * k$$  

Momentum operator ($$\rho$$):  

The momentum operator makes changes to the wavefunction. Ask for momentum and get back the eigenfunction ($$\Psi$$) and eigenvalue ($$\rho$$) from operation.  

Confirm this with an example where $$\rho = \frac{\hbar}{i} \frac{d}{dx}$$.  

$$\hat{$$\rho} \Psi = $$\rho(A e^{i k x}) = \frac{\hbar}{i} \frac{d}{dx}(A e^{i k x}) = \frac{\hbar}{i}A(i k)e^{i k x} = \hbar k A e^{i k x} = $$\rho A e^{i k x}$$  

This returns the scalar momentum ($$\rho$$) times the eigenfunction ($$A e^{i k x}$$).  

---

Now confirm for $$\rho^2$$ where the Energy for classical physics is  

$$E = \frac{1}{2}mv^2 = \frac{\rho^2}{2m}$$  

$$\rho^2 = \left(\frac{\hbar}{i}\frac{d}{dx}\right)^2 = \frac{\hbar^2}{i^2}\frac{d^2}{dx^2} = -\hbar^2 \frac{d^2}{dx^2}$$  

$$\frac{d^2}{dx^2} = \nabla^2$$  

confirms that this is a reasonable match to classical physics  

$$\frac{p^2}{2m} = H = -\frac{\hbar^2}{2m} \nabla^2$$  

---
