# Istrobot-MazeSolver

## ESP32 PINOUT GUIDE
Before connecting anything to ESP32, check this link: https://randomnerdtutorials.com/esp32-pinout-reference-gpios/  
ESP32 has some piins which are not allowed to use because of integrated SPI flash(6-11), boot failing whe pulled high(12) and other strange things.
There are 2 more pins which are not allowed to use - pin 21 and 22 - these will be used for I2C distance sensors communication.  
**SENSOR_VP = GPIO36  
SENSOR_VN = GPIO39**  
