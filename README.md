# DAQ Module for DCAF

The [Distributed Control And Automation Framework (DCAF)](https://github.com/LabVIEW-DCAF) is a collection of open-source software components that support the design and development of control applications with the LabVIEW graphical system design environment, including the LabVIEW Real-Time and LabVIEW FPGA modules.

This specific module interacts with the DCAF engine and uses the DAQmx driver from National Instruments to provide basic IO capability without any programming. Measurement types supported include: 

  - Analog Inputs (Includes configuration for RTDs, Thermocouples,and Strain)
  - Analog Outputs
  - Digital Inputs
  - Digital Outputs

# New Features

  - PWM support - you can now generate PWM signals with the DAQ Module

Limitations on PWM:
  - Minimum Duty Cycle supported: 0.01
  - Maximum Duty Cycle supported: 0.99
  - Minimum Frequency supported: 0.01 Hz



