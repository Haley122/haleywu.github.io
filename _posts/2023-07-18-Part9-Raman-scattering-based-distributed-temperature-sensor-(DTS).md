---
title: "Part9-Raman scattering based distributed temperature sensor (DTS)"
mathjax: true
layout: post
---
Raman scattering occurs when light interacts with optical phonons, which are material waves describing the collective vibration of atoms. This phenomenon is known as inelastic scattering, indicating that there is an energy exchange between the incident photon and the optical phonon. Raman scattering results in two outcomes: Stokes and anti-Stokes processes.

In the Stokes process, when electrons are in a lower energy state, they absorb energy from the incident photon and transition to a higher energy level. Later, they fall back to a state higher than their initial one, causing the emitted photon to have a lower frequency than the incident photon. This emitted light is called Stokes.

On the other hand, in the anti-Stokes process, the electrons' initial energy level is higher than the final energy level. Consequently, the electrons gain energy, and the anti-Stokes wave has a higher frequency than the incident wave.

<div align="center">
<a href="url"><img src="https://raw.githubusercontent.com/haleywuhuan/profile/master/assets/blog9_fig1.jpg" align="center" width="700"></a>
</div>

The utilization of Raman scattering in temperature measurement stems from Boltzmann's law, which states that the probability of an atom being in an energy state is proportional to \\(exp(-\epsilon<sub>i</sub>/kT)\\). Moreover, the ratio of atoms in energy states i and j is proportional to \\(exp(-(\epsilon<sub>i</sub>-\epsilon<sub>j</sub>)/kT))\\). Therefore, for two fixed energy levels i and j, at higher temperatures, a larger number of atoms will be in the higher energy level.

\\((E<sub>i</sub>-E<sub>j</sub>)\\)

\\(E<sub>i</sub>\\)-\\(E<sub>j</sub>\\)

By considering the Stokes and anti-Stokes processes with Boltzmann's law, we find that the anti-Stokes process is more sensitive to temperature. Researchers have discovered that the sensitivity of anti-Stokes is about 0.8%/&deg;C, while the sensitivity of Stokes is about 0.1%/&deg;C. Based on this relationship, we can employ Raman scattering for distributed temperature measurement. Temperature information can be derived from either Stokes, anti-Stokes, or their ratio.

It is important to note that Raman scattering-based distributed temperature sensors may not respond well to extremely low temperatures, and this can also be explained by Boltzmann's law. However, the measurement temperature range is sufficient for most industrial applications.

<div align="center">
<a href="url"><img src="https://raw.githubusercontent.com/haleywuhuan/profile/master/assets/blog9_fig2.jpg" align="center" width="700"></a>
</div>

**Reference**
1. [https://en.wikipedia.org/wiki/Raman_scattering](https://en.wikipedia.org/wiki/Raman_scattering)
2. Hartog A H. An introduction to distributed optical fiber sensors. CRC press, 2017.


