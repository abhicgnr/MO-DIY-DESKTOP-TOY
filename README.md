# 🤖 MO Robot – Animated Robot Face using ESP32, OLED, and Servo

This project showcases **MO**, a simple and expressive robot face built using **ESP32**, an **OLED display**, and a **servo motor** to simulate eye-blinking and nodding motions.

MO brings life to embedded systems with **animated facial expressions** and **random servo movements**, giving the impression of personality and emotion.

> ✨ No motion sensor needed — this version focuses on animation and servo behavior only.

---

## 🧩 Components Used

- **ESP32** (WROOM, XIAO ESP32-S3, or compatible board)
- **0.96" OLED Display** (I2C, SSD1306)
- **SG90 Servo Motor** (for eyelid/neck motion)
- Jumper wires and breadboard
- Arduino IDE for programming

---

## 🖼️ Features

- Displays looping animated face frames on OLED
- Periodic random "nod" animation via the servo motor
- Smooth return-to-neutral servo behavior
- Minimalistic and expandable design

---

## 🧠 How It Works

- **OLED Display**: Displays frames stored in `all_frames.h`. These create a looping animation of facial expressions.
- **Servo Control**: Every few seconds, the servo randomly nods the "head" (or eyelid), then returns smoothly.
- **Random Timing**: Nod intervals are randomized to add more personality and prevent robotic predictability.

---

## 🔧 Pin Connections

| Component     | ESP32 Pin |
|---------------|-----------|
| OLED SDA      | GPIO 21   |
| OLED SCL      | GPIO 22   |
| Servo Signal  | GPIO 13   |
| Servo VCC     | 5V        |
| Servo GND     | GND       |

---
# file toward video //  https://drive.google.com/file/d/1NJbE0hK12aVupZtRDtknpgl93zq41Yuk/view?usp=drive_link
## 📁 File Structure

