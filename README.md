# stm32-i2c-demo
Demo project: Reading I2C sensor using STM32 HAL and printing data on UART


# STM32 I2C Demo

### Project Overview  
This project demonstrates how to interface an I2C sensor with STM32 microcontroller using HAL libraries. The sensor data is read and displayed via UART.

### Hardware Used  
- STM32 Nucleo-F446RE  
- DHT11 Sensor (I2C)  
- USB-UART cable  

### Features  
- I2C communication setup @100kHz  
- Polling-based data read  
- UART debug output  

### Demo Output  
```
Temperature: 27°C  
Humidity: 56%  
```
### How to Run
1. Clone this repository  
   ```bash
   git clone https://github.com/<mee-username>/stm32-i2c-demo.git
   ```
2. Open project in **STM32CubeIDE**  
3. Build & flash to STM32 board  
4. Connect UART @9600 baud to see sensor data  
