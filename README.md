# IOT based Orthotic leg Analyser

## An overview of how to build this project

![Product Image](https://user-images.githubusercontent.com/103630404/213738748-5303ae63-945a-432f-98cc-d83288256b9a.png)

### Introduction
The ideal insole, knee, and heel-based monitoring system will be able to analyse, decipher, and assess the incoming data as well as keep track of the user's movement, heart activity, and PPD. Understandably, building an inconspicuous insole-based monitoring system would involve knowledge of both software and hardware design for electronic and mechanical components.

![Website Image](https://user-images.githubusercontent.com/103630404/213737511-b1adb06b-69f7-416d-a01a-297095b6ed0c.png)

### Hardware Components
- MPU6050 Gyroscope and Accelerometer × 2
- NTC Thermistor × 2
- ADXL335 Accelerometer Module × 4
- ESP32 WROOM × 2
- EMG Sensor × 2
- 12V Rechargeable Lithium Iron Battery × 2
- Force Sensors × 10
- Flux sensor × 2

### Description

Wearable health monitoring technology makes it possible to measure physiological indicators without interfering with daily activities and provides data that is indicative of a person's health and well-being. To acquire physiological data from the plantar aspect of the foot that may be evaluated to get insight into a
person's health, one such device can be placed in an insole, and the knee heals. An integrated understanding of a person's health and well-being can be achieved without interfering with daily activities by creating a system that can measure parameters such as PPD, gait characteristics, foot temperature, heart rate, and knee position. All the data are stored in the cloud. The proposed device can be used for a wide range of purposes, including the identification of pathologies, monitoring of medical conditions, and gait analysis. The data are processed using a machine learning - artificial neural network technique and stored in the cloud for later study. Real-time monitoring of the patient's schematic was done using the Unity software.

=> We first make sure the sensor is functioning effectively for our benefit before making the necessary alterations.

=> We must gather data from the sensors using the ESP-WROOM 32s microcontroller, manipulate the raw data, and transform it into real-time data.

=> The data transport to the website also used the same microcontroller. similar to https://friendly-dragon-0a92eb.netlify.app

=> We build the website using React JS and My SQL. which aids the physician's analysis.

=> We track the node using the ADXL335 Accelerometer and use the unity program to turn it into an animation. Animation is used to track the patent in a virtual environment.

=> The Force sensor, which helps to track the pressure of the leg at various locations, was mounted on the Feet.

### Conclusion

Our Ortho Mobi kit was portable and reusable, our software was easy accessible and affordable in price. The kit was used on any surface and is easy to handle and more flexible. It will be very useful for diabetic patients and people in remote villages. Thus it will be very useful in the medical field which monitors patients regularly. To analyze the daily activities of patient who has ortho-related problems and diabetes-related in legs patients.

