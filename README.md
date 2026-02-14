# Design and Implementation of a Smart Plug
## A Secure IoT Solution for Remote Control

### Project Overview
This project represents an integrated **End-to-End IoT solution** designed for the secure, remote management of household electrical loads. Developed with a focus on **sustainability and safety**, the system enables users to monitor and control power outlets through a secure web interface, bridging the gap between hardware precision and cloud scalability.

---

### Key Technical Features
* **Hardware Architecture:** Powered by the **ESP32 microcontroller**, featuring **galvanic isolation** via PC817 optocouplers to ensure user and component safety.
* **Cloud Infrastructure:** Real-time bidirectional communication powered by the **MQTT protocol** and hosted on **Vercel** for global accessibility.
* **Security Layer:** Implements **SHA-256 hashing** for secure user authentication and HTTPS encryption for all web traffic.
* **Smart Connectivity:** Integrated **WiFiManager** for intuitive, standalone network configuration via a captive portal.
* **Sustainable Design:** Housed in a custom **3D-printed enclosure** engineered for optimal thermal management and electrical insulation.

---

### Core Technologies
* **Languages:** C++ (Arduino IDE), JavaScript, HTML5, CSS3.
* **Protocols:** MQTT, WebSockets, HTTP/HTTPS.
* **Tools:** GitHub (CI/CD), Vercel, HiveMQ Broker.

---

### How to Use
1. **Network Setup:** Connect to the "Configurare_Priza_Smart" AP to set up local Wi-Fi.
2. **Authentication:** Access the Vercel deployment link and enter the secure access code.
3. **Control:** Monitor and toggle power states in real-time from any device.
