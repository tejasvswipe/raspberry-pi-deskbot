# DeskBot 

it is bot that can  do  stuff while moving on  the desk  its so  funny  to  move a big fat rectangle oon  the desk .,  going to  work with open  jarvis and more stuff 

---

## Key Features

*   **Audio Interaction:** can  speaker with  a shaddy  5w speaker
*   **Locomotion:** a dedicated motor driver to  make it movee 
*   **Motion Tracking:** mpu  4050  is more than  enough.
*   **Wireless Control:** can  be control  back  and forth  by transmitter
*   **Cloud Intelligence:** can be worked  with  api  or  local model
*   **Custom Design:** making it with  f3d and stuff
---

##  Hardware Architecture

### Core Components
*   **Compute:** Raspberry Pi 4
*   **Audio Output:** Microphone & Speaker connected via an Audio Amplifier Module
*   **Locomotion:** 2x DC Motors managed by a Motor Driver Module (e.g., L298N / L293D / TB6612FNG)
*   **Telemetry & Control:** MPU-4050 IMU Sensor + RF/RC Transmitter & Receiver

### Power Management
*   **Battery:** 5000 mAh, 3.7V Lithium-Ion/Polymer battery
*   **Regulation:** High-efficiency Buck Converter

---


## ⚙️ Setup & Installation

### 1. Hardware Assembly
1.  **3.7V 5000mAh battery** connects **Buck Converter** Tune the output  to **5V** then to **Raspberry Pi 4 GPIO** or **USB-C power rails**.
2. **motor module** connects with  the moter then  the gpio  of rasp pi 

## 📊 Bill of Materials (BOM)

| Component | Description | Qty | Est. Unit Price | Total Price |
| :--- | :--- | :---: | :---: | :---: |
| **Raspberry Pi 4 Model B** | Main processing unit | 1 | $90.00 | $90.00 |
| **MPU-4050/6050 IMU** | Motion tracking| 1 | $4.00 | $4.00 |
| **DC Geared Motors + Wheels**| Locomotion  | 2 | $5.00 | $10.00 |
| **Motor Driver Module** | H-Bridge controller (L298N/TB6612) | 1 | $4.50 | $4.50 |
| **USB Microphone** | Voice command  input | 1 | $8.00 | $8.00 |
| **Audio Amplifier Module** | Signal amplifier  to Pi | 1 | $3.00 | $3.00 |
| **Speaker (4Ω/8Ω)** | Audio output for speaking | 1 | $5.00 | $5.00 |
| **RF Transmitter & Receiver** | Wireless manual control| 1 | $7.00 | $7.00 |
| **3.7V 5000 mAh Li-ion Pack**| Main power source | 1 | $5.00 | $5.00 |
| **DC-DC Buck Converter** | Voltage regulator to steady 5V | 1 | $4.00 | $4.00 |
| **Custom 3D Chassis** | 3D Printed body using Fusion 360 | 1 | $12.00 | $12.00 |
| **Jumper Wires & Fasteners** | Hardware essentials & wiring | 1 | $5.00 | $5.00 |
| **screen** | hardware | object to  see :/ |1| | $25
| **Total Estimated Cost** | | | | **$192** |
### BOM is also in  the root
<img width="580" height="318" alt="image" src="https://github.com/user-attachments/assets/147ebfe0-b5cd-4d23-b972-c716c8b808e9" />

<img width="360" height="228" alt="image" src="https://github.com/user-attachments/assets/f3f2ac28-d288-4c37-ac52-26118254d712" />

**Autodesk Fusion 360**
. You can find the fully editable design file under `\cad`. fusion 360 to modify tolerances, add component mounts, or export `.f3d` `.STL` files for 3D printing.  
 yepiee stuff is done i  have tea  ppl can  dm  on @tejas67
<img width="61" height="38" alt="Screenshot 2026-10-28 201140" src="https://github.com/user-attachments/assets/987ab204-e09f-43f0-afeb-6d07699d44ed" />
<img width="367" height="331" alt="Screenshot 2026-10-28 183300" src="https://github.com/user-attachments/assets/2a04ab67-a5dd-4ecc-954a-15122dc822ea" /> <img width="308" height="278" alt="Screenshot 2026-10-28 185722" src="https://github.com/user-attachments/assets/635e830a-4bd2-43db-a3f4-dff598ea4528" />

<img width="611" height="338" alt="Screenshot 2026-10-28 201140" src="https://github.com/user-attachments/assets/01599788-c7f1-4ffb-b430-0ad557f608c5" />
