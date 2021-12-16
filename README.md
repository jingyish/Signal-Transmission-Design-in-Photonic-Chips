# Signal Transmission Design in Photonic Chips

## Group member
Yuhan Chen, Jingyi Shen, Xinyi Zhang

## Introduction
In our project, "Signal Transmission Design in Photonic chips", we apply with the software, Optisystem, to design our schematics, and simulate the results. Based on the properties of the WDM system and EDFA, we design this EDFA schematics for WDM systems to optimize the gain of the transmission signal. In this design, the multiplexer combine eight different signals with the pump laser, and the signals launched to the doped fiber, and the signals is amplified through the doping ions. The figure shown below is the principle schematic of EDFA system.

## Background
### WDM system
Wavelength Division Multiplexing (WDM) is a fiber-optic transmission technique that combine light with different wavelengths (or colors) into one fiber, and apply with the multiplexer to transmit data. Different colors of light can travel on one fiber at the same time, then signals can be transmitted in an optical waveguide at different wavelengths or frequencies on the optical spectrum. In WDM systems by multiplexing, a stream of wavelength channels particularly in C and L-band regimes can simultaneously amplify to a desired power level where the amplification of any particular channel is dependent on the signal wavelength, the number of signals present in the system, the input signal powers and its absorption and emission cross-sections [1]. In this project, we first combined 8 transmitter subsystems to be 8 channel WDM transmitter (shown in Sprint3 and Sprint4). Then connect it with mux and demux to build up the WDM system, which can combine or split light with different wavelengths, then transmit data. 

### EDFA (Erbium-Doped Fiber Amplifier)
Erbium-Doped Fiber Amplifier (EDFA) has large gain and high output power. It is an optical amplifier that along with the doped optical fiber to amplify several  optical signals at same time. Which means EDFA can amplify optical signals directly without converting into electrical signals. In this poject, we design this signals transmission schematic combined with EDFA and WDM system. The basic structure of an EDFA consists of a length of Erbium-doped fiber (EDF), a pump laser, and a WDM combiner. The WDM combiner is for combining the signal and pump wavelength so that they can propagate simultaneously through the EDF [2]. The figure shown below is the principle schematic of EDFA system. 
(![What_is_EDFA_forward_pumping](https://user-images.githubusercontent.com/90426866/146406262-11b68b56-143a-473b-a3ea-2690affdab40.png)

## Schematics
![schematic](https://user-images.githubusercontent.com/90426866/146411600-41443697-1224-4480-8830-d4b5b7ef5801.JPG)

## Simulations
#### Output power and noise spectrum 
The following figures show the results viewed from a visualizer in the OptiSystem software. It displayed a boost of the gain for pump powers when the power (dBm) versus the wavelength (m).
![spectrum2](https://user-images.githubusercontent.com/90426866/146411074-3e93b646-b064-4d72-8bdb-9fe0924993bf.JPG)
![spectrum1](https://user-images.githubusercontent.com/90426866/146411043-1600003e-3020-4748-a4f3-f23cf6ce91ac.JPG)


## Conclusion:
We think this signal transmission design has been built partially successfully, because with this part light can be transmitted in long distance without high distortion. Although the design is not perfect, it satisfy our primary goal. Multiple lights have been successfully combined into one fiber, and are amplified by an amplifier. 

## [Poster](https://docs.google.com/presentation/d/11vBK19e3JnWAzDKyC5hz2bTcq70_URKFLjz7jSAr5Ls/edit#slide=id.g106a4863df6_2_11)

## Sprint Link
#### [Sprint 1](https://docs.google.com/presentation/d/13f7-M4Ozyy60VHOJVp_0sXjAn0Q7F3sJRxwd86_Unww/edit#slide=id.p)
#### [Sprint 2](https://docs.google.com/presentation/d/1QKz9lBUuWOXDW8q7zqsBB_cB4_tMfTXbOShkj6dXukg/edit#slide=id.p1)
#### [Sprint 3](https://github.com/jingyish/Signal-Transmission-Design-in-Photonic-Chips/blob/main/ECE601%20Sprint%203.pdf)
#### [Sprint 4](https://github.com/jingyish/Signal-Transmission-Design-in-Photonic-Chips/blob/main/EC601%20Sprint4.pdf)

## Reference
[1] S. Yoshida, S. Kuwano, and K. Iwashita, Electron, Lett, 1995. 
[2] Optical Amplifier—EDFA (Erbium-doped Fiber Amplifier) for WDM System, https://community.fs.com/blog/erbium-doped-fiber-amplifier-edfa.html

 
