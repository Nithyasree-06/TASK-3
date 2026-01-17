# TASK-3
ESP32 Web Dashboard for Live Sensor Monitoring & Control
Project Overview :

This project implements a web-based dashboard hosted on an ESP32 that displays live sensor data and allows remote control of a digital output (LED/relay) through a web browser.
The dashboard is served directly by the ESP32 over Wi-Fi without any external server.
Implemented as part of the Embedded Systems Internship at Alfido Tech.

ObjectiveS :

Host a web server on ESP32
Display real-time sensor data on a web dashboard
Control an LED/relay remotely using a browser
Understand Wi-Fi based embedded system control

Hardware Used :

ESP32
DHT11 Sensor
LED 
Resistors & Jumper Wires
Power Supply

Software & Libraries :

ESP32 Arduino Core
WiFi.h
ESPAsyncWebServer / WebServer
DHT.h (sensor library)

Working Principle :

ESP32 connects to a Wi-Fi network
A web server runs on the ESP32
HTML, CSS, and JavaScript are embedded in the sketch
Sensor values are updated on the dashboard
User can toggle LED/relay using web buttons
Commands are handled via HTTP requests

Functional Flow :

ESP32 connects to Wi-FI
Web server starts and serves dashboard page
Sensor data is read periodically
Browser fetches updated values
User input toggles digital output in real time

How to Run :

Configure Wi-Fi credentials in code
Upload sketch to ESP32
Open Serial Monitor to get IP address
Enter IP address in browser
View sensor data and control output

Output :

Live sensor values displayed on browser
LED/relay toggled remotelY
Web dashboard updates in real time

Skills Demonstrated :

ESP32 Wi-Fi networking
Embedded web server
HTML/JS integration in microcontroller
Real-time sensor monitoring
Remote device control

Internship
Embedded Systems Internship – Alfido Tech
