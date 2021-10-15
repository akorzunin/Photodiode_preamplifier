# Photodiode_preamplifier
 The device is designed for use in a Fourier spectrometer as a photodetector 
 
 Configurations
===
## Scheme 1
![fixed_sheme4](https://user-images.githubusercontent.com/54314123/137503624-55bd6b11-64fa-427b-9f9a-5308727b5201.png)


описание:




## Scheme 2
![sheme2](https://user-images.githubusercontent.com/54314123/137486723-82f00660-7d07-4562-9d12-3ca68af0f063.png)
описание / тоже самое только меньшего масштаба
### Вариант 1
Схема с двуканальным усилителем в первом каскаде и одноканальным усилителем во втором каскаде
| **Перемычка** | **Состояние** |
|--|--|
|PDG1|замкнута|
|OP6|замкнута|
|OP7|разомкнута|
|OP5|разомкнута|
|OP8|замкнута|
|CCH1|разомкнута|
### Вариант 2
Схема с одним двухканальным усилителем, где используется два каскада усиления
| **Перемычка** | **Состояние** |
|--|--|
|PDG1|замкнута|
|OP6|разомкнута|
|OP7|замкнута|
|OP5|замкнута|
|OP8|разомкнута|
|CCH1|разомкнута|

Между коннекторами C8 и С9 ставится пара резистор и конденсатор обратной связи Cf = 10pf, Rf = 300k. Данные значения подбираяюся в зависимости от используемого фотодиода.

## Scheme 3

![sheme1](https://user-images.githubusercontent.com/54314123/137486351-342c5949-5df9-40b1-803d-53740eb993e8.png)
описание
Большая схема с одним двухканальным усилителем, где используется два каскада усиления
| **Перемычка** | **Состояние** |
|--|--|
|JUMPER1|замкнута|
|COAX1|разомкнута|
|OP1|разомкнута|
|OP2|замкнута|


|OP3|замкнута|
|OP4|разомкнута|

 1. List item

## Scheme 4

![sheme3](https://user-images.githubusercontent.com/54314123/137486867-261485b9-a7e2-4f39-91f7-37b946179ed3.png)
описание / тоже самое только меньшего масштаба
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTEzMzk5MDEwMjcsMTkxNDcwNTc2OSwxNj
Y4ODAyNDc1LC0xMjY4MTU0NjEsLTEwOTc0ODQ1MzRdfQ==
-->