---
layout: posts
title:  "The Bug Attractor"
date:   2015-11-10 10:08:29 +0200
categories: tech
---

Farmed crops are lost in significant quantities each year due to a variety of pests. In South Africa, sugarcane is plagued by Eldana Saccharina (E. Saccharina), commonly known as the African sugarcane borer. In the 2012 season alone, R744-million of sugarcane crop was lost due to E. Saccharina.

The female E. Saccharina lay their eggs on the stalks of sugarcane. The damage occurs when these eggs pupate and bore into the stalk and degrade its quality. Current pest management strategies are not completely effective in minimising the E. Saccharina population in sugarcane fields. A novel, more effective method of using acoustics to control pests has thus been suggested.

The mating process of E. Saccharina involves the males of the species attracting females with a mating call. This is an ultrasonic call spanning 10 kHz to 120 kHz in frequency. Using current technology, it is possible to imitate this call at low cost.

The proposed plan was to design a device that could imitate the male mating call and lure the females to traps. Reducing the population of females would result in fewer pupae boring stalks. A system to lure female E. Saccharina was designed. This system included a device for recording the male calls and another device to play back those recordings. These devices were based on low cost 32-bit microcontrollers. A user interface was created using the GUIDE toolbox in Matlab. This interface was used for processing the recordings, and transferring them from the recording device to the playback device.

![Alt Text](/assets/images/bug-attractor-prototype.jpg)
Recording and playback device prototype.

The design of this system was successful. The prototype was able to save a short sound recording on its flash memory, and play it back in a similar manner to the male E. Saccharina.

![Alt Text](/assets/images/bug-attractor-soundwave.png)
Recorded soundwave of a male E. Saccharina specimen.
