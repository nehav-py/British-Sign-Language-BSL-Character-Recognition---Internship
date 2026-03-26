# BRITISH SIGN LANGUAGE (BSL) CHARACTER RECOGNITION

🌐 LIVE DEMO

👉 https://british-sign-language-bsl-character.onrender.com


📌OVERVIEW

British Sign Language Character Recognition is a real-time gesture recognition system that translates BSL hand signs into readable text using computer vision and machine learning.
The system enables seamless human-computer interaction by recognizing hand gestures captured from a webcam. Using MediaPipe for landmark detection and a Random Forest classifier for prediction, it interprets single-hand BSL alphabets accurately and efficiently.
Designed with accessibility in mind, this project aims to support communication for the hearing and speech-impaired community, providing a foundation for assistive technologies that make sign language recognition both interactive and intuitive.


•	The application captures live video frames from the webcam.

•	MediaPipe detects and extracts key hand landmarks.

•	These features are then processed by a trained Random Forest model, which classifies the hand shape into a specific BSL alphabet.

•	The prediction is displayed instantly on the frontend, allowing users to visualize recognition results in real time.

Built using Python, OpenCV, and scikit-learn, with a lightweight web interface, the project demonstrates how deep learning-inspired models can drive inclusive, real-time communication systems.

TECH STACK:

• Python -	Core language for backend and model logic

• OpenCV -	Video capture and frame processing

• MediaPipe - 	Hand landmark detection 

• Flask - 	Lightweight backend server 

• scikit-learn - Random Forest classifier for prediction

• HTML, CSS, JavaScript - Interactive frontend demo

KEY FEATURES:

🎥 Real-Time Recognition — Detects and predicts signs directly from webcam input.

🖐️ Single-Hand BSL Alphabets — Focused on accurate character-level recognition.

⚡ Fast & Lightweight — Optimized for low-latency inference.

💻 Interactive Web Demo — Intuitive and easy to use interface.

🔧 Modular Design — Ready for new gestures, datasets, or features.


DEMO PREVIEW:

 📸 A live camera preview for gesture detection.

 🎛️ Buttons to start, capture, and predict signs.
 
 🔤 A BSL alphabet reference chart.
 
 ⚙️ Real-time display of the predicted character.
