# Arduino_Projects - TOTAL PROJECTS (2)

### Project 1: DHT11 Sensor with I2C LCD

This project demonstrates how to use the **DHT11** sensor to read temperature and humidity and display the results on an **I2C LCD** using Arduino.

## Components Needed
- **DHT11 Sensor**
- **I2C LCD (16x2)**
- **Arduino Board**
- **Jumper Wires**

## Wiring
- **DHT11**: 
  - VCC to 5V or 3.3V
  - GND to GND
  - DATA to Pin 2
- **I2C LCD**: 
  - VCC to 5V
  - GND to GND
  - SDA to A4
  - SCL to A5

## Libraries
- **SimpleDHT**: To read data from the DHT11 sensor.
- **LiquidCrystal_I2C**: To control the I2C LCD.

![WhatsApp Image 2025-01-01 at 16 40 55_939cf5f8](https://github.com/user-attachments/assets/eead3951-38bc-47fa-899b-4e108c9b58a9)


https://github.com/user-attachments/assets/1c53656b-c74e-41b4-b892-7cb3a9ecf764

### Project 2: ULTRASONIC PARKING ASSISTANT


This project uses an ultrasonic sensor to measure distance and provides parking assistance by displaying messages on an I2C LCD and controlling LEDs for visual alerts.

---

## Components Needed
1. **Ultrasonic Sensor (HC-SR04)**  
2. **I2C LCD (16x2)**  
3. **Arduino Board**  
4. **Red LED**  
5. **Green LED**  
6. **Jumper Wires**  

---

## Wiring
### Ultrasonic Sensor (HC-SR04):
- **VCC** to 5V  
- **GND** to GND  
- **Trig** to Pin 7  
- **Echo** to Pin 6  

### I2C LCD:
- **VCC** to 5V  
- **GND** to GND  
- **SDA** to A4 (on Arduino UNO)  
- **SCL** to A5 (on Arduino UNO)  

### LEDs:
- **Red LED (Positive)** to Pin 2  
- **Green LED (Positive)** to Pin 8  
- **Negative Terminals** of both LEDs to GND (via 220Ω resistors).  

---

## Libraries
1. **LiquidCrystal_I2C**: To control the I2C LCD.  



https://github.com/user-attachments/assets/c873ac69-5558-4ce3-9875-0406fb87c6c3



More projects uploading soon! 🚀

Happy coding! 😊
