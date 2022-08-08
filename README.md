## Sordes Motherboard SMT Version
### Schematic
![image](https://user-images.githubusercontent.com/82319443/183477162-3d633763-05bc-41f3-b66e-af52efb0368b.png)
### PCB
![image](https://user-images.githubusercontent.com/82319443/183476144-5c3a8d32-e4af-43c3-8d26-5c048b6cde0e.png)
### 3D Top
![top](https://user-images.githubusercontent.com/82319443/183480013-ddce393e-c5e9-400e-9e28-227f849170ec.png)
### 3D Bottom
![bottom](https://user-images.githubusercontent.com/82319443/183480018-8bf6ac9e-e13b-40db-85b8-491cb2b02f78.png)
### Main MCU
ESP32_WROOM_32D
Internal Antenna
### Battery Charging
TP4056 Li-Ion Battery Charging Circuit(1A)
### DC-DC
SX1308 DC-DC Step Up Convertor(1.2MHz,2A)
3.7v~4.2v(Battery) to 5v(Logic)
### Weight measurement
HX711 24-Bit ADC for Weigh Scales
## Sordes LCD Board SMT Version
### Schematic
![image](https://user-images.githubusercontent.com/82319443/183478640-55c2b1f6-043a-4532-a7cc-4db96eef6f59.png)
### PCB
![image](https://user-images.githubusercontent.com/82319443/183477351-22968638-6c4a-4c59-9608-a5b4a2891747.png)
### 3D Top
![LCD_module_top](https://user-images.githubusercontent.com/82319443/183480020-833c3ac2-8b47-4b1b-9c9c-9fcd7b4b91ba.png)
### 3D Bottom
![LCD_module_bottom](https://user-images.githubusercontent.com/82319443/183480023-808e46db-7670-41f0-bc22-91856fdf41d5.png)
### Main MCU
ESP32_WROOM_32D
Internal Antenna
### Pinmap
3.3V -> VCC
GND -> GND
GPIO15 -> CS
GPIO4 -> RESET
GPIO2 - > DC/RS
GPIO23 -> SDI(MOSI),T_DIN
GPIO18 -> SCK,T_CLK
GPIO32 -> LED
GPIO21 -> T_CS
GPIO19 -> T_DO
GPIO27 -> T_IRQ
