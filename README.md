# gemini-vision-voice-agent

🚀 Gemini Vision-Voice Companion

Gemini Vision-Voice Companion is a high-speed, real-time multimodal AI agent built for the Gemini Live Agent Challenge 2026. Using Gemini 1.5 Flash, it processes live video and audio to provide an interactive, hands-free user experience.

🌟 Key Features

🎥 Multimodal Intelligence: Seamlessly integrates video frames and audio input.

⚡ Low-Latency Performance: Sub-second reasoning with instant vocal feedback.

☁️ Cloud-Native Design: Fully containerized and deployable on Google Cloud Run.

🖥️ User-Centric Interface: Responsive web dashboard for live interaction.

🏗️ System Architecture

Frontend: HTML5 & JavaScript (MediaDevices API) captures live streams.

Backend: Python Flask server for multimodal data handling.

AI Core: Gemini 1.5 Flash API for real-time visual & auditory reasoning.

Infrastructure: Dockerized, cloud-ready for scalable deployment on GCP.

🚀 Getting Started
1️⃣ Clone the Repository
git clone https://github.com/sachin9065109/gemini-vision-voice-agent.git
cd gemini-vision-voice-agent
2️⃣ Install Dependencies
pip install -r requirements.txt
3️⃣ Setup Environment

Get your Gemini API Key from Google AI Studio:

export GEMINI_API_KEY='your_actual_api_key'
4️⃣ Run Locally
python app.py
🐳 Docker & Cloud Deployment
docker build -t gemini-agent .
docker run -p 8080:8080 -e GEMINI_API_KEY='your_key' gemini-agent

Fully cloud-ready, works on Google Cloud Run with zero hassle.

🛠️ Tech Stack

Model: Gemini 1.5 Flash

Backend: Python / Flask

Containerization: Docker

Cloud: Google Cloud Platform (GCP)




eveloped by Sachin Bhagat for the Gemini Live Agent Challenge 2026.


![Screenshot_19-3-2026_114347_gemini google com](https://github.com/user-attachments/assets/d65e91f2-d096-4cff-99cb-b55bdb35fe02)

