# Efficiency Sweep
This service measures the efficiency of the amplifier at multiple output levels. Two different methods for measuring efficiency are supported. Read up on these methods at [Efficiency Measurement Techniques](common/efficiency-measurement.md)

## InstrumentStudio Panel
### Usage
![Efficiency Sweep Panel](meas-images/efficiency-sweep.png)
In the Output Configuration section, enter the details for your digital communication settings. For the Power settings, you can select the measurement method you are using.
![Efficiency Measurement Settings](meas-images/efficiency-meas-settings.png)

When using the SMU method, the sense resistor is not needed and that value from software is ignored. When using the DMM method, the power supply voltage is the voltage of the programmed power supply. This voltage is not measured but is used to determine the input power to the DUT.