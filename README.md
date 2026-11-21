🏫 Smart Campus – Real-Time Monitoring System

An ESP32-based Smart Campus monitoring prototype developed during the SVVV Hardware Hackathon, Indore.

The project monitors environmental conditions and water tank levels using sensors and displays the readings on an LCD.

🚀 Features

- 🌡️ Real-time temperature monitoring.
- 💧 Humidity monitoring.
- 🚰 Water tank level measurement.
- 📊 Water percentage calculation.
- 🔔 Automatic buzzer alert when the tank is almost full.
- 🖥️ LCD-based data visualization.
- 🔄 Button-controlled display switching.

🛠️ Hardware Components

Component| Purpose
ESP32| Main controller
DHT22| Temperature and humidity
HC-SR04| Water level measurement
16×2 I2C LCD| Display
Buzzer| Alert system
Push Button| User control

🔌 Pin Connections

Component| ESP32 GPIO
DHT22 Data| GPIO 4
Ultrasonic TRIG| GPIO 5
Ultrasonic ECHO| GPIO 18
Buzzer| GPIO 26
Push Button| GPIO 27
LCD SDA| GPIO 21
LCD SCL| GPIO 22

Note: Use a voltage divider on the HC-SR04 ECHO pin to protect the ESP32.

💻 Technologies Used

- C/C++
- ESP32
- Arduino Framework
- DHT Sensor Library
- LiquidCrystal_I2C
- Embedded Systems & IoT

⚙️ How It Works

1. ESP32 collects temperature and humidity data from DHT22.
2. HC-SR04 measures the distance to the water surface.
3. Water level and percentage are calculated.
4. Buzzer activates when the tank reaches the configured full-level threshold.
5. LCD displays environmental and water-level information.
6. Push button switches between display screens.

🔮 Future Scope

- Wi-Fi-based data transmission.
- Mobile and web monitoring dashboard.
- Cloud data storage.
- Remote notifications.
- Smart campus infrastructure monitoring.

Note: These are planned improvements, not implemented features.

👨‍💻 Project Information

- Event: SVVV Hardware Hackathon, Indore
- Project: Smart Campus
- Role: Team Leader
- Contribution: Programming, hardware interfacing, sensor integration, and debugging.

🙌 Acknowledgement

Thanks to SVVV and my teammates for providing this valuable learning experience.

Although we didn't win, we gained practical experience in embedded systems, hardware integration, programming, and teamwork.

Keep Learning. Keep Building. Keep Innovating! 🚀

⭐ If you find this project interesting, consider starring this repository
