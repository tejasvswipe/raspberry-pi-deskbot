# DeskBot 

DeskBot is an autonomous/remotely controlled desktop companion robot built around the **Raspberry Pi 4**. It features two-way audio communication (listening and speaking), a two-wheel motorized drivetrain, inertial sensing, and custom 3D-printed hardware enclosures designed in Fusion 360.

---

## Key Features

*   **Audio Interaction:** Speaks via an amplified speaker and listens through a dedicated microphone.
*   **Locomotion:** Two-motor drivetrain powered by a dedicated motor driver module.
*   **Motion Tracking:** Equipped with an MPU-4050 IMU sensor for precise orientation and movement monitoring.
*   **Wireless Control:** Integrated transmitter and receiver setup for manual overrides or telemetry.
*   **Cloud Intelligence:** Powered by an external API key for advanced conversational or processing capabilities.
*   **Custom Design:** Features bespoke 3D-printable chassis components (`.f3d` Fusion 360 files included).

---

##  Hardware Architecture

### Core Components
*   **Compute:** Raspberry Pi 4
*   **Audio Output:** Microphone & Speaker connected via an Audio Amplifier Module
*   **Locomotion:** 2x DC Motors managed by a Motor Driver Module (e.g., L298N / L293D / TB6612FNG)
*   **Telemetry & Control:** MPU-4050 IMU Sensor + RF/RC Transmitter & Receiver

### Power Management
*   **Battery:** 5000 mAh, 3.7V Lithium-Ion/Polymer battery
*   **Regulation:** High-efficiency Buck Converter (steps up/stabilizes voltage to 5V required by the Raspberry Pi)

---


## ⚙️ Setup & Installation

### 1. Hardware Assembly
1. Connect the **3.7V 5000mAh battery** to the input of the **Buck Converter**. Tune the converter output strictly to **5V** before connecting it to the Raspberry Pi 4 GPIO or USB-C power rails.
2. Interface the **Motor Module** to the Raspberry Pi 4 GPIO pins and attach both drivetrain motors.
3. Wire the **MPU-4050** sensor to the I2C pins (`SDA`/`SCL`) of the Pi.
4. Hook up the **Microphone** and connect the **Amplifier + Speaker** setup to the audio jack or a dedicated USB audio adapter.
5. Connect your **Receiver** channels to the designated GPIO digital input pins.




## 📐 3D Modeling

The physical chassis, brackets, and mounts were built using **Autodesk Fusion 360**. You can find the fully editable design file under `\cad`. fusion 360 to modify tolerances, add component mounts, or export `.f3d` `.STL` files for 3D printing.
 yepiee stuff is done i  have tea  ppl can  dm  on @tejas67