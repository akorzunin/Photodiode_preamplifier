# Photodiode_preamplifier
 The device is designed for use in a Fourier spectrometer as a photodetector 
 
 Configurations
===

## Scheme 1
![sheme2](https://user-images.githubusercontent.com/54314123/137486723-82f00660-7d07-4562-9d12-3ca68af0f063.png)


### Option 1
Circuit with two-channel amplifier in the first stage and single-channel amplifier in the second stage
| **Jumper** | **State** |
|--|--|
|PDG1|closed
|OP6|closed
|OP7|op7|open
|OP5|op5|open
|OP8|closed
|CCH1 is open
### Option 2
Circuit with one dual channel amplifier using two amplifier stages
| **Jumper** | **State** |
|--|--|
|PDG1|closed
|OP6|op6|open
|OP7 closed
|OP5|closed
|OP8|op8|open
|CCH1Off closed

Between connectors C8 and C9 is a pair of resistor and feedback capacitor Cf = 10pf, Rf = 300k. These values depend on the photodiode used.

## Scheme 2

![sheme1](https://user-images.githubusercontent.com/54314123/137486351-342c5949-5df9-40b1-803d-53740eb993e8.png)
### Description:
A large-sized circuit with one dual-channel amplifier that uses two gain stages
| **Jumper** | **State** |
|--|--|
|JUMPER1|closed
|COAX1|open
|OP1|closed
|OP2|op2|open
|OP3|Connected
|OP4 open

Between the connectors C1 and C3 is a pair of resistor and feedback capacitor Cf = 10pf, Rf = 300k. These values depend on the photodiode used.

 ## Scheme 3
![fixed_sheme4](https://user-images.githubusercontent.com/54314123/137503624-55bd6b11-64fa-427b-9f9a-5308727b5201.png)

### Description:
Large-sized circuit with two single-channel op amps

## Scheme 4

![sheme3](https://user-images.githubusercontent.com/54314123/137486867-261485b9-a7e2-4f39-91f7-37b946179ed3.png)
### Description:
Small-sized circuit with two single-channel amplifiers



<!--stackedit_data:
eyJoaXN0b3J5IjpbOTA2MzYxODAsLTEyNDc4MjEzNTIsMTkxND
cwNTc2OSwxNjY4ODAyNDc1LC0xMjY4MTU0NjEsLTEwOTc0ODQ1
MzRdfQ==
-->