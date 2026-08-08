<div align="center">
<p align="center">
  <img src="./header-v2.svg" width="100%" alt="Natthawut Chungam Header">
</p>

---

## 👨‍💻 About Me

I'm a **Robot Integration Engineer** from Thailand 🇹🇭, working with industrial robots, backend systems, automation, and network infrastructure.

My work focuses on connecting **robots ↔ APIs ↔ servers ↔ industrial equipment** and building tools for robot monitoring, control, and task dispatch.

<div align="center">
## 🏗️ System Architecture

```mermaid
flowchart LR

    Sensor["📡 Photo Sensor"]
    ESP["🔌 ESP32"]
    MQTT["📨 MQTT Broker"]
    Backend["⚙️ FastAPI Backend"]
    API["☁️ Robot REST API"]
    Robot["🤖 Robot"]
    DB[("🗄️ SQLite")]
    Web["🖥️ React Dashboard"]
    User["👤 Operator"]

    Sensor --> ESP
    ESP -->|MQTT| MQTT
    MQTT --> Backend

    Backend -->|REST API| API
    API --> Robot

    Robot -->|Status| API
    API -->|Status| Backend

    Backend <-->|Read / Write| DB

    User --> Web
    Web -->|Command| Backend
    Backend -->|WebSocket| Web
```
</div>

---

<div align="center">

<h2>🧩 Engineering Stack</h2>

<h3>🤖 Robotics & Automation</h3>

<img src="https://img.shields.io/badge/Robot_Integration-1E40AF?style=for-the-badge&logo=probot&logoColor=white" />
<img src="https://img.shields.io/badge/Fleet_Management-2563EB?style=for-the-badge&logo=probot&logoColor=white" />
<img src="https://img.shields.io/badge/Task_Dispatch-0284C7?style=for-the-badge&logo=probot&logoColor=white" />
<img src="https://img.shields.io/badge/Robot_Monitoring-0369A1?style=for-the-badge&logo=probot&logoColor=white" />
<br>
<img src="https://img.shields.io/badge/OpenAPI-6BA539?style=for-the-badge&logo=openapiinitiative&logoColor=white" />
<img src="https://img.shields.io/badge/MQTT-660066?style=for-the-badge&logo=mqtt&logoColor=white" />
<img src="https://img.shields.io/badge/ESP32-E7352C?style=for-the-badge&logo=espressif&logoColor=white" />
<img src="https://img.shields.io/badge/Sensors-F97316?style=for-the-badge&logoColor=white" />

<br><br>

<h3>⚡ Software & Backend</h3>

<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" />
<img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" />
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
<br>
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
<img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white" />
<img src="https://img.shields.io/badge/REST_API-2563EB?style=for-the-badge&logoColor=white" />
<img src="https://img.shields.io/badge/WebSocket-111827?style=for-the-badge&logo=socketdotio&logoColor=white" />
<br>
<img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" />
<img src="https://img.shields.io/badge/JSON-5E5C5C?style=for-the-badge&logo=json&logoColor=white" />
<img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />

<br><br>

<h3>🌐 Network & Infrastructure</h3>

<img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" />
<img src="https://img.shields.io/badge/MikroTik-293239?style=for-the-badge&logo=mikrotik&logoColor=white" />
<img src="https://img.shields.io/badge/TCP%2FIP-1D4ED8?style=for-the-badge&logoColor=white" />
<img src="https://img.shields.io/badge/LAN-0284C7?style=for-the-badge&logoColor=white" />
<br>
<img src="https://img.shields.io/badge/DHCP-0EA5E9?style=for-the-badge&logoColor=white" />
<img src="https://img.shields.io/badge/VLAN-4338CA?style=for-the-badge&logoColor=white" />
<img src="https://img.shields.io/badge/Wi--Fi-06B6D4?style=for-the-badge&logo=wifi&logoColor=white" />
<img src="https://img.shields.io/badge/SSH-111827?style=for-the-badge&logo=gnubash&logoColor=white" />
<br>
<img src="https://img.shields.io/badge/Server-475569?style=for-the-badge&logo=linuxserver&logoColor=white" />
<img src="https://img.shields.io/badge/Network_Diagnostics-334155?style=for-the-badge&logo=wireshark&logoColor=white" />
<img src="https://img.shields.io/badge/Cloudflare-F38020?style=for-the-badge&logo=cloudflare&logoColor=white" />

<br><br>

</div>

---

## 🚀 Featured Projects

### 🤖 Robot Factory Dispatch System

Industrial robot dispatch and fleet management system designed for factory environments. Supports multi-robot task assignment, job queues, robot availability, real-time status updates, and physical dispatch stations.

<br>

### 🔗 Robot OpenAPI Integration

Backend integration layer for connecting robot platforms with custom applications, including authentication, robot status, task creation, task cancellation, mission tracking, and telemetry.

<br>

### 📡 ESP32 Industrial Sensor & Dispatch System

ESP32-based interface for industrial photo sensors and physical dispatch controls. Sensor states are processed by the controller and transmitted to backend systems through MQTT for automation and robot task triggering.

<br>

### 🌐 Robot Network & Infrastructure

Network infrastructure and troubleshooting for robot systems, servers, and industrial devices, including static IP configuration, DHCP reservation, LAN deployment, VLAN, Wi-Fi access points, and network diagnostics.

<br>

### 📊 Robot Monitoring Dashboard

Real-time web dashboard for monitoring robot status, missions, locations, connected equipment, sensor states, and system events from a centralized interface.

<br>

---

## 🔧 What I Work On

<div align="center">
  
<pre>
🤖 Robot Integration       ⚡ Backend Development
🚚 Fleet Management        📡 MQTT / REST API
🌐 Network Infrastructure  🐧 Linux Server
🔌 Industrial Equipment    📟 ESP32 / Sensors
</pre>
</div>


---

### ⚙️ Robots. Software. Networks.

<br>

---

## 🛠️ Demos & Implementations

Below are some **demo projects, prototypes, and system implementations** I have developed and deployed in real-world environments, covering robotics, automation, IoT, and software systems.

</div>
