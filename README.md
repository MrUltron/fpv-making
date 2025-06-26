# 🛩️ FPV Drone DIY Project

Build your own FPV (First Person View) drone with real-time video transmission and full manual control using an RC transmitter. This project is ideal for hobbyists, students, and DIY drone enthusiasts.

---

## 📦 Components Required

| Category          | Component                         | Description                      |
| ----------------- | --------------------------------- | -------------------------------- |
| Frame             | 220mm Quadcopter Frame            | Carbon fiber recommended         |
| Motors            | 2204/2205 2300KV Brushless        | 4 motors for quad configuration  |
| ESCs              | 20A–30A BLHeli                    | Speed controllers for each motor |
| Flight Controller | F4 / F7 (Betaflight Compatible)   | Central controller               |
| Propellers        | 5-inch (5045)                     | Two CW and two CCW               |
| Battery           | 3S or 4S LiPo (1300–1500mAh)      | High C-rating recommended (≥75C) |
| FPV Camera        | RunCam Nano / Caddx Ant           | Small analog camera              |
| Video Transmitter | 5.8GHz VTX (25–800mW)             | For video transmission           |
| Antenna           | Pagoda / Cloverleaf               | 5.8GHz circular polarized        |
| FPV Goggles       | Eachine / FatShark / Skyzone      | Video receiver & screen          |
| RC Transmitter    | FlySky / FrSky / Radiomaster      | With receiver                    |
| Tools             | Soldering iron, heat shrink, etc. | For wiring and assembly          |

---

## 🛠️ Assembly Overview

1. **Frame Assembly**

   * Mount arms and secure motor mounts
2. **Motor & ESC Connection**

   * Solder each motor to its ESC
   * Connect ESC signal wires to FC
3. **Install Flight Controller**

   * Mount using anti-vibration pads
   * Wire up ESCs, receiver, and VTX
4. **Install FPV Camera**

   * Mount at a 20–30° angle
   * Connect to VTX via FC (if applicable)
5. **Power Distribution**

   * Use a PDB or 4-in-1 ESC stack
   * XT60 connector for battery input
6. **Receiver Binding**

   * Connect SBUS/IBUS to UART
   * Bind with RC transmitter
7. **Propeller Setup**

   * Match direction with Betaflight motor preview

---

## 💻 Software Setup

1. Download and install [Betaflight Configurator](https://github.com/betaflight/betaflight-configurator/releases)
2. Connect flight controller via USB
3. Configure:

   * Receiver protocol (SBUS/IBUS)
   * Motor direction and mixer
   * Modes: ARM, ANGLE, ACRO, etc.
   * Enable OSD (if supported)
4. Test motor response (remove props!)

---

## 🧪 Pre-Flight Checklist

* ✅ All connections secured and insulated
* ✅ Motors spin in correct direction
* ✅ ESCs calibrated (if needed)
* ✅ Transmitter bound and channels mapped
* ✅ Video feed visible in FPV goggles

---

## 🚀 Optional Enhancements

* Add GPS for RTH (Return to Home)
* Use buzzer or LED status indicators
* Add lost model finder
* Upgrade to HD FPV system (e.g., DJI O3)

---

## 📚 Resources

* [OscarLiang's FPV Blog](https://oscarliang.com/)
* [RotorBuilds - Custom FPV Builds](https://rotorbuilds.com/)
* [Betaflight Wiki](https://github.com/betaflight/betaflight/wiki)

---

## 📜 License

MIT License

---

## 👨‍💻 Author

**Jaywing Technology**
Email: [support@jaywingtech.in](mailto:support@jaywingtech.in)

Fly safe and build smart! ✈️📹
