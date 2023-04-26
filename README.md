# SKY
CONTROLLER FOR DRONE

stm32F411xc on board controller flight controller.


Specification:
On board chip of controller is STM32F4XC high performance microcontroller.
Board contains gyroscope and accelorometer for flight controlling and PID motion.
Two pyro channels are present on board for parachute deployment in regular mode and other in emergency  mode.


Hardware design:
STM32F411xc main controller.
mpu6050 gyroscope and accelorometer sensor.
bmp280 pressure and altitude sensor.
Inbuilt SD card module.
nrf24 RF module for on board communicaton between base station and flight ROCEKT.


scematics img:

![image](https://user-images.githubusercontent.com/114358863/228628429-09c70a89-7db2-49fd-b2ef-2cce207696d4.png)

pcb img:

![image](https://user-images.githubusercontent.com/114358863/228628094-14ec1e12-a6ac-4a39-9471-7c13ca92b75c.png)

3D:

![image](https://user-images.githubusercontent.com/114358863/228628309-ca51cfef-0d01-4d40-bd45-98916c7a1b14.png)



datasheet:

stm32f411 

https://www.st.com/resource/en/datasheet/stm32f411re.pdf

MPU6050

https://invensense.tdk.com/wp-content/uploads/2015/02/MPU-6000-Datasheet1.pdf

BMP280

https://cdn-shop.adafruit.com/datasheets/BST-BMP280-DS001-11.pdf

NRF24

https://www.sparkfun.com/datasheets/Components/SMD/nRF24L01Pluss_Preliminary_Product_Specification_v1_0.pdf

BUILTIN MICRO SD CARD

https://components101.com/modules/micro-sd-card-module-pinout-features-datasheet-alternatives
