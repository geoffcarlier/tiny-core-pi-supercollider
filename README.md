# tiny-core-pi-supercollider
Notes and Scripts to build and run SuperCollider on a Pi Zero w with Tiny Core Linux

## Useful reading and influences:

#### Tiny Core on pi - getting wifi working
https://gist.github.com/BillyNate/13732d02c41378f1c630fa914fe63378

#### Building SuperCollider
https://fredrikolofsson.com/f0blog/building-supercollider-for-picore-linux-2/

#### Realtime
https://www.kernel.org/doc/Documentation/scheduler/sched-rt-group.txt
https://github.com/jackaudio/jackaudio.github.com/wiki/Cgroups

## Aims
This project takes the work of Fredrik Olofsson but upgrades to Tiny Core Linux 16.  
This includes realtime support to improve sound stability.
Ultimately battery powered sound devices are the target.  Tiny Core offers an improved power consumption over Rasberry OS or other heavier weight distro.  

## Hardware
- Computer device (currently MacOS)
- Raspberry pi zero w
- SD Card
- USB DAC (Terratek - AureonDualUSB)
