# ArdAlarm - Arduino Security System 
#### CS 426 Final Project Fall 2020

## Uploading Arduino Code
In order to upload the ArdAlarm code to the board from the Arduino IDE, follow these steps:
  - Attach all necessary modules to the board using the defined pins as shown in the code. The pin definitions refer to:
    - _rx_: Rx pin on HC-05 to 13 on the Arduino
    - _tx_: Tx pin on HC-05 to 12
    - _buzzer_: Positive pin on buzzer to 48
    - _sensorTrig_: Trig pin on ultrasonic sensor 9
    - _sensorEcho_: Echo pin on ultrasonic sensor 10
  - Connect Arduino to computer running the Arduino IDE using the board's USB port
  - Ensure the correct board model and serial port is selected in the Arduino IDE
  - Click the **Upload** button to compile and deploy the code to the board

## Running Android Application
To run the Android application from Android Studio, follow these steps:
  - Before running the application, connect the device to the Arduino in the devices Bluetooth settings:
    - The Arduino's Bluetooth module should show up under the name ""
    - Passcode is either 1234 or 0000 depending on the module
  - Select the device to run application from the **Available Devices** list
  - With the Arduino powered on, click **Run** to open the application

_Note: Must be run on a physical device because emulators do not support Bluetooth_
