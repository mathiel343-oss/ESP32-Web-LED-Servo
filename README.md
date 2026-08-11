# ESP32 Web Control

---

##  Project Overview

-  **Part 1:** LED control using digital values (0 and 1).
-  **Part 2:** Servo motor angle control through a web interface.

---

#  Part 1 — Web LED Control

###  Wiring

| Component | ESP32 |
|---|---|
| LED Signal | GPIO 2 |
| LED GND | GND |
| Resistor | Series with LED |

###  Wiring Photo
<img width="230" height="302" alt="led-wiring" src="https://github.com/user-attachments/assets/7f129dad-7599-4dbe-98cf-95bbb3aad128" />



### Web Control


<img width="956" height="505" alt="led-wep" src="https://github.com/user-attachments/assets/855050d4-f726-4cc7-876d-d0aef6123a60" />




| Input | Result |
|---|---|
| `1` | LED ON |
| `0` | LED OFF |

###  Demo




https://github.com/user-attachments/assets/ed2035b0-9be0-465b-9df9-88c907f45f33



---

#  Task 2 — Web Servo Control

###  Wiring
| Servo Wire | Function | ESP32 |
|---|---|---|
|  Yellow | Signal | GPIO 18 |
|  Brown | GND | GND |
|  Red | VCC | 5V / VCC |

###  Wiring Photo

<img width="273" height="307" alt="Servo-Wiring" src="https://github.com/user-attachments/assets/acc65bd5-628e-484f-935c-0077eec003a1" />

###  Web Control
<img width="953" height="509" alt="Wep-Servo" src="https://github.com/user-attachments/assets/3fd58afb-7524-4dbb-a715-d56f09a86ebd" />


| Angle | Action |
|---|---|
| 0° | Move Servo |
| 45° | Move Servo |
| 90° | Move Servo |
| 135° | Move Servo |
| 180° | Move Servo |

###  Demo


https://github.com/user-attachments/assets/22c66f8b-b5bd-401b-83c0-90692f6a7269



---

#  Network & Access

| Setting | Value |
|---|---|
| Wi-Fi SSID | `mathayelESP` |
| Password | `123456789` |
| Web Address | `http://192.168.4.1` |

---

#  Tools & Technologies

- ESP32
- Arduino IDE
- Wi-Fi Access Point
- Web Server
- HTML / CSS / JavaScript
- ESP32Servo Library

---

#  Final Result

| Task | Status |
|---|---|
| Web LED Control |  Completed |
| Web Servo Control |  Completed |
| Local Wi-Fi Network |  Completed |
| Web Interface |  Completed |
