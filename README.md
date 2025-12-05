# RescuNet

<div align="center" style="padding: 0; margin: 0; top: 0;">
  <img src="rescunet.png" alt="RescuNet Text" width="300" />
  <p><b>Next-Gen Disaster Response Intelligence</b></p>
  <p>
    <a href="#key-features">Key Features</a> •
    <a href="#tech-stack">Tech Stack</a> •
    <a href="#installation">Installation</a> •
    <a href="#usage">Usage</a> •
    <a href="#license">License</a>
  </p>
</div>

---

RescuNet is a comprehensive platform designed to revolutionize emergency response operations. By integrating AI-powered aerial surveillance, advanced graph-based routing, and real-time text analysis, RescuNet empowers responders to locate survivors, identify hazards, and navigate complex disaster zones with unprecedented efficiency.

# RescuNet_Computer_Vison

### 🚁 Aerial Intelligence
- **Real-Time Detection**: Utilizes **YOLOv11** to detect survivors, fire, and smoke hazards instantly from drone video feeds.
- **Dual-Mode Surveillance**: Supports both **Thermal** (Person Detection) and **RGB** (Fire & Smoke Detection) modes.
  - **Fire**: Detected with **Red** bounding boxes.
  - **Smoke**: Detected with **Gray** bounding boxes.
- **Low-Latency Streaming**: WebSocket-based architecture ensures real-time video transmission and processing.
