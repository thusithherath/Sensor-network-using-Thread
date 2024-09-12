# Sensor Network Using Thread Protocol

## Project Overview

This project implements a **Fire Alarm System** using the **Thread protocol** to connect multiple nodes that detect fire. Each node consists of an **ESP32-H2 board** integrated with a fire detection sensor. The nodes communicate with each other over a low-power, mesh network powered by the Thread protocol, ensuring a reliable and scalable solution for fire monitoring.

## Features

- **Fire Detection**: Each node is equipped with a fire detection sensor that triggers an alarm when fire or excessive heat is detected.
- **Thread Protocol**: All nodes are connected using the Thread protocol, providing a low-latency and energy-efficient network for communication.
- **Scalable Network**: The mesh architecture of Thread allows the network to expand by adding more nodes without degrading performance.
- **Real-Time Alarms**: The system provides real-time fire detection alerts by ringing alarms and notifications.
- **Low-Power Consumption**: The ESP32-H2 board and Thread protocol ensure that the system consumes minimal power, making it suitable for long-term deployments.
- **Node Failure Detection**: The system continuously monitors the health of each node using a heartbeat mechanism. If a node fails or becomes unreachable, the system detects the failure and alerts the network.
- **Visual Node Status Display**: The OLED display shows real-time node status, alerting users if a node fails or goes offline.
- **Network Reliability**: The Thread protocol ensures a highly reliable network. Even if one node fails, the mesh network self-heals, allowing other nodes to continue communicating and the system to remain fully operational.

## Components

- **ESP32-H2 Board**: A microcontroller that supports Thread networking and acts as the core of each sensor node as well as a central node in the Thread mesh network, facilitating communication between nodes.
- **IR 3 Wire Flame Detection Sensor**: The sensor connected to each node for detecting fire or heat.
- **Buzzer**: Generates a sound when triggered, used to provide an audible fire alert.
- **OLED Display**: A display used to indicate the status of the nodes and show any node failures or alerts in real-time.
- **Power Supply**: Powering the ESP32-H2,Display,Buzzer and sensors.

## Setup and Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/thusithherath/Sensor-network-using-Thread
   ```
