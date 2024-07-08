# ESP32-C6-Temp-Example
#### Using Arduino IDE

To get more information about the Espressif boards see [Espressif Development Kits](https://www.espressif.com/en/products/devkits).

* Before Compile/Verify, select the correct board: `Tools -> Board`.
* Select the End device Zigbee mode: `Tools -> Zigbee mode: Zigbee ED (end device)`
* Select Partition Scheme for Zigbee: `Tools -> Partition Scheme: Zigbee 4MB with spiffs`
* Select the COM port: `Tools -> Port: xxx` where the `xxx` is the detected COM port.

* This is modifed from the Arduino example I added MANUFACTURE_NAME AND MODEL_IDENTIFIER
* It reports cpu temp using this Hubitat driver, https://github.com/hubitat/HubitatPublic/blob/master/examples/drivers/environmentSensor.groovy
