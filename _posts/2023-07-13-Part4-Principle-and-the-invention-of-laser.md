---
title: "Part4-Principle and the invention of laser"
mathjax: true
layout: post
---
Laser, stands for Light Amplification by Stimulated Emission of Radiation. The name indicates the fundamental principle is stimulated emission. This concept was first proposed by Einstein in 1916. Before Einstein's theory, scientists were familiar with spontaneous emission, which accounts for light emission from natural sources like sunlight or artificial sources like candles and light bulbs. Spontaneous emission occurs as follows. Assume we have a two-level energy system, an electron transits from a higher energy state to a lower energy state, emitting energy in the form of a photon. The emitted light has random direction, phase, and polarization, explaining why light from bulbs lacks directionality. Einstein's stimulated emission theory revolutionized our understanding of light. The process of stimulated emission is as follows, in a similar situation to spontaneous emission, if a photon with energy precisely matches the energy \\((hv)\\) required for the electron transition to interact with the electron, a remarkable phenomenon occurs. The electron is stimulated to transition back to the lower energy state, releasing an additional photon that is identical to the incident photon in terms of frequency, direction, phase, and polarization. 

<div align="center">
<a href="url"><img src="https://raw.githubusercontent.com/haleywuhuan/profile/master/assets/blog4_fig1.jpg" align="center" width="700"></a>
</div>

**The Invention of Laser**     
When Einstein initially proposed the theory of stimulated emission, he could hardly imagine the groundbreaking invention it would lead to. It was not until 1960 that Theodore H. Maiman constructed the world's first laser, using a synthetic ruby crystal as the gain medium. This invention marked the birth of the laser age and revolutionized various fields of science, medicine, communications, and industry. 

Maiman's pioneering device, known as the ruby laser, was a masterpiece of engineering. Ruby is a three-level energy system, simplied in the diagram below. Within the ruby crystal, there were \\(N1\\)electrons in the \\(E1\\) state, \\(N2\\) electrons in the \\(E2\\) state, and \\(N3\\) electrons in the \\(E3\\) state. Under normal conditions, the majority of electrons resided in the lower energy state, \\(E1\\), with only a few in the higher energy states, \\(E2\\), \\(E3\\).

To initiate the lasing action, Maiman pumped energy into ruby crystals. This energy absorption prompted some electrons to transition to the higher energy level, \\(E3\\). However, the \\(E3\\) level was unstable, and electrons quickly returned to the \\(E2\\) state, with a short lifetime of approximately \\(10^-8\\) seconds. As a result, more electrons accumulated in the $E2$ state than left it. This unique scenario, where the higher energy level \\(E2\\) had a larger number of electrons than the lower energy level \\(E1\\), is known as population inversion. 

With population inversion achieved, Maiman's ruby laser was primed for lasing. When electrons in the \\(E2\\) state fell back to the \\(E1\\) state and spontaneously emitted photons, these photons triggered the process of stimulated emission. According to Einstein's theory, these emitted photons would have the same frequency, phase, and polarization as the incident photons, resulting in a cascaded of stimulated emissions. This chain reaction amplified the intensity of the emitted light, producing a coherent laser beam. 

The transmittance spectrum and emission wavelengths of ruby are depicted in the following figure. Notable absorption peaks at 400nm and 550nm can be observed. The ruby emission wavelength range is 692.7nm to 694.3nm. The key to the laser's invention lies in the process of stimulated emission. However, this alone is not sufficient. Another equally crucial element is the resonant cavity. 

<div align="center">
<a href="url"><img src="https://raw.githubusercontent.com/haleywuhuan/profile/master/assets/blog4_fig2.jpg" align="center" width="700"></a>
</div>

**The role of resonant cavity**     
A resonant cavity is formed by placing two mirrors on opposite sides of the ruby crystal. One mirror is coated with 99.9% silver, while the other is coated with 99% silver to allow some of the light to emit out. The resonant cavity serves two critical functions:
1. Narrowing the laser wavelength
The resonant cavity significantly narrows the range of wavelengths emitted by the laser. Only those wavelengths that satisfy the condition of the cavity length being equal to an integer multiple of half a wavelength \\((L=n*\lambda/2)\\) can survive. As a result, considering both the gain medium's spectrum and the wavelengths permitted by the cavity, only one specific wavelength will ultimately survive, resulting in a highly monochromatic laser output.

2. Providing amplification to the light
The resonant cavity also contributes to further amplifying the light. Suppose the one-way gain of light in the ruby is 10%. After 30 trips back and forth within the cavity, the light can be amplified by more than 17 times. This repeated amplification process enhances the intensity of the laser. While this might lead one to believe that the power of the laser output could grow infinitely, there are limitations. In reality, the power of the laser output is determined by the balance between the gain and loss within the gain medium. Here is why. As the number of photons in the cavity increases, more electrons in the excited state are required to sustain the amplification process. However, if there are insufficient electrons at the excited state, the gain provided by the gain medium diminishes. Eventually, the loss of the gain medium to photons equals the gain provided by the gain medium, leading to a steady state. At this point, the power of the laser output stabilizes and cannot be further increased. 

In summary, the invention of a laser hinges on two essential components: the stimulated emission and the design of an efficient resonant cavity. 

<div align="center">
<a href="url"><img src="https://raw.githubusercontent.com/haleywuhuan/profile/master/assets/blog4_fig3.jpg" align="center" width="700"></a>
</div>

**Historical stories behind laser invention**    
The journey to the invention of the laser is filled with fascinating stories of brilliant minds and their quest for scientific breakthroughs. As we mentioned earlier, Theodore H. Maiman was the inventor of the first laser in 1960. Mainman's work with the ruby laser earned him two Nobel Prize nominations. However, the Nobel Prize was awarded to three other scientists, Charles Townes, Nikolay Basov, and Alexander Prokhorov for their foundation work in the maser-laser principle. Another notable figure in the history of the laser's invention is Gordon Gould. As a Ph.D. student at Columbia University during the 1950s, Gould was in the same department as Charles Towns. While Gould was pursuing his doctoral studies, he showed an extraordinary vision for the commercial potential of the laser. Driven by his entrepreneurial instincts, he made the bold decision to abandon his Ph.D. program and venture into independent research on lasers. In 1959, Gould filed a patent application detailing the concept of laser, including the resonant cavity. However, the patent was not granted, leading to a nearly 30-year legal battle. Finally, in 1985, he won the legal war, which brought him significant financial success. The history was vividly depicted in the book, "Beam: The Race to Make the Laser". This book offers an exploration of scientific discoveries, the rivalry among researchers, and the intriguing personal stories that shaped the development of technology. If you are curious about the tales behind the laser invention, this book is highly recommended.

[Next Part5](https://haleyhw.github.io/web/Part5-Invention-of-optical-fiber/)

**Reference**
1. [https://en.wikipedia.org/wiki/Stimulated_emission](https://en.wikipedia.org/wiki/Stimulated_emission)
2. Hecht J. Beam: the race to make the laser. Optics and photonics news, 2005.
3. Hammack W S, Ryan P, Ziech N. Eight Amazing Engineering Stories: Using the Elements to Create Extraordinary Technologies. Articulate Noise Books, 2012.



