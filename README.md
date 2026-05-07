# 🕷️ Project SpiderBot

A fully 3D printed 12DOF quadruped spider robot powered by an ESP32 and controlled using a custom mobile application.

This robot can walk, sit, move forward/backward, shake legs, and perform different motion actions using 12 servo motors.

---

#  Robot Preview

> Add your robot images here

```md
![Spider Robot](images/spiderbot.jpg)
```

---

#  Features

* 12DOF Quadruped Spider Robot
* Fully 3D Printed Design
* ESP32 Based Controller
* PCA9685 Servo Driver Support
* Custom Mobile App Control
* Forward & Backward Movement
* Sit & Stand Motions
* Front Leg Shake Motion
* Full Body Shake Motion
* Smooth Servo Movement Control
* Modular Design
* Easy to Upgrade

---

# Hardware Used

| Component                 | Quantity    |
| ------------------------- | ----------- |
| ESP32                     | 1           |
| Servo Motors (SG90/MG90S) | 12          |
| PCA9685 Servo Driver      | 1           |
| Battery Pack              | 1           |
| 3D Printed Parts          | Multiple    |
| Jumper Wires              | As Required |
| Switch                    | 1           |

---

# Robot Structure

Each leg contains:

* Coxa Joint
* Femur Joint
* Tibia Joint

### Total Configuration

* 4 Legs
* 3 Servos Per Leg
* 12 Degrees of Freedom

---

# Mobile App Functions

The custom app supports:

* Move Forward
* Move Backward
* Sit Position
* Stand Position
* Shake Front Legs
* Shake All Legs
* Custom Motions

---

#  Included Files

```bash
body_d.stl
body_u.stl
coxa_l.stl
coxa_r.stl
femur_l.stl
tibia_l.stl
tibia_r.stl
s_hold.stl
spider-open-v1.skp
```

All required 3D printable files are included in this repository.

---

# 3D Printing Settings

Recommended print settings:

```yaml
Layer Height: 0.2mm
Infill: 20% - 40%
Material: PLA
Supports: Yes (for some parts)
```

---

#  Electronics & Wiring

* ESP32 controls the PCA9685 Servo Driver
* Servo Driver controls all 12 servos
* External battery powers the servos
* ESP32 handles app communication and motion logic

---

#  Assembly Steps

1. Print all STL files
2. Install servo motors
3. Assemble all four legs
4. Assemble the main body
5. Connect servos to PCA9685
6. Connect ESP32 to the servo driver
7. Upload the code to ESP32
8. Connect battery power
9. Pair the mobile app
10. Start controlling the robot

---

# Future Improvements

* Obstacle Avoidance
* Ultrasonic Sensor Support
* Camera Module
* Voice Control
* Autonomous Walking
* AI Based Motion System

---

# Project Purpose

This project was built for:

* Robotics Learning
* ESP32 Development
* 3D Printing Practice
* Quadruped Motion Study
* DIY Robotics Projects

---

#  Contributions

Contributions are welcome.

You can improve:

* Walking algorithms
* App UI
* Motion control
* Power management
* Autonomous functions

---

#  Support

If you like this project, consider giving this repository a ⭐.

---

# 📜 License

This project is open-source and available under the MIT License.
