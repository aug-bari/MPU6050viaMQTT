# MPU6050viaMQTT
An ESP8266 Sketch used to read data from MPU6050 and transfer it via MQTT

# Connectivity
This sketch uses https://shiftr.io/ as MQTT broker.
You have to: sign up, create a new namespace, go to namespace settings, add a token, use your token information to update your Arduino code and gain access to the namespace connection.


# Hardware
you just need an ESP8266+Arduino like controller and an MPU6050 Acceleration and Gyro Sensor

# Libraries to include
you need to download this library https://github.com/256dpi/arduino-mqtt as a zip file and include it to the sketch.
NOTE: if there are problem with compatibility you can use the version uploaded in this repo : https://github.com/aug-bari/MPU6050viaMQTT
