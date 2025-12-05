# RescuNet

<div align="center" style="padding: 0; margin: 0; top: 0;">
  <img src="rescunet.png" alt="RescuNet Text" width="300" />
  <p><b>Next-Gen Disaster Response Intelligence</b></p>
</div>

---

RescuNet is a comprehensive platform designed to revolutionize emergency response operations. By integrating AI-powered aerial surveillance, advanced graph-based routing, and real-time text analysis, RescuNet empowers responders to locate survivors, identify hazards, and navigate complex disaster zones with unprecedented efficiency.

# RescuNet Computer Vison

### 🚁 Aerial Intelligence
- **Real-Time Detection**: Utilizes **YOLOv11** to detect survivors, fire, and smoke hazards instantly from drone video feeds.
- **Dual-Mode Surveillance**: Supports both **Thermal** (Person Detection) and **RGB** (Fire, people, Smoke, and cars Detection) modes.
  - **RGB**
    - **Smoke, fire**: **YOLOV11m** model is used to detect this featsures as they are comples.
    - **Cars, People**: two **YOLOV11s** model is used to detect this featsures to make the RGB model light and have low latency.
  - **Thermal**: **YOLOV11s** model is used to detect this featsures to make the RGB model light and have low latency.
  - 
