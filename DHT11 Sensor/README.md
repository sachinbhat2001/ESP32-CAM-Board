# ESP32 CAM BOARD AND DHT 11 SENSOR






| PIN NUMBER | NAME OF THE PIN | DESCRIPTION                                            |
| ---------- | --------------- | ------------------------------------------------------ |
| 1          | Vcc             | Power supply from 3.5V to 5V                           |
| 2          | data            | Outputs temperature and humidity on the serial monitor |
| 3          | GND             | connected to ground pin of the circuit                 |





#### Connections:



 

| DHT 11 Sensor pin                        | ESP32 CAM Board pin |
| ---------------------------------------- | ------------------- |
| Vcc                                      | 3V3                 |
| Data(pulled up with10 kilo ohm resistor) | GPIO 4              |
| GND                                      | GND                 |





#### Instructions:

1) Make sure have properly connected the pins of DHT11 sensor with ESP32 CAM board.

2) Now compile the code and upload it to the ESP32 CAM board.

3) Now disconnect the GPIO pin and GND pin on ESP32 CAM Board and click on reset button on the microcontroller.

4) Now open the serial monitor and and click on reset button on ESP32 CAM board.

5)You can see the IP address of ESP32 CAM Board.

6) Copy that IP address and paste it in the web browser.

7) You will get the temperature and humidity output on the web browser.

