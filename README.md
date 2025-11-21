#crop-health-monitoring-system
📌 Description

IoT-based Crop Health Monitoring System built using ESP32 and low-cost sensors.
This project collects real-time environmental and soil parameters to detect early plant stress.
It uses:

Capacitive Soil Moisture Sensor

DS18B20 Waterproof Soil Temperature

BME280 (Air Temperature, Humidity, Pressure)

BH1750 Light Intensity Sensor

ESP32 Microcontroller

Optional Wi-Fi Upload (HTTP or MQTT)

The system converts sensor readings to actionable insights such as water stress, humidity-based disease risk, and low-light detection.
It outputs data as JSON via Serial, and can also upload to cloud dashboards using Wi-Fi.

📌 Features

Real-time soil moisture percentage

Soil temperature monitoring

Air temperature & humidity logging

Light intensity measurement (lux)

Threshold-based alerts (e.g., moisture < 25%)

Optional Wi-Fi + MQTT + Google Sheets integration

Fully open-source and low-cost hardware solution

📌 Technologies Used

ESP32

Arduino Framework

I²C Sensors (BME280, BH1750)

OneWire (DS18B20)

ADC Input (Soil Moisture)

Wi-Fi Networking

JSON Data Encoding

📌 Folder Structure
/code
  ├── esp32_main.ino
  ├── mqtt_version.ino
  ├── http_upload.ino
/hardware
  ├── wiring_diagram.png
  ├── hardware_list.pdf
/docs
  ├── project_report.pdf
  ├── block_diagram.png

📌 Use Cases

Precision agriculture

Smart irrigation

Disease risk forecasting

Greenhouse monitoring

Research & student IoT projects

📌 License

MIT License — free to use, modify, and distribute.
