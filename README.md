# TSPC-Latch
Low Power VLSI Project

### Introduction

* The True Single-Phase Clocking (TSPC) latch, a fundamental CMOS circuit element in digital logic design, offers high-speed performance with simple clock generation and distribution. TSPC latches provide efficient temporary data storage by capturing and holding digital values until overwritten. They synchronize different parts of a circuit, ensuring accurate timing and reliable operation. TSPC latches feature a small number of clocked transistors, enhancing their speed and efficiency in digital systems. 

* There are two types of  TSPC latches
1. Precharged TSPC Latches (PN and PP type)
2. Non-precharged TSPC latches (SP and SN type)

![335595600-78f17cf4-5555-443c-ab3d-2ba3fe7b445d](https://github.com/Karthik-6362/TSPC-Latch/assets/137412032/7af11924-e17f-4bb3-91ae-2d99a3a90589)

### Non-Precharged TSPC latch

A TSPC non-precharged latch is a variation of the TSPC latch design used in digital circuitry. Unlike traditional TSPC latches, which use precharge and evaluate phases to achieve storage and transfer operations, TSPC non-precharged latches do not have a precharge phase. 
* The latch directly captures and holds the input data during the clock's active phase without the need for precharging the internal nodes.
* This design simplifies the latch structure and can lead to reduced power consumption and improved speed, particularly in high-frequency applications.
* However, TSPC non-precharged latches may have limitations in terms of robustness and noise immunity compared to their precharged counterparts.

![335595847-da443438-d76a-4a10-b10e-f03e8959ed5d](https://github.com/Karthik-6362/TSPC-Latch/assets/137412032/a9514088-1944-4e3f-9785-a773ccf8dd60)


### SP type latch
The latch relies on the clock signal and the data input (D) to capture and hold a data value. Here's a step-by-step explanation:
* Clock Low (CLK = 0):
    * During the low phase of the clock signal, a path is created between the data input (D) and the latch output (Q) using transmission gates formed by NMOS and PMOS transistors controlled by the clock signal.
    * The current state of the data input (D) is directly passed through this open path and reflected on the latch output (Q).
* Clock High (CLK = 1):
    * When the clock signal goes high, the transmission gates controlled by the clock become inactive, effectively closing the path between the data input (D) and the latch output (Q).
    * The latch now enters a hold state, where it retains the value that was present at the output (Q) just before the clock went low. This captured value remains stable until the next clock cycle.

![335596295-e628d1f4-2476-4fd6-abea-04fcf4912c54](https://github.com/Karthik-6362/TSPC-Latch/assets/137412032/3183ad4a-eb1a-4aca-9434-f0240776107d)









