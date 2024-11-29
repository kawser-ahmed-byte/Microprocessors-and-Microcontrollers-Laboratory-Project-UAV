# TritonZ: A Remotely Operated Underwater Rover  
## Designed for Exploration and Rescue Operations  

Welcome to the repository for **TritonZ**, our **Remotely Operated Underwater Rover (ROV)** with a manipulator arm for versatile underwater exploration and rescue tasks. This project was developed as part of our **Microprocessors & Microcontrollers Laboratory Course** under the supervision of **Fahim Hafiz** and presented at **ICCIT 2024**.  

---

<p align="center">
  <img src="assets/rov_overview.jpg" alt="TritonZ ROV" width="600">
</p>

---

## 🌟 Key Features  
1. **Project Proposal**: Explore the objectives and goals driving TritonZ.  
2. **Codebase**: Access the detailed source code for microcontrollers and processors powering the ROV.  
3. **Implementation**: Learn about hardware integration, software design, and testing.  
4. **Manipulator Arm**: See how we built and implemented a functional arm for rescue tasks.  
5. **Reports**: Detailed documentation on design challenges, solutions, and lessons learned.  

---

## 📹 Demo Video & Project Gallery  
🎥 **Watch TritonZ in Action!**  
[![TritonZ Demo Video](https://img.youtube.com/vi/your_video_id_here/0.jpg)](https://youtu.be/your_video_id_here)  

### 📸 Project Images  
- ROV Design Overview  
- Manipulator Arm in Action  
- Underwater Testing Footage  

<p align="center">
  <img src="assets/testing.jpg" alt="ROV Testing" width="300">
  <img src="assets/arm.jpg" alt="Manipulator Arm" width="300">
  <img src="assets/submerged.jpg" alt="ROV Submerged" width="300">
</p>

---

## 🛠️ System Architecture  

### **Hardware Overview**  
The TritonZ integrates robust components for efficient underwater operations:  
- **Main Controller**: Raspberry Pi 3 B+  
- **Camera**: Pi Cam for live video feed  
- **Manipulator Arm**: Controlled by servo and stepper motors  
- **Motors**:  
  - 4x BLDC Motors for thrust  
  - 2x BLDC Motors for directional control  
- **Other Components**:  
  - ESP-32 and ESP-8266 for wireless communication  
  - PVC Frame and Epoxy for a waterproof design  

### **Software Architecture**  
Our multi-tier software includes:  
- **Sensor Feedback**: Real-time data from Pi Cam and onboard sensors.  
- **Motor Control**: Thrust and directional motors controlled via Raspberry Pi and Arduino Mega.  
- **Manipulator Arm**: Integrated logic for object handling and rescue operations.  

<p align="center">
  <img src="assets/architecture_diagram.png" alt="System Architecture" width="600">
</p>

---

## 📖 How to Run  

### **Clone the Repository**  
```bash
git clone https://github.com/kawser-ahmed-byte/Microprocessors-and-Microcontrollers-Laboratory-Project-UAV.git
cd Microprocessors-and-Microcontrollers-Laboratory-Project-UAV

### **Install Dependencies**
 1. Install necessary Python libraries for Raspberry Pi:
    pip install -r requirements.txt
 2. Upload the Arduino .ino files using the Arduino IDE.

### ***Run the System**
 1. Connect the hardware: Ensure motors, sensors, and arm components are wired correctly.
 2. Launch the Python script to initiate the control system:
    python main.py


## 🧩 Technologies Used

| **Component**     | **Description**                           |
|--------------------|-------------------------------------------|
| **Raspberry Pi**   | Main controller for video streaming & logic. |
| **Arduino Mega**   | Handles motor and manipulator arm logic. |
| **ESP-32/8266**    | Wireless communication.                  |
| **BLDC Motors**    | Thrust for underwater navigation.        |
| **Pi Cam**         | Captures live video for monitoring.      |
| **Servo Motors**   | Controls the manipulator arm.            |

---

## 🤝 Contributors

This project was collaboratively developed by students of **United International University (UIU), Bangladesh**:  
- **Kawser Ahmed**  
- **[Team Member 1 Name]**  
- **[Team Member 2 Name]**  
- **[Team Member 3 Name]**

---

## 📚 Acknowledgments

We extend our gratitude to **Fahim Hafiz** for his guidance and support and to **UIU** for enabling us to explore innovative applications in underwater robotics.

---

## 📬 Contact

Have questions or feedback? Reach us at **[kawserahmd2001@gmail.com]** or open an issue in this repository.
