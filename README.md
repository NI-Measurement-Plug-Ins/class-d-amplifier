# Class D Amplifier Measurements
This plug-in makes measurements for Class D amplifiers. The tests will generate a digital audio signal and then measure the analog output of the amplifier.
![Single tone](docs/images/single-tone.png)
## Key Features
 - Generates digital audio signal
   - I2S
   - PCM
   - TDM
 - Single tone measurements
   - THD
   - THD+N
   - SNR
   - SFDR
   - Dynamic range
   - Gain error
   - Output power
 - Crosstalk
 - Stepped Frequency Sweep

## Hardware Setup
![Hardware setup](docs/images/hw-setup.png)
Instrumentation:
- NI Dynamic Signal Acquisition device (NI 446x)
- NI 7820/21 
- SMU or power supply (note: the software does not use the SMU/power supply but need something to power the DUT)

Tested hardware setup:
- NI 4468
- NI 7821
- NI 4139
- TAS6424 evaluation board
- Load resistors

## Softwware Installation
Install from NI Package Manager:
- NI RIO
- NI DAQmx
- NI DCPower (if using NI SMU to power device)
- InstrumentStudio

Download the latest NI package from the releases section of this repo or add the feed to NI Package Manager to get updates from this repo and other in this community 

[comment]: # (add link to documnetation at community level)

## Getting Started
When you are ready to start using the software, check out [this](docs/help.md).

## Contributing
Use the instructions in [Software development](docs/sw-dev.md) for setting up a development environment and overview of the code.
