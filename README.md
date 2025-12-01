# Power distribution and monitoring box
## Introduction
This project is to distribute and monitor power. It must be able to detect shorts, overvoltages etc. and take remedial action. It must also have an oscilloscope which is suitable for anything up to standard speed SPI in frequency at a minimum. The data from this must be displayed on a screen.   

## Requirements for power measurement
1. Must measure the voltage outputs.
2. Must measure the current being output.
3. Must be able to alter the output voltages with always on presets and 2 adjustable variable outputs.
4. Variable must be able to provide 2A up to 20V.
5. Fixed must include -5, -3.3, 3.3, 5 positives values must do 1A minimum.
6. Must display current and voltage for each line above eache breadboard.
7. Must have a high speed adc (40MS/s or 4MHz bandwidth) integrated.  
8. Display values from ADC in graph form.  
9. Testing to use MCUs final to use FPGA.  
10. Must take in 240V from power plug.
11. General sensors must be 16 bit. 
