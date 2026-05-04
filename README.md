# 🕉️ H.A.N.U.M.A.N. 
### **Home Automation Network Utilizing Modern Artificial Neural-intelligence**

**H.A.N.U.M.A.N.** is a sophisticated, agentic home assistant designed to create a "Rajya" (Kingdom) of order and efficiency. Unlike standard assistants, it is built with a warrior's spirit—integrating high-level Linux system administration, real-time sensor data, and state-of-the-art Large Language Models (LLMs) into a single, unified consciousness.

---

## 🧠 Maha-Mastishka (The Brain)
The system is powered by a **Raspberry Pi Zero 2 W**, acting as the central nervous system. It manages all logic and hardware-software synergy without the need for secondary microcontrollers.

*   **OS:** Custom-configured Linux environment.
*   **Intelligence:** Driven by **Llama 3.3 (70B)** via Groq for wise, near-instant reasoning.
*   **Deployment:** Hybrid architecture using a **Flask** backend optimized for Vercel.

---

## 🛠️ The Siddhis (The Features)

| Feature | Concept | Technical Implementation |
| :--- | :--- | :--- |
| **Aagya** | **Chat Mode** | Direct interaction with LLM for problem-solving and advice. |
| **Khoj** | **Search Mode** | Real-time web-crawling to retrieve live information. |
| **Hasya** | **Laughter Center** | Humorous personality mode for jokes and storytelling. |
| **Rajya Vyavastha** | **Home Management** | Control of fans/lights and real-time DHT11 climate monitoring. |
| **Vayu-Gyan** | **Atmosphere** | Sensing room temperature and humidity via DHT11. |

---

## 👁️ Divya Chakshu (The Divine Eye & Ear)
The assistant utilizes a "Divine Eye" (Webcam) and "Ear" (Microphone) for dual-mode activation:
1.  **Vision-Based:** Automatically activates the system upon detecting human presence (Sentinel Mode).
2.  **Voice-Based:** Listens for "Jai Shri Ram" or "Hanuman" using a dual STT pipeline (**Whisper-Large-V3**).

---

## 💻 Tech Stack

### **Hardware**
*   **Single-Board Computer:** Raspberry Pi Zero 2 W
*   **Sensors:** DHT11 (Temperature/Humidity), USB Webcam
*   **Output:** PAM8403 Amplifier with high-fidelity speakers
*   **Actuators:** Servos and Relays for home appliance control

### **Software**
![Linux](https://img.shields.io/badge/-Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Python](https://img.shields.io/badge/-Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/-Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![Groq](https://img.shields.io/badge/-Groq-f55036?style=for-the-badge)
![ElevenLabs](https://img.shields.io/badge/-ElevenLabs-black?style=for-the-badge)
![Bash](https://img.shields.io/badge/-Bash-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white)

---

## 🚀 Setup & Installation

### Backend (Cloud)
1.  Clone the repository.
2.  Install dependencies:
    ```bash
    pip install -r req.txt
    ```
3.  Configure `.env` with your API keys:
    ```env
    GROQ_API_KEY=your_key_here
    ELEVENLABS_API_KEY=your_key_here
    ```
4.  Deploy to Vercel (includes auto-installer for static FFmpeg binaries).

### Frontend (Hardware)
1.  Connect the webcam and DHT11 to the Raspberry Pi GPIO.
2.  Ensure `ffmpeg` and `alsa-utils` are installed on the Pi.
3.  Run the client-side script to capture audio/video.
4.  The system captures audio locally, POSTs to the cloud backend, and streams back the high-fidelity response.

---

## 📍 Origin
**Developed in Kolkata, India.**
*Focused on creating hardware-software synergy to solve technical challenges.*
