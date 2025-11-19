---
title: Radial Wavefunctions of the Hydrogenic Atom
layout: default
author: Reagan McNeill Womack
nav_exclude: false # excludes file from navigation
nav_order: 14
---

# The Radial Wavefunctions of the Hydrogenic Atom
The **Radial Wavefunction**, $$R(r)$$, described how an electron's behavior changes with its distance ($$r$$) from the nucleus. Unlike the <span class="blue bold">Radial Distribution Function</span>[^1] ($$P(r)$$) which tells us the *probability of finding an electron at a given radius*, $$R(r)$$ is the mathematical function whose square gives the *probability density* at that point.

Understanding $$R(r)$$ provides the foundation for visualizing and calculating the most important properties of the electron in an atom, directly linking the quantum numbers to the size and shape of the orbital.

For brevity sake, we will focus on taking the full form of the radial wavefunction and applying it to 1s, 2s, and 2p atomic orbitals.

Full Form of the Radial Wavefunction
{: .label .section-label .label-green }

The full mathematical expression for the radial wavefunction is rather complex, but it can be simplified into three multiplicative factors:

$$R_{n,l}(r) = \underbrace{N_{n,l}}_{\substack{\text{Normalization}}} \times \underbrace{\rho^l}_{\substack{\text{Near Nucleus}}} \times \underbrace{L_{n,l}(\rho)}_{\substack{\text{Bridging Polynomial}}} \times \underbrace{e^{-\rho/2}}_{\substack{\text{Far from Nucleus}}}$$

The **Associated Laguerre polynomial** ($$L_{n,l}(\rho)$$) is the term that makes the function oscillate and accounts for the **radial nodes**. A **radial node** is a spherical surface with fixed radius $$r$$ where the radial wavefunction $$R(r)$$ passes through, meaning the probability of finding the electron at that specific distance is zero. The number of radial nodes for any orbital is given by the formula

$$n-l-1$$

<hr class="dashed blue">

Examples of Radial Wavefunctions
{: .label .section-label .label-blue }

To simplify the expressions a bit, we define the dimensionless distance:

$$\rho = \frac{2Zr}{na_0}$$

| **Orbital** | **Quantum Numbers** | **Radial Wavefunction** |
|:--- | :--- | :---|
| 1s | <span>$$n=1, \ l=0$$</span> | <span>$$R_{1,0}(r) = \left(\frac{Z}{a_0}\right)^{3/2} \cdot 2e^{-\rho/2}$$</span> |
| 2s | <span>$$n=2, \ l=0$$</span> | <span>$$R_{2,0}(r) = \frac{1}{\sqrt{2}} {\left( \frac{Z}{a_0} \right)}^{3/2} \cdot (2-\rho)e^{-\rho/2}$$</span> |
| 2p | <span>$$n=2, \ l=1$$</span> | <span>$$R_{2,1}(r) = \frac{1}{\sqrt{24}} {\left( \frac{Z}{a_0} \right)}^{3/2} \cdot \rho e^{-\rho/2}$$</span> |

---
<!--- add footnotes here --->
*For further details on the derivation of the radial wavefunction, see [this](https://chem.libretexts.org/Bookshelves/Physical_and_Theoretical_Chemistry_Textbook_Maps/Free_Energy_1e_(Snee)/15%3A_The_Hydrogen_Atom/15.03%3A_Hydrogen_Radial_Wavefunctions) article.[^2]*

[^1]: [Radial Distribution Function](../docs/radial-distribution-function.html)\
[^2]: Hydrogen Radial Wavefunctions; Preston Snee, University of Illinois Chicago. [Chemistry LibreTexts](https://chem.libretexts.org/Bookshelves/Physical_and_Theoretical_Chemistry_Textbook_Maps/Free_Energy_1e_(Snee)/15%3A_The_Hydrogen_Atom/15.03%3A_Hydrogen_Radial_Wavefunctions)
