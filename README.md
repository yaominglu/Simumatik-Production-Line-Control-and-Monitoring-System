# Simumatik-Production-Line-Control-and-Monitoring-System
Simumatik Production Line Control and Monitoring System
This project is designed to control and monitor a factory production line simulation using Simumatik. The system integrates Python for controlling the factory components, MQTT for communication, and Node-RED for dashboard visualization. The project supports real-time monitoring of Key Performance Indicators (KPIs) such as Overall Equipment Effectiveness (OEE), production rates, and error handling.

·Features：
Dual Production Line Control: Manages two separate production lines (left and right), each capable of producing different products (lids or bases).  
Real-time Monitoring: Tracks production metrics including busy time, idle time, error time, and total production.
Collision Prevention: Ensures no product collision occurs when both production lines merge.
Batch Production: Supports batch production with customizable batch sizes.
MQTT Integration: Communicates with a dashboard via MQTT for real-time KPI updates and system control.
Node-RED Dashboard: Visualizes the system's performance, allowing start/stop control, error resets, and production rate monitoring.

·Technologies Used：
Python: For system control and KPI calculations.
MQTT (paho-mqtt): For communication between the Python script and the Node-RED dashboard.
Node-RED: For building a dashboard to visualize and control the production system.
Simumatik: A simulation environment for factory automation.

·Getting Started：
Set up MQTT: Install a broker such as Mosquitto or use Aedes within Node-RED.
Install Node-RED: Set up the necessary packages for the dashboard.
Run the Python script: Use the provided Main.py to control the system and monitor KPIs.
