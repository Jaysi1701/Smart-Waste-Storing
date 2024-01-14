# Smart-Waste-Storing

A smart waste management system that uses IoT sensors to identify and sort different types of waste (dry and wet) automatically, promoting recycling and reducing contamination.

## Requirements
- Arduino IDE
- Breadboard
- Arduino Uno
- Servo Motor
- Moisture Sensor
- Ultrasonic Sensor (X2)
- Buzzer
- IR Sensor (attach close to moisture sensor to detect the object placed )


## Circuit Diagram
![WMS](https://github.com/Jaysi1701/Smart-Waste-Storing/assets/128627421/bfc21d91-848b-47e1-ae80-97b771745c99)

## Working
The waste material is placed on top of the moisture sensor, which is attached to the servo motor. The IR sensor, placed right behind , detects the object and displays an object detection message. The moisture sensor determines the moisture value of the object, and based on that value, the waste is classified as wet or dry waste. The servo motor then puts the waste into its respective bin. Both bins contain ultrasonic sensors, which determine the space left inside their respective bins. The buzzer goes off when the bin is full.

