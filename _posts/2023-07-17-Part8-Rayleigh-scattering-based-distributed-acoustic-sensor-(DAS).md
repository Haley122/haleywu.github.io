---
title: "Part8-Rayleigh scattering based distributed acoustic sensor (DAS)"
mathjax: true
layout: post
---
Rayleigh scattering is a phenomenon caused by the atomic structure of glass and is almost unavoidable. As a result, one of the most common uses of Rayleigh scattering is to measure the loss of optical fiber. A typical Rayleigh scattering profile is depicted in the following. The slope in the profile represents the loss coefficient of the fiber, and any additional dips indicate extra losses, such as bending or poor connections. This technology is known as an optical time-domain reflectometer (OTDR).

<div align="center">
<a href="url"><img src="https://raw.githubusercontent.com/haleywuhuan/profile/master/assets/blog8_fig1.jpg" align="center" width="600"></a>
</div>

In addition to characterizing the loss of optical fiber, researchers later discovered that when using a highly coherent laser and demodulating the phase of the Rayleigh scattering, it is possible to measure strain changes in the fiber. The principle behind this lies in the phase change between two positions, which is given by \\(4pin(z_c-z_a)/\lambda)\\). If there is no strain change between positions (a) and (c), the phase difference will remain constant. However, if there is a strain change between these positions, both the refractive index and the distance between them will be modified, following a linear relationship. By demodulating the phase difference between (a) and (c), we can derive the strain change of the optical fiber. Fig. 3 shows a typical signal collected from a Rayleigh-based distributed acoustic sensor. The plot is two-dimensional, with one axis representing time and the other axis representing fiber length. Notably, at the 1km position, there is a clear vibration signal.

It is worth mentioning that although this technology is called a distributed acoustic sensor, it primarily measures strain changes rather than acoustic waves. This is because acoustic waves are pressure waves, and optical fiber, being made of glass, is not highly sensitive to pressure. The term distributed acoustic sensor may have been adopted to facilitate better communication with non-technical staff, as it allows one to illustrate the technology's capability by describing it as a system that can effectively turn the optical fiber into thousands of virtual microphones.

<div align="center">
<a href="url"><img src="https://raw.githubusercontent.com/haleywuhuan/profile/master/assets/blog8_fig2.jpg" align="center" width="700"></a>
</div>

**Reference**     
1. [https://en.wikipedia.org/wiki/Rayleigh_scattering](https://en.wikipedia.org/wiki/Rayleigh_scattering)
2. Hartog A H. An introduction to distributed optical fiber sensors. CRC press, 2017.

