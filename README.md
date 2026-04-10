# Ultransonic-sensor# Ultrasonic Distance Sensor with Arduino

A simple yet effective project using **Arduino** and **HC-SR04** ultrasonic sensor to measure distance accurately. The results are displayed in both centimeters and inches on the Serial Monitor.



## ✨ Features
- Accurate distance measurement (approx. 2cm to 400cm)
- Real-time output in **cm** and **inches**
- Well-commented and easy-to-understand code
- Easy to expand (LCD, OLED, buzzer, parking sensor, etc.)

## 🛠 Hardware Components
- Arduino Uno / Nano / Mega
- HC-SR04 Ultrasonic Sensor
- Jumper wires
- Breadboard (optional)

## 📌 Circuit Connections

| HC-SR04 Pin | Arduino Pin |
|-------------|-------------|
| VCC         | 5V          |
| Trig        | **9**       |
| Echo        | **10**      |
| GND         | GND         |

> *You can change the trigger and echo pins in the code if needed.*

## 🚀 How to Use

1. Clone or download this repository
2. Open the `ultrasonic_sensor.ino` file in **Arduino IDE**
3. Connect the sensor as shown in the table above
4. Upload the code to your Arduino
5. Open the **Serial Monitor** (Baud rate = 9600)

You should start seeing live distance readings.



## How It Works
The HC-SR04 sensor sends out ultrasonic waves. When the waves hit an object, they bounce back. The Arduino measures the time between sending and receiving the signal and calculates the distance using the speed of sound.

## Future Improvements
- Add an LCD or OLED display
- Add a buzzer for proximity alert
- Create a smart parking assistant
- Connect with Bluetooth to show data on mobile

---


⭐ If you like this project, please give it a star!
