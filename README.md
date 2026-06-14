# 🎮 BuzzBattle – Smart Quiz Arena

A real-time quiz buzzer system built using the **Shrike Lite RP2040** development board and an **I/O Shield**, designed to ensure fair and accurate participant response detection during quiz competitions.

The system instantly identifies the first participant to press their buzzer, locks all other inputs, and displays the winner, eliminating manual judgment errors and improving competition fairness.

---

## 🚀 Overview

BuzzBattle is an embedded systems project that demonstrates real-time event handling using the RP2040 microcontroller. Multiple push-button inputs are monitored simultaneously, and the first valid press is recorded with priority over all subsequent inputs.

Once a participant buzzes in:

- The winner is identified immediately.
- Remaining buzzers are disabled.
- Visual feedback is provided through the display.
- The system can be reset for the next question.

---

## ✨ Features

- ⚡ First-Press Detection Logic
- 🏆 Instant Winner Identification
- 🔒 Input Lockout Mechanism
- 📟 Seven-Segment Display Feedback
- 🔄 Reset for New Round
- 🎯 Low-Latency Response Handling
- 🛠️ RP2040-Based Embedded Implementation

---

## 🧩 Hardware Used

### Controller
- Shrike Lite RP2040 Development Board

### Interface Hardware
- I/O Shield
- Push Buttons (Participants)
- Seven Segment Display
- Buzzer
- Breadboard & Jumper Wires

---

## ⚙️ System Architecture

```text
Participant Buttons
         │
         ▼
 ┌─────────────────┐
 │ Shrike Lite     │
 │ RP2040 Board    │
 └─────────────────┘
         │
         ▼
 ┌─────────────────┐
 │ First Press     │
 │ Detection Logic │
 └─────────────────┘
         │
         ▼
 ┌─────────────────┐
 │ Display Output  │
 └─────────────────┘
```

---

## 🛠️ Software

- Embedded C/C++
- Arduino IDE
- RP2040 Core
- GPIO Interrupt/Polling Logic

---

## 📸 Hardware Platform

### Shrike Lite RP2040
Compact RP2040-based development board used as the main controller.

### I/O Shield
Provides integrated buttons, display, buzzer, sensors, and expansion interfaces, enabling rapid prototyping and testing.

---

## 🎯 Learning Outcomes

- Embedded Firmware Development
- GPIO Handling
- Real-Time Input Processing
- Event Prioritization
- Hardware Interfacing
- System Testing & Debugging

---

## 🚀 Future Enhancements

- Wireless Buzzers using ESP32
- OLED Scoreboard
- Team-Based Quiz Mode
- Mobile/Web Dashboard
- Sound and Light Effects
- Automatic Score Tracking

---

## 👩‍💻 Author

**Sakshi Gupta**  
Automation & Robotics Engineering Student  
Passionate about Industrial Automation, Embedded Systems, IoT, and Robotics.

- GitHub: https://github.com/saksysus
- LinkedIn: https://www.linkedin.com/in/saksysus/
---

⭐Contributions, suggestions, and feedback are always welcome.
