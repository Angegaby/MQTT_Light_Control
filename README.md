<<<<<<< HEAD
# MQTT Light Control 💡  
A web-based application that allows users to turn a light ON/OFF over MQTT.  
It also simulates an IoT device (ESP8266) using Python, which listens for MQTT messages and prints the light status.

## Features  
- 🌍 Web interface with ON/OFF buttons  
- 💡 Light bulb icon that changes state  
- 📡 MQTT.js for real-time communication  
- 🐍 Python script simulating an IoT device  
- 🔄 Live status updates based on MQTT messages  

## Installation & Setup  
### 📌 Web Interface  
1. Open `index.html` in a browser  
2. Click the ON/OFF buttons to send MQTT messages  

### 🐍 Simulated IoT Device  
1. Install dependencies:  
   ```bash
   pip install paho-mqtt
   ```  
2. Run the Python script:  
   ```bash
   python light_simulation.py
   ```  
3. Check the console for light status updates  

## MQTT Configuration  
- **Broker:** `wss://test.mosquitto.org:8081`  
- **Topic:** `/student_group/light_control`  

## Project Structure  
```plaintext
📂 MQTT-Light-Control  
 ┣ 📜 index.html        # Web UI (Frontend)  
 ┣ 📜 light_simulation.py  # Python MQTT Subscriber (Simulated IoT)  
 ┣ 📜 README.md         # Project Documentation  
```

## How It Works  
1️⃣ The web page sends an MQTT message (`ON` or `OFF`) when a button is clicked  
2️⃣ The Python script listens to the topic and prints "Light is TURNED ON/OFF"  
3️⃣ The UI updates the bulb color based on the sent command  


## License & Credits  
📜 MIT License  
🚀 Developed by NDUWINGOMA Marie Ange Gabriella  


=======
# MQTT_Light_Control
>>>>>>> 84dbf0a09f056d9fd51f7beb0d018be30f4659c1
