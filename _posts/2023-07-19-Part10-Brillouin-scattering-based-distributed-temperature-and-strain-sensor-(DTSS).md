---
title: "Part10-Brillouin scattering based distributed temperature and strain sensor (DTSS)"
mathjax: true
layout: post
---
Brillouin scattering occurs when light interacts with acoustic phonons, which are material waves describing the vibrations of atoms affected by mechanical waves. When a pressure wave propagates through the material, it causes certain areas to compress and others to expand, and the pattern repeats over and over. When light interacts with this pressure wave or acoustic wave, it scatters light in a specific direction and frequency, governed by momentum conservation.

The frequency and direction of the incident light and acoustic wave differ. According to the Doppler effect, the scattered light may have a higher or lower frequency. When the acoustic wave approaches the incident light, the scattered light has a higher frequency, known as anti-Stokes Brillouin scattering. Conversely, when the acoustic wave moves away from the incident light, the scattered light has a lower frequency, known as Stokes Brillouin scattering.

In optical fibers, the frequency difference between the incident light and Stokes or anti-Stokes scattering is equal to \\(2nV_a/\lambda)\\). As the acoustic wave in the optical fiber is influenced by both temperature and strain, the Brillouin scattering frequency shift changes accordingly.

<div align="center">
<a href="url"><img src="https://raw.githubusercontent.com/haleywuhuan/profile/master/assets/blog10_fig1.jpg" align="center" width="800"></a>
</div>

The sensitivity of the Brillouin frequency shift to temperature and strain follows a linear relationship, and the slope represents the coefficient of the optical fiber's sensitivity to temperature and strain. Since the frequency shift is affected by both temperature and strain, addressing this cross-sensitivity is crucial.

Several methods can be used to solve this problem. One approach is to use two identical optical fibers and keep one fiber in a loose condition to measure temperature only. Then, the measured temperature can be used to compensate for the measurement result from the fiber affected by both temperature and strain. Another solution involves using a single fiber and employing a Raman scattering-based distributed temperature sensor to measure the temperature first. This measured temperature value can then be substituted into the Brillouin frequency shift measurement.

The Brillouin spectrum provides valuable information for determining the central frequency of the Brillouin scattering and obtaining the corresponding temperature or strain information by knowing the fiber's temperature or strain coefficient. By addressing the cross-sensitivity and utilizing Brillouin scattering, optical fiber sensors can accurately and effectively measure temperature and strain for various applications.

<div align="center">
<a href="url"><img src="https://raw.githubusercontent.com/haleywuhuan/profile/master/assets/blog10_fig2.jpg" align="center" width="800"></a>
</div>

[Next Part11](https://haleyhw.github.io/web/Part11-Applications-of-DOFSs/)

**Reference**
1. [https://en.wikipedia.org/wiki/Brillouin_scattering](https://en.wikipedia.org/wiki/Brillouin_scattering)
2. Hartog A H. An introduction to distributed optical fiber sensors. CRC press, 2017.
