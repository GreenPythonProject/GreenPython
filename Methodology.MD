# Methodology

The methodology used to setup, obtain, and analyise energy measures are based on FEETGINGS (Framework for Energy Efficiency Testing to Improve Enivornmental Goals of the Software) framework.  This framework uses the following seven stages

1.  Scope Defintion.

This begins to specify the requirements for evaluating energy efficiency and describes the software to be analysed.  This project aims to measure the energy consumption of various Python functions and how refactoring them      could improve energy efficiency.

2.  Measurement Environment Setting.

This stage refers to measuring equipment used to obtain the energy measurement data.

<img src="/assets/Setup_Layout.png" alt="Setup Layout" width="250" height="250">

The DUT (Device Under Test) is the device on which the Python Scripts are run on. A Raspberry PI 5: 64-bit Quad-Core Arm Cortex-A76 Processor @2.4GHz, 8GB RAM, Raspbery PI OS-Lite, using Python 3.11. A Towards Electrics Instruments TPS-4000 Dual-Tracking Power Supply powers the DUT.  The multi-meter, Keithley DMM6650 1/2 Dig, is connected to the DUT.

<img src="/assets/Power_Supply.jpg" alt="Power Supply" width="250" height="250">
Towards Electrics Instruments TPS-4000 Dual-Tracking Power Supply
