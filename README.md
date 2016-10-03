# dHPC

## What is this?

dHPC stands for deltaHacker PC and it's a small **home-brew** computer. It's not only small
in size, but in performance too! The capabilities of this tiny system resemble those of the 80's
home computers. It was built as a project for [deltaHacker magazine][delta], an ethical hacking
magazine, that occasionally hosts articles about electronics.

## What can I do with it?

The computer.* files in this repository were created with [Eagle][eagle], a popular choice for
PCB design among makers and students. In order to view the schematics or the PCB, you need to
download the free version of the program. Alternatively, you could use the on-line viewer that
many board manufacturers facilitate on their websites. You can find a noteworthy viewer of this
kind at [EuroCircuits][euro].

## Is it possible to make one?

Of course it is! Keep in mind, though, that the three microcontrollers which comprise the system
need to be "burnt" with the appropriate firmware. This means You'll need a programmer for AVR
microcontrollers, such as [this one][avrisp]. If you have no idea what a programmer is, You
definitely don't have one and You'll need the help of some electronics tinkerer/hobbyist/engineer.

## I'm good to go! Where is the firmware?

You can find the source code for the firmware of each sub-system in the relevant repository:

* [For the CPU][cpu] (source code in C)
* [For the GPU][gpu] (source code in ASM and the "compiled" HEX)
* [For the APU][apu] (source code in ASM and the "compiled" HEX)

[delta]:    http://deltahacker.gr                       "ethical hacking magazine"
[eagle]:    http://cadsoft.io                           "Eagle PCB design"
[euro]:     http://www.eurocircuits.com                 "EuroCircuit PCB services"
[avrisp]:   http://www.atmel.com/tools/AVRISPMKII.aspx  "AVR ISP programmer homepage"
[cpu]:      https://github.com/pvar/nstBASIC            "firmware for the main processor"
[gpu]:      https://github.com/pvar/dhpc_gpu_firmware   "firmware for the graphics processor"
[apu]:      https://github.com/pvar/dhpc_apu_firmware   "firmware for the sound processor"
