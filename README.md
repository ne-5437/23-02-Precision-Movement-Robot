# Precision Moment Robot

The **Precision Moment Robot** is a highly maneuverable robotic platform designed to achieve high precision movement using stepper motors and motor drivers. The robot is powered by a **NodeMCU ESP8266** and controlled over Wi-Fi. The project integrates wireless control and precise stepper motor operations for fine movement control, which is ideal for applications requiring accuracy and fine adjustments.

### Key Features:
- **Wi-Fi Control**: The robot can be controlled remotely through a Wi-Fi connection using the ESP8266.
- **Precision Movement**: Stepper motors are used to drive the wheels, allowing precise movements in forward, reverse, left, right, and stop directions.
- **Stepper Motor Drivers**: Four stepper motors are used, two for each set of wheels (front and back).
- **Maneuverability**: The robot can move in different directions, allowing it to navigate easily with high precision.

---

## Hardware Components

- **NodeMCU ESP8266**: Microcontroller for Wi-Fi connectivity and control.
- **Stepper Motors (4)**: Two for each set of wheels (front and back) for accurate movement.
- **Motor Drivers (ULN2003)**: To drive the stepper motors.
- **Power Supply**: Adequate power supply to run the motors and the NodeMCU.
- **Wires & Connectors**: For connecting the motors and motor drivers to the ESP8266.

---

## Software Requirements

- **Arduino IDE**: To upload the code to the ESP8266.
- **AccelStepper Library**: For controlling the stepper motors with fine precision.

Install the **AccelStepper** library in the Arduino IDE through the Library Manager.

---

#### Key Functions:
1. **Wi-Fi Connection**: The NodeMCU connects to a specified Wi-Fi network using the provided SSID and password.
2. **Motor Movement**: Depending on the received command, the robot moves forward, backward, left, right, or stops.
3. **Web Server**: A basic web server is hosted on the NodeMCU to receive control commands.
4. **Stepper Motor Control**: The stepper motors are controlled to perform precise movements in the specified directions.

