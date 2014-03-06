Mako DSP
=======

Open Source Audio DSP Platform for engineers, makers, DIYers, and musicians. The goal of the project aims to provide a hardware platform and software library to enable easy implementation of audio DSP systems. Building off the popularity of the Arduino project Mako DSP is Arduino shield compatible, featurng a set of headers like the Leonardo board. It was decicded to support Arduino shields to help diversify the Mako DSP's pontial applications that extend beyond standard audio DSP applications. The Arduino Leonardo header set was chosen since the Leonard is an experimental model, Mako DSP is still very much in develoment so it is considered experimental as well. THe Mako DSP is powered by a unique asymmetrical dual core ARM Cortex M4F MCU, the NXP LPC4337, which has a Cortex M4F core and an M0 core in the same package. Being dual core will allow Mako DSP to process audio signals in real time but also act as a controller simultaneously. The sources for the hardware platform and software are available as FOSS here on Github.

Mako DSP Board Prototype 1.0 Specs:
- NXP LPC4337 ARM Cortex M4F/M0 204MHZ Asymmetrical Dual-Core
- Arduino Leonardo Hardware Compatible Pinout
- Two 10 pin additional GPIO banks for more I/O
- Wolfson Audio WM8778 24 Bit 96KHZ In/Out Audio Codec
- microSD Card Slot
- USB 2.0 w/ OTG and Host Support
- Dedicated Analog and Digital Supplies for clean audio
- Real time DSP Capable

Updated Prototype 1.6:

![Prototype Design 1.6](/Hardware/PCB/MakoDSP_P1.6.png)


Prototype Design 1.0:

![Prototype Design 1.0](/Hardware/PCB/Mako%20DSP%20P1.png)



Update:
Mako DSP has been in development since August 2013, the first prototype design was completed in october 2013, development stopped from the end of october until lay January 2014. No prototypes have been manufactured as of yet. I have been doing a lot of thinking about what sort of audio processing I want the Mako to be able to do and thinking about how that will affect the design. For a long while even at the start of the project I was considering external memory. External memory would allow for many more possibilities, the only issues is that it needs more pins. THe decision has been made to swtich over the to the BGA256 package for the LPC4337 and add an external SDRAM module. These are huge changes and will require a complete redesign of the hardware but its the right direction to go in. Stay tuned folks!


Created and Designed by Adam J. Vadala-Roth
MakoDSP founded by Adam J. Vadala-Roth

NOTE: Currently in active development

Released as 100% Open Source under
Creative Commons Attribution-ShareAlike 3.0 Unported License
http://creativecommons.org/licenses/by-sa/3.0/us/

