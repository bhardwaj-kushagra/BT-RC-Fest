![922594a2-70d3-4f8c-885c-69eaf861c82b (4)](https://github.com/user-attachments/assets/d393a214-d10d-4a6f-b46f-f923e0782c0c)
## CIRCUIT DIAGRAM

# Bluetooth-Controlled RC Car 🚗💨

This project is all about building a **Bluetooth-controlled RC car** using an **Arduino Uno**, **HC-05 Bluetooth module**, and an **L298N motor driver**. The car can be controlled wirelessly via an Android app, making it a fun and practical DIY robotics project!

## 🚀 Features
- **Bluetooth Control** – Drive the car remotely using a smartphone.
- **Smooth Navigation** – Forward, backward, left, and right movements.
- **Speed Control** – Adjust speed via PWM signals.
- **Compact & Efficient** – Low power consumption for longer runtime.
- **DIY-Friendly** – Simple to assemble and program.

## 🔧 Components Used
- **Arduino Uno** – The brain of the car.
- **HC-05 Bluetooth Module** – Enables wireless control via Android.
- **L298N Motor Driver** – Controls the DC motors.
- **BO Motors (x2)** – Provides movement.
- **Wheels & Chassis** – The frame of the car.
- **Battery Pack** – Powers the system.

## 📲 How It Works
1. Pair the HC-05 Bluetooth module with your smartphone.
2. Use an **Android app** (like Arduino Bluetooth Controller) to send control signals.
3. The Arduino processes the signals and drives the motors accordingly.
4. The car responds to commands and moves in the desired direction.

## 🔧 Setup & Wiring
- **HC-05 to Arduino**
  - VCC → 5V
  - GND → GND
  - TX → RX (via 1KΩ + 2KΩ voltage divider)
  - RX → TX
- **L298N Motor Driver**
  - IN1, IN2, IN3, IN4 → Arduino Digital Pins
  - Motor terminals → BO motors
  - 12V Power → Battery Pack

## 🎯 Future Improvements
- Add obstacle detection using **ultrasonic sensors**.
- Implement **voice control** for hands-free operation.
- Integrate **WiFi control** for long-range operation.

## 📜 License
This project is open-source. Feel free to modify and improve it!

---

🔥 **Let's build & race!** If you liked this project, consider giving it a ⭐ on GitHub!


