---
title: Classical Vibration
layout: default
author: Hans Kindstedt
nav_order: 7
---

# Hooke's Law
Let's imagine a ball with mass $$m$$ attached to an immovable wall by a spring. The only force that acts upon the ball is the force exerted by the spring. 

<p align="center"><img src="assets/images/Classical Spring.jpg" width="250"></p>

The force applied on the ball by the spring can be described by the equation $$F=-k_{f}x$$. $$k_{f}$$ is the force constant of the spring which is dependant on the spring itself and $$x$$ describes the position of the ball in relation to the spring's equilibrium point $$(x=0)$$. This intuitively makes sense. As you pull the ball in the $$+x$$ direction away from the wall, the spring resists pulling it back in the $$-x$$ direction and vise versa. 

The force can also be described using Newton's second law of motion as $$F=ma$$. Acceleration (a) can also be described as the derivative of velocity (v) or the double derivative of position (x) with respect to time. When combined with the spring equation, we get the following equation:

$$-k_{f}x=ma=m\frac{dv}{dt}=m\frac{d^{2}x}{dt^{2}}$$

All of the aforementioned equations describe the force applied on the mass by the spring but not the position of the mass as a function of time. The equation for that is as follows:

$$x(t)=A\sin{(2\pi\nu t)}=A\sin{(\sqrt{\frac{k_{f}}{m}}t)} = x(t)=A\sin{(\omega t)}$$
>Note: $$\nu = \frac{1}{2\pi}\sqrt{\frac{k_{f}}{m}}$$ and $$\omega=\sqrt{\frac{k_f}{m}}$$

>$$\nu$$ is the frequency of the vibration in terms of cycles per time while $$\omega$$ is the amount of radians travelled per time.

To prove that this equation accurately describes the ball's position, we can plug it in to our spring equation for force and solve like so:

$$F=ma=m(A\sin{(\sqrt{\frac{k_{f}}{m}}t)})\frac{d^{2}x}{dt^{2}}=\sqrt{\frac{k_{f}}{m}}mA\cos{(\sqrt{\frac{k_{f}}{m}}t)}\frac{dx}{dt}=-{k_{f}}A\sin{\sqrt{\frac{k_{f}}{m}}t)}=-{k_{f}}x(t)$$

You can see the result is consistent with our equation from before ($$F=ma=-k_{f}x$$) verifying our chosen function $$x(t)$$. 

## Potential derivation
To find the ball's potential in relation to its position, we begin with the following expression:

$$E=\int^{x}_{0}Fdx$$

The energy of the system is equal to the sum of the force applied by the spring over the distance the ball travelled. Taking the derivative of each side gives us the change in energy over the distance travelled:

$$dE=Fdx$$

The potential of the ball is defined as the negative value of this energy as the spring pulls the ball in the opposite direction and we can plug in our spring equation for force to arrive at:

$$dv=-fdx=k_{f}xdx$$

We then integrate both sides to get the potential of the ball.

$$V=\frac{1}{2}k_{f}x^{2}$$



---