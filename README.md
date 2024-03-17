# Shruthi XT mod

This modification is a clone of the popular Shruthi-1, a digital/analog hybrid MIDI monosynth. The author of the project, Emilie Gillette [Mutable Instruments](https://pichenettes.github.io/mutable-instruments-documentation/), has posted all the resources for this device in the repository of his profile [github.com](https://github.com/pichenettes). Documentation for the original project is available here [Mutable Instruments: NON Eurorack project](https://pichenettes.github.io/mutable-instruments-diy-archive/)

This modification is a completely changed design of the main board, as well as additional filter boards, which in turn also changed their design and board size.

Original filter boards are not suitable for this project. The entire design has been reduced and redesigned for SMD type electronic components, including all chips including the atmega644 processor.

This synthesizer design is still in development, but the main board and the smr4mk2 filter have already been tested for errors and functionality. In the future, the boards may be modified, but to a lesser extent. There may be minor changes in the location of connectors or some parts.

Main board dimensions 207.5 mm x 110 mm. Dimensions of the filter board are 55 mm x 85 mm.
For this project there was a need to redraw the electrical circuit for routing. In addition, a preliminary case and top panel have been created.
All listed files are posted as is in the repository resource files.

In the process of debugging the main board and the filter board, version numbering of changes was used. At the time of publication, the main board has an index of 0.4, the sm4mk2 filter board has an index of 0.2

## [Aciduino V1](https://github.com/midilab/aciduino/tree/master/v1/)  
2 Tracks TB303 sequencer and MIDI Controller.

V1 on PCB
[![](https://midilab.co/data/uploads/2022/05/aciduino_mk2-1024x632.jpg)](https://midilab.co/data/uploads/2022/05/aciduino_mk2.jpg)

V1 on Protoboard
[![](https://midilab.co/data/uploads/2023/03/aciduinov1-1024x576.jpg)](https://midilab.co/data/uploads/2023/03/aciduinov1.jpg)

## [Aciduino V2](https://github.com/midilab/aciduino/tree/master/v2/)  
Up to 16 Tracks TB303/TR808 sequencer with step, pattern and mute automation grid system, MIDI Controller, OLED display and extensible modular design to plug more potentiometers, buttons, MIDI or CV/Gate interfaces.

V2 on Protoboard
[![](https://midilab.co/data/uploads/2023/01/aciduino_v2_teensy_bb-1024x696.jpg)](https://midilab.co/data/uploads/2023/01/aciduino_v2_teensy_bb-scaled.jpg)

V2 on PCB(prototype)
[![](https://midilab.co/data/uploads/2023/03/uone_umodular-scaled.jpg)](https://midilab.co/data/uploads/2023/03/uone_umodular-scaled.jpg)

Features
========

### 303/808 Step Sequencer clone

Programming bass and drum steps using same analogy of original machines • Save your pattern work on microcontroller EPPROM memory for later live gigs • Use step length and shift to make some unusual sequences • Automation grid system for step edit, pattern navigation and mute tracks • Realtime and Step record modes for MIDI keyboard input(v2 only)

### Professional grade Clock

Tight and solid clock system using hardware timers to achieve realtime professional grade tick system • Send or receive clock to keep all your external equipment synced

### Generative Engine

Generate new and fresh acid music patterns by pressing a single button and twist some parameters • Harmonizer to force musical harmonic modes for bass lines • Euclidian generator for drum parts

### Midi Controller

Controls up to 16 parameters per track of your external synthesizers(bass/drums) • Midi learn(v2 only) • 16 potentiometers modular support to extend aciduino as midi controller(v2 only)

### Pattern memory

Store your patterns conveniently on the microcontroller's EEPROM, allowing you to access them effortlessly during live performances.

# Easy and fast Assembly

1 or 2 hours assembly time on protoboard. 

[V1 Assembly](https://github.com/midilab/aciduino/tree/master/v1)

[V2 Assembly](https://github.com/midilab/aciduino/tree/master/v2#assembly)
