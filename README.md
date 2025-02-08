# Smart Greenhouse

## Project Overview
The IoT-Based Garden Monitoring and Protection System is designed to help maintain plant health and security through smart monitoring. The system integrates IoT sensors, real-time data processing, and automation to optimize environmental conditions and detect potential threats.<br><br>

## How?
The system utilizes environmental sensors such as temperature, humidity, and light sensors to track garden conditions. These sensors provide real-time data that ensures optimal plant care. A NodeMCU microcontroller connects the sensors to a cloud-based database, enabling continuous monitoring and data logging. The collected data is then transmitted via Wi-Fi to a structured database, allowing users to access and analyze information through an interactive dashboard.<br><br>

To optimize irrigation, the system uses soil humidity levels to trigger automated watering, ensuring that plants receive water only when necessary. Security features include an ultrasonic sensor that detects intrusions and activates a buzzer to deter pests or unauthorized access. Additionally, a photoresistor monitors light levels and controls an LED indicator, providing valuable insights into sunlight exposure for plants. If temperature levels exceed a predefined threshold, the system activates a cooling fan to prevent plant overheating.<br><br>

All sensor data is stored and processed in a cloud database, allowing for detailed analysis of environmental trends. A web-based dashboard displays real-time sensor readings, enabling users to make informed decisions about garden maintenance. Furthermore, the system offers remote access, allowing users to monitor and control settings from any location via an IoT platform.<br><br>

Arduino programming is used to establish system parameters and ensure smooth integration with a XAMPP-based database. This setup enables continuous data monitoring and logging. The integrated circuit board connects sensors and actuators via a protoboard, allowing automated responses to specific environmental conditions. An ultrasonic sensor and buzzer combination serve as a security measure, detecting movement and triggering an alarm to deter pests or intruders.<br><br>

A photoresistor-based LED system regulates lighting conditions. If light levels fall below a certain threshold, the LED turns on to indicate low light availability. Power management is achieved using a 9V battery with a voltage regulator to ensure stable distribution. Essential components such as the buzzer, sensors, and cooling system receive power through dedicated pins on the NodeMCU.<br><br>

To maintain optimal environmental conditions, the system includes an automated cooling mechanism. If the temperature rises above 24-26°C, a relay-controlled fan activates to cool the plants. The software integration involves multiple platforms such as Arduino IDE, XAMPP, phpMyAdmin, and other tools to facilitate data processing and storage, ensuring a smooth interaction between hardware and cloud services.<br><br>

## Key Components
- **NodeMCU**: Manages data transmission and device communication.<br>
- **DHT11 Sensor**: Measures temperature and humidity.<br>
- **Photoresistor**: Detects light intensity.<br>
- **Ultrasonic Sensor**: Monitors object proximity for security.<br>
- **Buzzer**: Emits an alarm when an intrusion is detected.<br>
- **Cooling Fan**: Activated when temperature exceeds safe levels.<br>
- **LED Indicators**: Provide visual feedback on environmental conditions.<br>
- **Cloud Database**: Stores and processes sensor data for analysis.<br><br>

## Results & Benefits
- **Optimized Plant Care**: Maintains proper watering and light conditions.<br>
- **Automated Monitoring**: Reduces manual effort in garden maintenance.<br>
- **Enhanced Security**: Protects plants from pests and unauthorized access.<br>
- **Data-Driven Insights**: Helps users track environmental patterns for better decision-making.<br>
- **Remote Accessibility**: Allows monitoring and control from any location.<br><br>

This project demonstrates the potential of IoT in sustainable gardening, providing an efficient and smart approach to plant care and security.

