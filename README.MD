# Shruthi XT mod

This modification is a clone of the popular Shruthi-1, a digital/analog hybrid MIDI monosynth. The author of the project, Emilie Gillette [Mutable Instruments](https://pichenettes.github.io/mutable-instruments-documentation/), has posted all the resources for this device in the repository of his profile [github.com](https://github.com/pichenettes). Documentation for the original project is available here [Mutable Instruments: NON Eurorack project](https://pichenettes.github.io/mutable-instruments-diy-archive/)

This modification is a completely changed design of the main board, as well as additional filter boards, which in turn also changed their design and board size.

Original filter boards are not suitable for this project. The entire design has been reduced and redesigned for SMD type electronic components, including all chips including the atmega644 processor.

This synthesizer design is still in development, but the main board and the smr4mk2 filter have already been tested for errors and functionality. In the future, the boards may be modified, but to a lesser extent. There may be minor changes in the location of connectors or some parts.

Main board dimensions 207.5 mm x 110 mm. Dimensions of the filter board are 55 mm x 85 mm.
For this project there was a need to redraw the electrical circuit for routing. In addition, a preliminary case and top panel have been created.
All listed files are posted as is in the repository resource files.

In the process of debugging the main board and the filter board, version numbering of changes was used. At the time of publication, the main board has an index of 0.4, the sm4mk2 filter board has an index of 0.2

## [Shruthi XT mod rev 0.4](https://github.com/ibizafm0/shruthi_xt_mod)  
Rev 0.4 main PCB
Front
[![](https://github.com/ibizafm0/shruthi_xt_mod/blob/main/shruthixtmod/mb_shrt_xt_rev0_4_img001.jpg)](https://github.com/ibizafm0/shruthi_xt_mod/blob/main/shruthixtmod/mb_shrt_xt_rev0_4_img001.jpg)

Rev 0.4 main PCB
Rear
[![](https://github.com/ibizafm0/shruthi_xt_mod/blob/main/shruthixtmod/mb_shrt_xt_rev0_4_img003.jpg)](https://github.com/ibizafm0/shruthi_xt_mod/blob/main/shruthixtmod/mb_shrt_xt_rev0_4_img003.jpg)

Rev 0.2 filter PCB SMR4MK2
Front
[![](https://github.com/ibizafm0/shruthi_xt_mod/blob/main/shruthixtmod/flt_shrt_xt_rev0_2_img001.jpg)](https://github.com/ibizafm0/shruthi_xt_mod/blob/main/shruthixtmod/flt_shrt_xt_rev0_2_img001.jpg)

Rev 0.2 filter PCB SMR4MK2
Rear
[![](https://github.com/ibizafm0/shruthi_xt_mod/blob/main/shruthixtmod/flt_shrt_xt_rev0_2_img002.jpg)](https://github.com/ibizafm0/shruthi_xt_mod/blob/main/shruthixtmod/flt_shrt_xt_rev0_2_img002.jpg)

Additional photos of a working prototype
========

[![](https://github.com/ibizafm0/shruthi_xt_mod/blob/main/shruthixtmod/photo_m001.jpg)](https://github.com/ibizafm0/shruthi_xt_mod/blob/main/shruthixtmod/photo_m001.jpg)
[![](https://github.com/ibizafm0/shruthi_xt_mod/blob/main/shruthixtmod/photo_m002.jpg)](https://github.com/ibizafm0/shruthi_xt_mod/blob/main/shruthixtmod/photo_m002.jpg)
[![](https://github.com/ibizafm0/shruthi_xt_mod/blob/main/shruthixtmod/photo_m003.jpg)](https://github.com/ibizafm0/shruthi_xt_mod/blob/main/shruthixtmod/photo_m003.jpg)


Description of changes
========

- The main pcb board of the device has the maximum possible minimum size, at which all controls will be conveniently located without interfering with each other when adjusting parameters. Knobs for potentiometers can have a maximum diameter of 10 mm.
- All input power circuits of the device, previously located on the filter pcb boards, are now routed to the main pcb board. Thus, the cost of the filter, as well as the complete device with several filters, is significantly reduced.
- Since the filter circuits now have fewer components and the main pcb board has been reduced in size, the filter pcb boards have been brought down to the basic standard of 55mm x 85mm, similar in size to a standard plastic card (yes, I want the filter be the size of a plastic card = ))
- The seat for the filter pcb board is designed for a larger pcb board size, in case you need to design some kind of extremely cool filter that would not fit into a standard 55 mm x 85 mm space. It is permissible to design pcb boards measuring 55 mm x 105 mm into the footprint.
- In the author's original version, the output sound volume can be adjusted in two ways: digital adjustment and analog adjustment. In order to switch sound control options, it was necessary to use a soldering iron and solder. In the same modification project, to switch adjustment options, it is enough to switch a pair of switches on the back of the main pcb board.
- All filters in the original design have settings for the output sound and filtering using changeover jumpers. In the modified version, linear sliding switches are installed instead of jumpers.

Upcoming of changes
========

- In the current version, a 4.0 mm x1.7 mm power port is installed on the main pcb board to power the device; it will be necessary to replace it with the more popular 5.5 mm x 2.1 mm.
- The 24-step encoders used in the modified version, for some strange circumstances, had different switching directions from batch to batch, and therefore it will be necessary to add additional contacts to change the polarity of the encoder adjustment.
- It is necessary to add seats for installing ferrite beads, in case of using an OLED display, to prevent interference.
- Need to consider adding spring mounting holes to accommodate the battery compartment. Portable use is an interesting idea, why not.
- Need add additional pins for in-circuit firmware of the 24lc512 memory chip.

