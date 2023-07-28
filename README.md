# Surveillance Robot Car 🚗🎥
![MasterHead](https://cdn.discordapp.com/attachments/782838733133053994/1134424748672168017/image.png)


**Introduction** 🌟

Welcome to the world of Surveillance Robot Car! 🎉 In this exciting project, we have created a wirelessly controlled robot car equipped with a camera for surveillance purposes. Surveillance Robot Car is a fascinating project that combines web technologies and C++ programming to create a versatile ESP32-based robot capable of real-time video streaming and remote control. The robot uses a Wi-Fi camera and motorized wheels to deliver an interactive and dynamic experience. This repository contains the source code, schematics, and documentation for building and operating the Surveillance Robot Car. 🕵️‍♂️ Now you can unleash your inner spy and explore your surroundings with this nifty little gadget! 🕵️‍♀️ 


**Team Members** ⚡

| Team Member Name                   | Roll Number   |
|------------------------------------|---------------|
| Amrutha Macharla                   | 20BCE7391     |
| Mangapathi Srileakhana             | 20BCE7397     |
| Venna Jaya Devi Sai Charan         | 20BCR7105     |
| Viswanadha Lakshmi Kalyani         | 20BCI7116     |
| Murari Pavan Tejesh                | 20BEV7033     |
| Paruchuri Kumara Sai Pradeep       | 20BCE7149     |


**Features** 🚀

🔍 Real-time Video Streaming: Keep an eye on things with live video streaming directly to your mobile phone. 👀

📶 Wireless Control: No more messy wires! Control the robot car wirelessly through your web browser. 📱

🔦 LED Light: Illuminate dark corners with the built-in LED light. Perfect for secret missions in the dark! 💡

🎥 Camera Flexibility: The camera can be easily adjusted to capture the perfect view. 📹


**Working Method** 🔩
1. Hardware Requirements: ESP32 board, ESP32-CAM module, DC motors, L298D motor driver, batteries, robot chassis.
2. Software Requirements: Arduino IDE, ESP32 board package, required libraries (AsyncTCP, ESPAsyncWebServer).
3. Wiring and Setup: Follow the provided schematics and documentation to assemble the robot and upload the code.
4. Connect to Wi-Fi: Access the robot's web interface by connecting to its Wi-Fi network from your mobile or computer.
5. Control the Robot: Navigate the robot, adjust speed, and control the onboard light using the web interface.


**Code Overview:**
- `main.cpp`: The main C++ file that handles motor control, WebSocket communication, and camera streaming.
- `esp_camera.h`: Library for interfacing with the ESP32-CAM module and capturing video frames.
- `AsyncTCP.h`: Library for asynchronous TCP communication.
- `ESPAsyncWebServer.h`: Library for setting up the web server and handling web requests.
- `htmlHomePage`: HTML code for the web interface, allowing users to control the robot.
  
1. Libraries: The code includes several libraries, such as esp_camera.h for camera functionality, Arduino.h for the Arduino core, WiFi.h for Wi-Fi connectivity, and various libraries for working with Async TCP, Async Web Server, and WebSockets.
2. Motor Control: The code defines motor pins and functions for controlling the motors (LEFT and RIGHT) of the car to move it in different directions (UP, DOWN, LEFT, RIGHT, STOP).
3. Web Page: The code defines an HTML page (htmlHomePage) to control the Wi-Fi camera and car. The page includes buttons for moving the car, sliders for adjusting the car's speed and light intensity, and an image element to display the camera feed.
4. WebSocket Handlers: The code sets up WebSocket handlers for both camera and car control. When a client connects to the WebSocket server for car control, it can send commands to move the car, adjust the speed, or control the light intensity.
5. Camera Setup: The code initializes the camera using esp_camera_init() with specific configurations for pins and settings.
6. Main Setup: In the setup() function, the code sets up pin modes, starts the HTTP server, initializes the WebSocket servers, and sets up the camera.
7. Main Loop: In the loop() function, the code periodically sends the camera picture to clients connected to the WebSocket camera server and cleans up WebSocket clients. It also monitors incoming WebSocket messages for car control.


**Getting Started** 🚀

To start your espionage adventure, follow these simple steps:
1. Connect to the robot car's Wi-Fi network: "MyWiFiCar" 📶
2. Open your web browser and navigate to the unique link provided by the robot car. 🌐
3. Voila! You are now in full control of the Surveillance Robot Car. Use the arrow buttons to move it around and explore your surroundings. 🚗


**Important Notes** 📝

🔋 Keep an eye on the battery level to ensure uninterrupted missions. Charge it regularly for endless spy fun! 

🌌 Avoid using the robot car for intergalactic travel. While it's advanced, it's not quite ready for space missions yet! 


**Contributing** 🤝
We welcome contributions from fellow spies and tech enthusiasts! If you have any cool ideas or improvements, feel free to create a pull request. Let's make this surveillance robot even more awesome together! 


**Bug Reports** 🐞
If you encounter any bugs during your top-secret missions, don't worry! Just open an issue, and our team of brilliant developers will fix it ASAP. 🛠️


**Disclaimer** ⚠️
The Surveillance Robot Car is intended for entertainment and hobby purposes only. Any illegal or unauthorized use is strictly prohibited. We will not be held responsible for any secret agent mishaps! 


**Acknowledgements** 🙏
Special thanks to the amazing open-source community for their contributions and inspiration. 


**License** 📜
This project is licensed under the MIT License. Feel free to use, modify, and distribute it, but please keep the credits intact. Happy spying! 


**Let the Adventures Begin!** 🚀
So, what are you waiting for? Embark on thrilling spy missions and explore the world from the perspective of a Surveillance Robot Car!


Enjoy the fun and excitement! 😄

![MasterHead](https://cdn.discordapp.com/attachments/782838733133053994/1134424920886091837/image.png).
