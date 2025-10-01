---
title: Particle in a Ring
layout: default
author: Juliette 
nav_order: 10
---

# Particle in a Ring
## Hamiltonian
### Coordinate System
#### Quantization

Assume a system where a particle lives on a ring of radius, \(r\), where there is zero potential because for all coordinates, 

$$H = - \frac{\hbar^{2}}{2m} \frac{d^{2}}{dx^{2}}$$  

Therefore, the Hamiltonian of the particle of the ring would be as follows, where the coordinate system is not represented in terms of $$r$$ and $$\phi$$:  

$$H = - \frac{\hbar^{2}}{2m} \left(\frac{d^{2}}{dx^{2}} + \frac{d^{2}}{dy^{2}}\right)$$  

$$= - \frac{\hbar^{2}}{2mr^{2}} \frac{d^{2}}{d\phi^{2}}$$  

$$= - \frac{\hbar^{2}}{2I} \frac{d^{2}}{d\phi^{2}}$$  

where \(I =\) moment of inertia.  

---
![Wavefunction representation](assets/wavefunction.png)
The blue squiggle line is a representation of the wavefunction.  

$$H \Psi = E \Psi$$  

$$e^{i m_{l} \phi}$$  

Use Euler’s function to rewrite as:  

$$e^{i m_{l} \phi} = \cos(m_{l} \phi) + i \sin(m_{l} \phi)$$  

---
![Cosine and sine phase shift](assets/phase_shift.png)
This shows that the wave oscillates with a phase shift of \(90^{\circ}\), represented as real and imaginary. Both waves oscillate with the same frequency but it looks like cos precedes sin by \(\pi/2\).  

Show that \(e^{i m_{l} \phi} = \cos(m_{l} \phi) + i \sin(m_{l} \phi)\) is an eigenfunction of the Hamiltonian.  

$$H \Psi = - \frac{\hbar^{2}}{2I} \frac{d^{2}}{d\phi^{2}} \left(e^{i m_{l} \phi}\right)$$  

$$H \Psi = - \frac{\hbar^{2}}{2I} \frac{d}{d\phi} \left(i m_{l} e^{i m_{l} \phi}\right)$$  

$$H \Psi = - \frac{\hbar^{2}}{2I} \left(- m_{l}^{2} e^{i m_{l} \phi}\right)$$  

$$H \Psi = \frac{\hbar^{2} m_{l}^{2}}{2I} e^{i m_{l} \phi}$$  

$$= \frac{\hbar^{2} m_{l}^{2}}{2I} \Psi$$  

Where  $$E = \frac{\hbar^{2} m_{l}^{2}}{2I}$$ for a particle in a ring. At this time, there is no quantization because there are no restrictions or boundaries. A restriction must be set to achieve quantization: the wave must meet smoothly and continuously, or the wavefunction must start and end in the same place as seen in the wavefunction figure above. Therefore for a ring where the phase \(\phi\) ranges from \(0\) to \(2\pi\), a wavefunction at a given angle \(\phi\) must be equal to the wavefunction at \(\phi + 2\pi\).  

$$\Psi(\phi) = \Psi(\phi + 2\pi)$$  

---

If the wavefunction is defined as $$\Psi = e^{i m_{l} \phi}$$ then how does this new restriction ($$\Psi(\phi) = \Psi(\phi + 2\pi)$$) lead to quantization? Note: the wavefunction is now in spherical coordinates. 

Plug $$\Psi = e^{i m_{l} \phi}$$ into $$\Psi(\phi) = \Psi(\phi + 2\pi)$$  

$$e^{i m_{l} \phi} = e^{i m_{l} (\phi + 2\pi)}$$  

$$= e^{i m_{l} \phi} \cdot e^{2\pi i m_{l}}$$  

$$1 = e^{2\pi i m_{l}}$$  

$$1= (e^{i \pi})^{2 m_{l}}$$  

$$1= (-1)^{2 m_{l}}$$  

Therefore:  

$$m_{l} = ..., -2, -1, 0, 1, 2, ...$$  

---

In order for $$1= (-1)^{2 m_{l}}$$ to equal each other then \(m_{l}\) must equal any whole number. Because of this restriction we get our \(m_{l}\) which is a quantum number and demonstrates the quantization of the particle on a ring.  

---
