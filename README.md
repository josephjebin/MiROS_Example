This is a practice project for developing an RTOS with instructions from the GOAT Miro Samek from Quantum Leaps LLC (can be found on YouTube). 

Under instruction from Miro Samek's RTOS course, I developed a preemptive (interrupt-based) priority-based scheduler for an RTOS, and this can be found in the diy_RTOS_preemptivePriorityBasedScheduler branch. 

# Sub-directories in this lesson:
```
|
+---CMSIS           - CMSIS (Cortex Microcontroller Software Interface Standard)
|
+---ek-tm4c123gxl   - support code for EK-TM4C123GXL (TivaC Launchpad) board
|
\---qpc
        \---include             - header files for RTOS
        \---ports\arm-cm        - RTOS ported to my microcontroller (TM4C)
        \---src                 - source files for RTOS
|
\---tm4c123-keil
        ...
        lesson.uvprojx - KEIL project for TM4C123 (TivaC LaunchPad)
```
