# Rain Detector using DHT11 and Raindrop Sensors
This project aims to create a weather monitoring system, especially rain detection using raindrop sensors and DHT11

## Tools
- Esp8266
- Raindrop sensor
- HL-01 modul
- DHT11
- Blynk Apps

## Goals
my goal is to develop an intelligent and reliable tool to assist individuals in adapting to unpredictable weather conditions caused by global warming. This project aims to provide an efficient solution for detecting rain based on water intensity, temperature, and humidity data. Ultimately, it seeks to support daily activities, such as drying clothes, food, or other items outdoors, by offering timely and accurate rain alerts to improve convenience and efficiency.

## Step 1:  Requirement Analysis
- Identify the system's functional and non-functional requirements, such as sensor specifications, environmental condition ranges, and alert methods.
- Research weather patterns and typical use cases for rain detection in tropical climates to ensure the system meets user needs effectively.

## Step 2: Component Selection
- Select a DHT11 sensor for temperature and humidity measurement and a Raindrop sensor for water intensity detection.
- Choose a suitable microcontroller to process data and manage system operations.
- Decide on the type of alert mechanism for indicating rain detection.

## Step 3: System Design
- Create a circuit diagram showing the connections between the DHT11 sensor, Raindrop sensor, microcontroller, and alert mechanisms.
- Design the physical casing to ensure the device is compact, weatherproof, and suitable for outdoor use.

![image](https://github.com/user-attachments/assets/bffc75e4-72ca-44ef-bd32-a2ada8c38c9b)

## Step 4: Prototyping
- Assemble the selected components according to the circuit diagram.
- Write and upload the code to the microcontroller to read sensor inputs, process the data, and activate alerts when rain is detected.
- Test the prototype in controlled conditions to verify its functionality.

![sensor 1](https://user-images.githubusercontent.com/92429478/173230333-31d6d82c-4fc6-4d17-b0ea-44e08f2d378c.jpeg)

![sensor 2](https://user-images.githubusercontent.com/92429478/173230403-473f5198-f7be-4adf-84bd-93e137b81d32.jpeg)

## How it Works
For testing temperature and humidity values, testing is done by bringing solder to the DHT11 sensor to make sure whether the tool is running or not. For testing the value of water intensity, testing was carried out by dripping water on the raindrop sensor. the value of rain intensity we set to a value of 100 for normal conditions (without water), so that when the raindrop sensor is given water, the value of water intensity that appears on the cell phone will decrease depending on how much water there is. 

full details are here: https://www.youtube.com/watch?v=wT8t1fPAsLU
