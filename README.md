# FLIGHT COMPUTER
controller for any four motors based flying object according to specification mentioned below.

![image](https://github.com/Himanshukohale22/SKY/assets/114358863/dddf1d66-9bc2-485a-a960-776019762b69)


This repository contains hardware files and gerber files of board . this is open source project board can be used aacording to features mentioned below.

### BOARD SPECIFICATION.
---

* STM32f4 cortex M4 based on board microcontroller for precision and fligt data simulation.
  * core -  Arm® 32-bit Cortex®-M4 CPU with FPU, Adaptive real-time accelerator .
  *  1 Mbyte of Flash memory
  *  192+4 Kbytes of SRAM
  *  Serial wire debug
* sensors
  * MPU9250.(IMU)
    *  9-axis of freedom. (6 are used).
    * accerelometer an gyroscopic values
    * Higher calibration precision.
    * for statbility and orientation of board/vehicle.
    * configured with SPI1.
  * BMP280 .(Barometer)
    * configured with I2C .
    * barometer for altitude calculations . helps to hover the flight.
    * absolutely accurate p = 950 -- 1100 hPa.
  * NRF module
    * nrf module for communication upto 1km.
    * configured with SPI2.
* for programme the ,board include four pins ckl , io , pwr , gnd as in 1.27mm pins(SWD). use ST-LINK.
* power input
  * usbB mini for testing testing.
  * jst connector i/p from 12v to 27v .
 


### schematics   
---

![image](https://github.com/Himanshukohale22/SKY/assets/114358863/e396841e-36db-40f1-8974-4811c69fe763)

![image](https://github.com/Himanshukohale22/SKY/assets/114358863/c2cab9f4-40db-4b7d-9f78-5be6ef26bf45)


## 3D 
---

![image](https://github.com/Himanshukohale22/SKY/assets/114358863/86a1a5f5-95be-4de3-8b41-1c4b5e165a02)


![image](https://github.com/Himanshukohale22/SKY/assets/114358863/121057b6-c61a-4bd1-aa27-ee1c04cacf7d)


## Tools 

* [kicad](https://www.kicad.org/)

* [STM32cubeide](https://www.st.com/en/development-tools/stm32cubeide.html)


## Reference 
---

[stm32f411](https://www.st.com/resource/en/datasheet/stm32f411re.pdf)

[MPU6050](https://invensense.tdk.com/wp-content/uploads/2015/02/MPU-6000-Datasheet1.pdf)

[BMP280](https://cdn-shop.adafruit.com/datasheets/BST-BMP280-DS001-11.pdf)

[NRF24](https://www.sparkfun.com/datasheets/Components/SMD/nRF24L01Pluss_Preliminary_Product_Specification_v1_0.pdf)


## future work 
---
* work with higher level cortex controller.(ex f7/f8)
* include SD card for collecting flight data.
* include FVP cameras. and configuring. collecting photos/videos.
* higher level nrf modules for rf communications. 

