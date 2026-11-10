# Portable IoT Traffic Light System with Solar Energy

> 🏆 **Consolation Prize** — Faculty-level Scientific Research Competition  
> 📅 Jan – Mar 2025

---

## 📌 Overview

A **portable, solar-powered smart traffic light** system that dynamically adjusts signal timing based on **real-time vehicle density** using computer vision (YOLOv8).

Traditional fixed-timing traffic lights waste time on empty roads. Our system detects the number of vehicles in each lane and allocates green light time proportionally — reducing unnecessary waiting and improving traffic flow.

---

## 🏗️ System Architecture

```
┌─────────────────────────────────────────────────┐
│              Portable Traffic Light              │
│                                                 │
│  ☀️ Solar Panel                                 │
│       │                                         │
│       ▼                                         │
│  🔋 Battery + Charge Controller                 │
│       │                                         │
│       ▼                                         │
│  📷 Camera ──► YOLOv8 Detection ──► Vehicle     │
│                                      Count      │
│                    │                   │        │
│                    ▼                   ▼        │
│              STM32 MCU ◄──────── Signal Timer   │
│                    │                            │
│                    ▼                            │
│            🚦 Traffic Light LEDs                │
└─────────────────────────────────────────────────┘
```

---

## 🛠️ Tech Stack

| Component | Technology |
|-----------|-----------|
| Microcontroller | STM32 |
| Object Detection | YOLOv8 |
| Power System | Solar Panel + LiPo Battery |
| Communication | UART / IoT |
| Programming | C (STM32), Python (YOLOv8) |

---

## 👥 My Contributions

- ☀️ Designed and implemented the **solar power subsystem** (panel sizing, charge controller, battery management)
- 🔌 Integrated STM32 with the detection output for real-time signal control
- 🤝 Collaborated with teammates on YOLOv8-based vehicle density detection

---

## 🏆 Achievement

> **Consolation Prize** at the Faculty-level Scientific Research Competition  
> Danang University of Science and Technology — March 2025

---

## 📸 Results

- System reliably detected vehicle density across multiple test scenarios
- Signal timing adapted dynamically based on lane occupancy
- Fully portable — solar powered, no external wiring required

---

## 👨‍💻 Author

**Bui Thai Phuoc**  
Control and Automation Engineering, DNUT  
📧 thaiphuocbui2310@gmail.com  
🔗 [linkedin.com/in/thaiphuocbui](https://linkedin.com/in/thaiphuocbui)

---

## 📄 License

MIT License — see [LICENSE](LICENSE) for details.
