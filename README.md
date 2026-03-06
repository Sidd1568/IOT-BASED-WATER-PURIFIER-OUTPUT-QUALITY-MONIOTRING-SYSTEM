Water Quality Monitoring System using ESP32

📌 Project Overview

This project is a Water Quality Monitoring System that measures the Total Dissolved Solids (TDS) in water using a sensor and displays the value on an OLED screen.
If the water quality becomes poor, a buzzer alerts the user.

The collected data can also be analyzed using a Power BI dashboard for visualization and insights.
---

⚙️ Technologies Used
* Arduino (C++ based microcontroller programming)
* ESP32 Microcontroller
* TDS Sensor
* OLED Display (SSD1306)
* Buzzer
* Power BI for Data Visualization
---

🔧 Hardware Components
* ESP32 Development Board
* TDS Sensor
* OLED Display (128x64 SSD1306)
* Active Buzzer
* Jumper Wires
* Breadboard
---

 💻 Software Used
* Arduino IDE
* Power BI Desktop
---

🚀 Features
* Real-time water quality monitoring
* Displays TDS value (ppm) on OLED screen
* Automatic buzzer alert when water quality is poor
* Power BI dashboard visualization** for data analysis
* Simple and low-cost IoT based system
---

 📊 Power BI Dashboard

The collected data can be visualized using Power BI dashboards.

Dashboard Screenshot:

![Dashboard](dashboard.png)
---
 
 📁 Project Structure

water-quality-monitor
│
├── water_quality_monitor.ino
├── water_quality_dashboard.pbix
├── dashboard.png
└── README.md
---

 🧠 Working Principle

1. The TDS sensor measures dissolved solids in water.
2. The ESP32 microcontroller reads the analog value from the sensor.
3. The value is converted to TDS (ppm).
4. The reading is displayed on the OLED screen.
5. If the TDS value exceeds a threshold (e.g., 500 ppm), the buzzer alerts the user.
6. Data can be analyzed in Power BI to create dashboards and insights.
---

 📷 Project Output

Example Output Display:

![Project Output](dashboard.png)
---

👨‍💻 Author

Siddharth M




