Kritrim: AI-Driven Multilingual Humanoid Robot 🤖🇮🇳

Student Innovation: Swadeshi for Atmanirbhar Bharat - Robotics and Drones > Problem Statement ID: 25117 

📖 Overview

Kritrim is an affordable, emotion-aware humanoid robot designed to empower MSMEs (Micro, Small, and Medium Enterprises) and public service desks. Unlike existing global solutions that cost between ₹20-60 Lakh, Kritrim provides an indigenous, modular alternative costing significantly less (approx. ₹5-7 Lakh).




It is designed to automate repetitive tasks—such as answering FAQs, providing directions, and greeting visitors—while bridging language barriers through advanced multilingual NLP.

🎯 Key Features

Multilingual Support: Communicates fluently in English, Hindi, and regional languages to assist diverse demographics.


Emotion AI: Detects user tone, pitch, and facial expressions to provide empathetic and consistent service.


AI Vision: Capable of detecting customers and analyzing surroundings for better interaction.



Cost-Effective Hardware: Built using Raspberry Pi and Arduino, making it accessible for small businesses.



Offline Capability: Designed to function effectively even without consistent internet connectivity.

👨‍💻 My Contribution: Real-Time Voice Intelligence
Role: Voice AI & Interaction Developer

I was responsible for the core conversational capabilities of Kritrim. My primary contribution focused on creating a seamless, low-latency verbal interaction system.


LiveKit Integration: Built a real-time voice assistant module using LiveKit to handle streaming audio data efficiently.

Natural Conversation Flow: Engineered the interaction loop to support natural, interruption-handling conversations rather than rigid command-response loops.

Student Support Optimization: While the robot serves MSMEs, I specifically tuned the voice model to resolve complex university student queries efficiently, acting as an automated receptionist for campus settings.


Multilingual Pipeline: Integrated Speech-to-Text (STT) and NLP models to ensure accurate query resolution across different languages.


🛠️ Tech Stack
Hardware

Core Compute: Raspberry Pi 


Control: Arduino, Servo Motors 


Sensors: Cameras (Vision), Microphones 

Software & AI

Languages: Python, C++ 


Robotics Framework: ROS (Robot Operating System) 


Computer Vision: OpenCV, TensorFlow Lite 


NLP & Voice: HuggingFace, Vosk/Google Speech-to-Text 


Real-Time Comms: LiveKit 


Cloud: AWS / Firebase 

⚙️ Architecture
The system operates on a feedback loop comprising four main stages:


Perception: Cameras and Microphones capture user input (Vision & Audio).


Processing:

Visual data is processed via OpenCV/TF Lite for object/face detection.

Audio is streamed via LiveKit to the NLP engine for intent recognition.


Decision: The Emotion AI and NLP models determine the appropriate response and physical gesture.


Action: The Robotics Control System actuates servo motors for gestures and plays back audio responses.

🚀 Impact & Viability

Economic: 70-80% cheaper than global humanoid competitors.


Scalability: Suitable for deployment in retail, hospitality, healthcare, and education sectors.


Efficiency: Frees up human staff from repetitive inquiries, allowing them to focus on complex tasks.

🔮 Future Scope
Expansion into healthcare for patient assistance.

Enhanced autonomous navigation in complex environments.

RaaS (Robot as a Service) business model implementation.

Team Ourobonics | SIH 2025 Grand Finalists
