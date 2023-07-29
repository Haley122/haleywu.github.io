---
title: "Part6-Principle of photodiode"
mathjax: true
layout: post
---
The photodiode is a fundamental component of modern electronics and communication systems. The function is converting light into electrical signals and it is based on the photoelectric effect. 

**Photoelectric effect**     
The phenomenon occurs when light illuminates a metal plate, causing electrons to be ejected from its surface. Contrary to common belief, the probability of electron emission is not governed by the intensity of light but rather by its frequency. If the energy of a photon \\((hv)\\) exceeds the energy required to release an electron from the plate, the electron will be emitted with Kinetic energy \\((E_k)\\). 

Theoretically, a metal plate could serve as a photodiode; however, it would only be effective for very high frequencies, such as ultraviolet light. With the advent of semiconductor technology, scientists utilized the unique properties of PN junctions to create photodiodes with broader light wavelength ranges.

<div align="center">
<a href="url"><img src="https://raw.githubusercontent.com/haleywuhuan/profile/master/assets/blog6_fig1.jpg" align="center" width="450"></a>
</div>

**PN Junctions**     
Semiconductors, a class of materials lying between conductors and insulators, provide the foundation for modern electronics. Silicon, a widely used semiconductor, has 14 electrons and 4 electrons are in its outermost shell. When it crystallizes, each silicon atom shares its outermost electrons, therefore, it seems every atom has eight electrons in its outermost shell. This balanced state results in low conductivity for pure silicon.

However, by introducing specific atoms, such as phosphorus (P) or boron (B), into the silicon crystal, we can modify its conductivity. Phosphorus (P), with five outer shell electrons, creates an excess electron in the crystal, giving rise to an N-type semiconductor. On the other hand, boron (B), with three outer shell electrons, generates 'holes' where electrons are effectively missing, making it a P-type semiconductor. Despite their differing conductivities, both N-type and P-type semiconductors maintain electrical neutrality with equal numbers of electrons and protons. 

<div align="center">
<a href="url"><img src="https://raw.githubusercontent.com/haleywuhuan/profile/master/assets/blog6_fig2.jpg" align="center" width="600"></a>
</div>

When a N-type semiconductor and a P-type semiconductor are brought together, a PN junction is formed. Electrons from the N-type region migrate to the P-type region due to diffusion, where they combine with holes. This combination establishes an electrical field between the two regions, forming a depletion region with no mobile charge carriers. 

By connecting an electrical circuit to the PN junction, the photodiode can operate. In a positive bias, the electrical field from the external circuit partially cancels out the internal field, reducing the width of the depletion region. Conversely, a reverse bias increases the width of the depletion region. When light is directed onto the depletion region in the reverse bias condition, electron-hole pairs are separated and guided by the electrical field. The directed movement of electrons forms the current and is called photocurrent in this case.

<div align="center">
<a href="url"><img src="https://raw.githubusercontent.com/haleywuhuan/profile/master/assets/blog6_fig3.jpg" align="center" width="450"></a>
</div>

[Next Part7](https://haleyhw.github.io/web/Part7-Scattering-phenomena-in-optical-fiber/)

**Reference**
1. [https://en.wikipedia.org/wiki/Photoelectric_effect](https://en.wikipedia.org/wiki/Photoelectric_effect)
