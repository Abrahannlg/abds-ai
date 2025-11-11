# abds-ai
Intelligent YOLO-based bidirectional object detection system with configurable camera zones and automatic action response.



# 🧠 Autonomous Bidirectional Detection System (ABDS)

### Intelligent YOLO-based system for dual-direction object detection and automation.

---

## 📖 Overview

The **Autonomous Bidirectional Detection System (ABDS)** is a software-based platform designed to perform **object detection and directional analysis** using YOLO models.  
It enables multi-camera integration, allowing each camera to define **two configurable zones of interest**.  
By analyzing the order in which an object is detected across these zones, ABDS determines its **direction of movement** and can execute predefined **automated actions** accordingly.

This approach provides a flexible, camera-based detection solution without requiring additional hardware for movement tracking.

---

## 🚀 Features

- 🔹 YOLO-based object detection with real-time inference.  
- 🔹 Multi-camera connectivity and configuration.  
- 🔹 Dual-zone logic to determine object direction.  
- 🔹 Software-defined zones for easy calibration.  
- 🔹 Modular and scalable architecture.  
- 🔹 Future-ready for integration with other languages or AI frameworks.

---

## 🧩 System Architecture

- **Cameras:** Capture real-time frames from one or more sources.  
- **ABDS Core:** Handles detection, zone logic, and communication between components.  
- **YOLO Model:** Performs object recognition and bounding box prediction.  
- **Zone Analysis:** Identifies which defined zone was triggered first.  
- **Action Logic:** Executes configured responses based on direction.

---

## ⚙️ Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/autonomous-bidirectional-detection-system.git
   cd autonomous-bidirectional-detection-system

   python -m venv .venv
    source .venv/bin/activate   # On Linux/Mac
    .venv\Scripts\activate      # On Windows

    pip install -r requirements.txt
