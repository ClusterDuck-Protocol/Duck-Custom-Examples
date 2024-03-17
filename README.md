# Example Firmware Using the ClusterDuck Protocol

These are few examples to show how someone can build on top of the ClusterDuck Protocol. It works using the master branch of the ClusterDuck Protocol firmware. 

## 2. Sensors

#### BMP180Example
The BMP180 example is a custom MamaDuck that will send sensor data from the BMP 180 (Temperature, Pressure, Altitude) if integrated with the .

#### BMP280Example
The BMP280 example is a custom Mama that will send sensor data from the BMP 280 (Temperature, Pressure, Humidity) inside its own payload into the mesh.

#### DHT11Example
The DHT example is a custom Mama that will send sensor data from the DHT11 (Temperature and Humidity) inside its own payload into the mesh.

#### DustSensorExample
The DustSensor example is a custom mama that will send sensor data from a Dust Sensor inside its own payload into the mesh.

#### MQ7Example
The MQ7 example is a custom mama that will send sensor data from the MQ7 Gas sensor (Carbon Monoxide) inside its own payload into the mesh.

#### WS2812Example
The WS2812 example is a Mama Duck, which also brings some light to the world by incorporating some WS2812 LEDs via the FastLED library.

## 3. TTGO T-Beam
If you have a TTGO T-Beam you can use these custom examples for it.

#### GPS
This example is a MamaDuck, that uses using TinyGPS++ to get and send GPS data with the GPS topic based on the set timer.

#### Telemetry
Using the TTGO's hardware we can collect all different kinds of live board information such as: onboard temperature, battery voltage (if 18650 installed), and charging.

## 4. Custom Papa

#### PaPa-DishDuck and PaPa-DishDuck-WiFi
The papa Iridium Example is built to have an extra Iridium Satelite Backhaul when WiFi breakes down.

#### Papa-Downtime-Counter
This custom PapaDuck keeps track of when it loses access to the internet and for how long. 

### PaPi-DMS-Lite-Examples
https://github.com/Project-Owl/dms-lite-docker

#### PapiDuck-Serial-Example
The Serial Papi Example is a custom papa that will print the incoming data into the Serial Monitor for the PAPI to read.

#### PapiDuck-WiFi-Example
The WiFi Papi Example is a custom papa that will send the incoming data into the Papi.

## 5. Encryption
You can enable encryption. CDP comes with default settings, but set your own IV and AES256 key when in use.

#### DecryptionPapa
Decryption is a very fast operation and using this example your messages will be decrypted before sending to the cloud. Remember to set IV and AES256 key to be the same as what you use on other devices.

## 6. Ble-Duck-App
The BLE example is a custom mama that will accept data from the Duck App over bluetooth.
https://github.com/Project-Owl/DuckApp