# gemini-vision-voice-agent

Gemini Vision-Voice Companion 🚀

Gemini Vision-Voice Companion is a high-speed, real-time multimodal AI agent built for the Gemini Live Agent Challenge 2026. Leveraging the power of Gemini 1.5 Flash, this project processes live video and audio streams to provide an interactive, hands-free user experience.

🌟 Key Features

Multimodal Intelligence: Seamlessly processes video frames and audio input for intelligent responses.

Low-Latency Performance: Optimized for sub-second reasoning with instant vocal feedback.

Cloud-Native Design: Fully containerized and deployable on Google Cloud Run.

User-Friendly Interface: Responsive web dashboard for live interactions.

🏗️ System Architecture

The architecture is designed for speed, scalability, and reliability:

Frontend: HTML5 & JavaScript using the MediaDevices API to capture live streams.

Backend: Python Flask server managing multimodal data pipelines.

AI Core: Gemini 1.5 Flash API for real-time visual and auditory reasoning.

Infrastructure: Dockerized and cloud-ready for seamless deployment on GCP.

🚀 Getting Started
1. Clone the Repository
git clone https://github.com/sachin9065109/gemini-vision-voice-agent.git
cd gemini-vision-voice-agent
2. Install Dependencies
pip install -r requirements.txt
3. Setup Environment

Obtain your Gemini API Key from Google AI Studio and set it:

export GEMINI_API_KEY='your_actual_api_key'
4. Run Locally
python app.py
🐳 Docker & Cloud Deployment

Build and run the container:

docker build -t gemini-agent .
docker run -p 8080:8080 -e GEMINI_API_KEY='your_key' gemini-agent
🛠️ Tech Stack

Model: Gemini 1.5 Flash

Backend: Python / Flask

Containerization: Docker

Cloud: Google Cloud Platform (GCP)

Developed by Sachin Bhagat for the Gemini Live Agent Challenge 2026.
