
### Project Overview

The **Food Spoilage Detector** is an IoT-based embedded system designed to monitor food freshness by detecting gases released during spoilage. This project utilizes Arduino technology and various sensors to provide early warnings about spoiled food, aiming to reduce waste and prevent health risks associated with consuming spoiled food.


### Prerequisites

- Arduino IDE
- Blynk app (available for iOS and Android)
- Required hardware components 

### Hardware Setup

1. **Components Needed:**
   - Arduino UNO
   - MQ-4 methane sensor (or alternatives like MQ-2, MQ-3)
   - NodeMCU (ESP8266 Wi-Fi module)
   - Red and Green LEDs
   - Buzzer
   - Breadboard and jumper wires
   - Power supply (USB or external)

2. **Wiring:**
   - Connect the MQ-4 sensor to an analog pin on the Arduino.
   - Wire the Red LED to a designated digital pin for spoilage alerts.
   - Wire the Green LED to indicate fresh food.
   - Connect the Buzzer for audible alerts.
   - Connect the NodeMCU for Wi-Fi communication. (notifications on spoilage)

### Software Setup

1. **Arduino IDE:**
   - Install necessary libraries for Blynk and sensors.
   - Upload the Arduino sketch provided in the directory.

2. **Blynk App:**
   - Create a new project and obtain the Auth Token.
   - Configure Wi-Fi settings in the code.

## Components

- **Arduino UNO**: Main controller for processing sensor data.
- **MQ-4 Sensor**: Detects methane gas levels indicating spoilage.
- **ESP8266 Module**: Connects to Wi-Fi for remote monitoring.
- **LEDs and Buzzer**: Provide visual and audible alerts for spoilage.
- **Blynk App**: Interface for real-time monitoring and notifications.

## Usage

1. Power on the system and ensure all components are properly connected.
2. Open the Blynk app and monitor the dashboard for live gas readings.
3. The system will provide alerts based on methane levels:
   - **Green LED** and no Buzzer: Food is fresh.
   - **Red LED** and Buzzer: Spoilage detected; food should not be consumed.

## Project Structure
![image](https://github.com/user-attachments/assets/7f622d92-cd02-418c-954f-6cd14382de82)

![image](https://github.com/user-attachments/assets/d3489fa9-c05e-41ae-9294-cea83b4b3c48)

![image](https://github.com/user-attachments/assets/165e3047-bfbe-4850-8dd8-a85db33fe72f)

![image](https://github.com/user-attachments/assets/2169db80-d171-4cad-9aee-60b69728addd)

![image](https://github.com/user-attachments/assets/1ec17385-1f47-41c8-adf7-dfa82992b3ad)


## Outputs
![image](https://github.com/user-attachments/assets/d49e3e49-c0ef-499f-a895-db06a7235977)

![image](https://github.com/user-attachments/assets/9ea3a91f-353f-45dc-8747-a98cd2ae84f9)

![image](https://github.com/user-attachments/assets/a12916f5-539f-4041-8f09-b079b026d9da)

## Sample Poster

![image](https://github.com/user-attachments/assets/17310821-045c-418e-99b5-74fc52e57edf)

