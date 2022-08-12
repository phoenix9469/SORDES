## Sordes Motherboard SMT Version
### Schematic
![image](https://user-images.githubusercontent.com/82319443/183477162-3d633763-05bc-41f3-b66e-af52efb0368b.png)
### PCB
![image](https://user-images.githubusercontent.com/82319443/184364888-13750411-0b20-40bb-b71e-10912473e623.png)
### 3D Top
![image](https://user-images.githubusercontent.com/82319443/184365297-e3f394b4-f3ed-4541-9aea-9b1490216869.png)
### 3D Bottom
![image](https://user-images.githubusercontent.com/82319443/184365460-4c070b2c-b38b-4b33-8b4f-89303b3da26b.png)
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
