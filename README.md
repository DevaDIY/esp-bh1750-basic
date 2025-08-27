# esp-bh1750-basic
ESP32 + BH1750 Light Sensor Project – ตัวอย่างโค้ดอ่านค่าแสงและแสดงผลผ่าน Serial Monitor
This project demonstrates how to use the BH1750 light sensor with an ESP32 board.
It reads the ambient light level in lux and prints the values via Serial Monitor.

🔧 Hardware Required

ESP32 DevKit v1

BH1750 Light Sensor (I2C)

Jumper wires

🔌 Wiring

VCC → 3.3V (หรือ 5V)

GND → GND

SDA → GPIO 21 (default ESP32 SDA)

SCL → GPIO 22 (default ESP32 SCL)

📦 Library

Install BH1750 library by Christopher Laws from Arduino IDE Library Manager.

▶️ How to Run

Connect the BH1750 sensor to the ESP32 as shown above.

Open Arduino IDE and install required library.

Upload the code from this repository to your ESP32.

Open Serial Monitor (115200 baud) to see the lux readings.
