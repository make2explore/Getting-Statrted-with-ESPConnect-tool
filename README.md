# Getting-Statrted-with-ESPConnect-tool
Getting Started with ESPConnect - Zero installation web application that lets you Explore, Backup and Manage your ESP32
  
<img src="/Images/m2e-ESPConnect.jpg" height="200"> &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; <img src="/Images/ESPConnect-github.png" height="200" >

  
**ESPConnect** is a browser-based control center for ESP32- and ESP8266-class boards. It runs entirely inside a modern Chromium browser so you can inspect hardware details, manage SPIFFS files, back up flash, and deploy firmware without installing desktop software. 
  
Building an OpenThread Border Router (OTBR) on an ESP32 requires a **two-chip architecture** because a standard ESP32 lacks the necessary IEEE 802.15.4 radio for Thread networking. The setup involves a Wi-Fi-capable ESP32 board, such as the ESP32-S3, to act as the host processor and a separate chip with an 802.15.4 radio, like the ESP32-H2, to function as the Radio Co-Processor (RCP). This dual-chip design allows the host ESP32 to handle the high-level border router tasks while the RCP manages the low-level Thread network communications. To simplify this, Espressif offers a dedicated development board, though a DIY setup with a standard ESP32 and an external RCP is also an option.  

The software-based setup uses Espressif's IoT Development Framework (ESP-IDF) and their ESP Thread Border Router SDK to compile and flash the necessary firmware. Developers first build and flash the RCP firmware onto the 802.15.4 chip. Then, they configure and flash the main border router firmware onto the host ESP32, which enables network-bridging capabilities. The process is guided by the ESP-IDF command-line interface, allowing developers to configure network settings and manage the Thread network from the serial monitor once the device is running.  
  
### Prerequisites 🧰
  
ESPConnect is Zero installation web application that lets you Explore, Backup and Manage your ESP32.  
  
## What You Need
- Chrome, Edge, Brave, Arc, or another Chromium browser based on version 89 or newer.  
- An ESP32, ESP32-C3, ESP32-S2, ESP32-S3, ESP32-C6, ESP32-H2, ESP32-C5, ESP32-P4, or ESP8266 board connected over USB.  
- A USB cable with data lines. If your board lacks automatic reset wiring, the app walks you through entering the bootloader manually.

## Quick Start
1. Open [ESPConnect](https://thelastoutpostworkshop.github.io/ESPConnect/).  
2. Click **Connect** and choose your device when the browser asks for permission.  
3. After the handshake completes, the navigation drawer unlocks every tool: Device Info, Partitions, SPIFFS, Apps, Flash, Console, and Logs.  
4. Use **Disconnect** whenever you want to free the USB port for another application.   
  
➡️ **[CONTRIBUTING.md](./CONTRIBUTING.md)**
That document contains development setup instructions, project conventions, and contribution guidelines.  

------------------------------------------------------------------------------------------------------

📕 **YouTube Video Links**  

- In this tutorial we will see How to get statrted with ESPConnect Tool

▶️ ESPConnect - Ultimate ESP32 "Swiss Army Knife" Tool!   - 🔗  https://youtu.be/DnZZ9E_58aQ     
  

-------------------------------------------------------------------------------------------------------
📒 **Important Links**  
 
🌐 ESPConnect GitHub Repo - 🔗 https://github.com/thelastoutpostworkshop/ESPConnect    
🌐 ESPConnect Tool - 🔗 https://thelastoutpostworkshop.github.io/ESPConnect/     
📙 Release Page 🔗 https://github.com/thelastoutpostworkshop/ESPConnect/releases  
🌐 ESPConnect Developer - 🔗 https://github.com/thelastoutpostworkshop   

------------------------------------------------------------------------------------------------------

📜 Source Code, Circuit Diagrams and Documentation : 

🌐 GitHub Repository - 🔗 https://github.com/make2explore/Getting-Statrted-with-ESPConnect-tool     
  
🌐 Hackster Blog - 🔗 https://www.hackster.io/make2explore  
  
🌐 Instructable Blog - 🔗 https://www.instructables.com/make2explore  
  

------------------------------------------------------------------------------------------  

[![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

This work is licensed under a
[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg