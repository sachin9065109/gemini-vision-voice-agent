# gemini-vision-voice-agent

Markdown
# Gemini Vision-Voice Companion 🚀

A high-speed, real-time multimodal AI agent built for the **Gemini Live Agent Challenge 2026**. This project demonstrates the power of **Gemini 1.5 Flash** in processing live visual and auditory data to provide an interactive, hands-free user experience.

## 🌟 Key Features
- **Multimodal Intelligence:** Seamlessly integrates video frames and audio input using Gemini 1.5 Flash.
- **Low-Latency Performance:** Optimized for sub-second reasoning and vocal feedback.
- **Cloud-Native Design:** Fully containerized with Docker and architected for **Google Cloud Run**.
- **User-Centric Interface:** A responsive web dashboard for real-time interaction.

## 🏗️ System Architecture
The application follows a streamlined cloud-native workflow to ensure scalability and speed:

1. **Frontend:** HTML5 and JavaScript (MediaDevices API) capture live streams.
2. **Backend:** A Python Flask server acts as the gateway for multimodal payloads.
3. **AI Core:** Gemini 1.5 Flash API performs real-time visual and auditory reasoning.
4. **Infrastructure:** Hosted in a Docker container, ready for deployment on Google Cloud.



## 🚀 Reproduction Instructions

### 1. Clone the Repository
```bash
git clone [https://github.com/sachin9065109/gemini-vision-voice-agent.git](https://github.com/sachin9065109/gemini-vision-voice-agent.git)
cd gemini-vision-voice-agent
2. Install Dependencies
Bash
pip install -r requirements.txt
3. Setup Environment
Obtain your Gemini API Key from Google AI Studio and set it:

Bash
export GEMINI_API_KEY='your_actual_api_key'
4. Run Locally
Bash
python app.py
🐳 Docker & Cloud Deployment
To ensure the project is "Cloud-Ready," use the provided Dockerfile:

Bash
docker build -t gemini-agent .
docker run -p 8080:8080 -e GEMINI_API_KEY='your_key' gemini-agent
🛠️ Tech Stack
Model: Gemini 1.5 Flash

Backend: Python / Flask

Containerization: Docker

Cloud: Google Cloud Platform (GCP)

Developed by Sachin bhagat for the Gemini Live Agent Challenge.
