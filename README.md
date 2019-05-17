# Interfacing-SI7021-with-esp32-
Displaying Temperature And Humidity Data on Ubidots  using  ESP32-AND-SI7021.

![alt tag](https://github.com/mjScientech/ESP32-AND-SI7021/blob/master/SI7021_I2CS_A_1.png)
# SI7021
The Si7021 I2C Humidity and Temperature Sensor is a monolithic CMOS IC integrating:

humidity and temperature sensor elements,
an analog-to-digital converter,
signal processing,
calibration data, and
an I2C Interface.
The Si7021 offers an accurate, low-power, factory-calibrated digital solution ideal for measuring humidity, dew-point, and temperature, in a number of industrial and consumer applications.

Applications of Si7021 include:
- respiratory therapy.
- defogging.
- mobile phones and tablets.
- white goods.
- indoor weather stations.
- asset/goods tracking.
- automotive climate controls. 
- micro-environments/data center monitoring.

![alt tag](https://github.com/mjScientech/ESP32-AND-SI7021/blob/master/ESP32_1.png)
# ESP-32
The ESP32 makes it easy to use the Arduino IDE and the Arduino Wire Language for IoT applications. This ESp32 IoT Module combines Wi-Fi, Bluetooth, and Bluetooth BLE for a variety of diverse applications. This module comes fully-equipped with 2 CPU cores that can be controlled and powered individually, and with an adjustable clock frequency of 80 MHz to 240 MHz. This ESP32 IoT WiFi BLE Module with Integrated USB is designed to fit in all ncd.io IoT products.

Monitor sensors and control relays, FETs, PWM controllers, solenoids, valves, motors and much more from anywhere in the world using a web page or a dedicated server.

We manufactured our own version of the ESP32 to fit into NCD IoT devices, offering more expansion options than any other device in the world! Integrated USB port allows easy programming of the ESP32. The ESP32 IoT WiFi BLE Module is an incredible platform for IoT application development. This ESP32 IoT WiFi BLE Module can be programmed using Arduino IDE.

# Steps to send data to Ubidot using ESP-32 and SI7021-

## Connection of SI7021 with shield
![alt tag](https://github.com/mjScientech/ESP32-AND-SI7021/blob/master/I2Cconnection%20SI021.JPG)

## Connection of ESP-32 with shield
![alt tag](https://github.com/mjScientech/ESP32-AND-SI7021/blob/master/Esp32%20Connection.png)

## Setup the all the connection properly and upload the [UbidotSI7021](https://github.com/mjScientech/ESP32-AND-SI7021/blob/master/UbidotSI7021.ino) code  to ESP32 using Arduino IDE.

## Making the Ubidot work:
- Create the account on [Ubidot](https://ubidots.com/).
- Go to my profile and note down the token key which is a unique key for every account and paste it to your ESP32 code before uploading.
- Add a new device to your ubidot dashboard name esp32.
![alt tag](https://github.com/mjScientech/ESP32-AND-SI7021/blob/master/Device.JPG)

- Inside device create new variable name sensor in which your temperature reading will be shown.
![alt tag](https://github.com/mjScientech/ESP32-AND-SI7021/blob/master/variable.JPG)

Hardware needed Interfacing-SI7021-with-esp32:
- [ESP-32](https://store.ncd.io/product/esp32-iot-wifi-ble-module-with-integrated-usb/)
- [SI7021](https://store.ncd.io/product/si7021-humidity-and-temperature-sensor-%C2%B13rh-%C2%B1-4c-i2c-mini-module/)
- [I2C Cable](https://store.ncd.io/product/i2c-cable/)
- [PARTICLE ELECTRON OR PHOTON COMPATIBLE I2C SHIELD](https://shop.controleverything.com/products/i2c-breakout-for-particle-electron-or-particle-photon)

Software Used:
- Arduino IDE
- [Ubidot](https://ubidots.com/)

