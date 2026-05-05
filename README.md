# 🤖 Project Legion Robot

![Robot](https://via.placeholder.com/1200x400?text=Project+Legion+Robot)

![Platform](https://img.shields.io/badge/Platform-Arduino%20%7C%20ESP32%20%7C%20RaspberryPi-blue)
![Type](https://img.shields.io/badge/Project-Robotics-green)
![Status](https://img.shields.io/badge/Status-Active-brightgreen)
![License](https://img.shields.io/badge/License-MIT-yellow)

A powerful **12 DOF humanoid robot** built using **Arduino, ESP32, and Raspberry Pi**, designed for modular robotics development, real-time control, and future AI integration.

---

## 📸 Project Preview

![Preview](https://via.placeholder.com/800x400?text=Robot+Preview)

---

## 🚀 Features

* 🤖 12 Degrees of Freedom (DOF)
* 🔌 Multiple hardware configurations
* 📡 Serial, I2C, and WiFi-based control
* 🎥 Live streaming (ESP32-CAM version)
* 🧠 Ready for AI/ML integration
* 🧩 Modular and upgrade-friendly design

---

## ⚙️ Versions Available

### 🔹 Arduino (Basic)

* Arduino Nano + Expansion Board
* Serial Monitor Control
* Beginner-friendly setup

---

### 🔹 Arduino + PCA9685 Servo Driver

* 16-channel servo driver
* Solves pin limitations
* I2C communication (SDA/SCL)

---

### 🔹 Arduino + ESP32-CAM

* Live video streaming
* Remote control interface
* Communication via RX/TX

---

### 🔹 ESP32 Version

* Standalone ESP32 control
* ⚠️ FlexiTimer2 not supported
* Open for improvements

---

### 🔹 Raspberry Pi Version

* Python-based control
* Designed for AI/ML integration
* Uses Raspberry Pi 4

---

### 🔹 Legion Mark 2

* Most advanced version
* Improved performance & design
* 🎥 Demo: *(Add your YouTube link here)*

---

## 🛠️ Getting Started

### 🔧 Build Steps

1. 3D print the robot structure
2. Choose your preferred version
3. Attach servos *(without horns)*
4. Run `Servo_Config` → set all to **90°**
5. Attach servo horns correctly
6. Complete wiring using circuit diagrams
7. Upload main code
8. 🎉 Power ON and test

---

## 📂 Project Structure

```bash
Project-Legion-Robot/
│
├── hardware/
│   ├── 3d-models/
│   ├── circuit-diagrams/
│
├── software/
│   ├── arduino/
│   ├── esp32/
│   ├── raspberry-pi/
│
├── media/
├── docs/
└── README.md
```

---

## 📁 Resources

* 📦 3D Models → `/3D Files`
* 🔌 Circuit Diagrams → `/Circuit Diagrams`
* 📸 Images → `/media`
* 🧾 Docs → `/Documents`

---

## ⚠️ Important Notes

* Ensure correct servo alignment before powering
* Double-check wiring connections
* Some modules may need updates

---

## 🙏 Credits

Inspired by **SunFounder Robot**
📧 [panerqiang@sunfounder.com](mailto:panerqiang@sunfounder.com)

---

## 🤝 Contributing

Contributions are welcome!

* Improve ESP32 timer handling
* Add AI features
* Optimize code structure

---

## 🔮 Future Scope

* 🗣 Voice control
* 👁 Computer vision
* 📱 Mobile app control
* 🤖 Autonomous movement

---

## ⭐ Support

If you like this project, consider giving it a ⭐ on GitHub!
