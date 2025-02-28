# Smart Home Automation using Bluetooth

This project demonstrates how to control home gadgets (like bulbs, fans, etc.) using a mobile app and Bluetooth communication. The system uses an Arduino microcontroller, HC-05 Bluetooth module, and a mobile app built with MIT App Inventor.

## Features
- Control home gadgets (bulb, fan, lamp, PC) using a mobile app.
- Bluetooth communication between the mobile app and Arduino.
- Simple and user-friendly interface.

## Components
- Arduino Uno
- HC-05 Bluetooth Module
- LEDs (for simulating gadgets)
- Resistors (220Ω)
- Jumper wires

## Circuit Diagram
![Circuit Diagram](Circuit_Diagram/SmartHomeAutomation_Circuit.png)

## Arduino Code
The Arduino code is located in the `Arduino/` folder. It reads data from the Bluetooth module and controls the gadgets accordingly.

## MIT App Inventor Project
The mobile app is built using MIT App Inventor. The project file (`SmartHomeAutomation.aia`) is located in the `MIT_App_Inventor/` folder.

## How to Use
1. Upload the Arduino code to your Arduino Uno.
2. Connect the HC-05 Bluetooth module to the Arduino as per the circuit diagram.
3. Install the MIT App Inventor app on your mobile device.
4. Open the `SmartHomeAutomation.aia` project in MIT App Inventor and build the app.
5. Pair your mobile device with the HC-05 Bluetooth module.
6. Open the app and control the gadgets using the buttons.

## Future Scope
- Integrate more gadgets (e.g., AC, TV).
- Add voice control using Google Assistant or Alexa.
- Implement IoT for remote control over the internet.

## References
- [Arduino Official Website](https://www.arduino.cc/)
- [MIT App Inventor](https://appinventor.mit.edu/)
- [HC-05 Bluetooth Module Datasheet](https://www.engineersgarage.com/hc-05-bluetooth-module-datasheet-pinout-configuration-at-commands/)

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
