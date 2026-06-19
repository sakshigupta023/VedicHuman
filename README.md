VEDICHUman : Yog At Ease

VedicHuman is an AI-powered yoga training platform that helps users perform yoga poses correctly through real-time pose detection and feedback. The system uses computer vision and machine learning techniques to analyze body posture through a webcam and provide guidance for improving yoga practice.

The project aims to make yoga training accessible, interactive, and personalized by combining traditional wellness practices with modern AI technology.


✨ Features
🎥 Real-time pose detection using webcam
🤖 AI-based posture analysis
📊 Performance tracking and progress monitoring
🔊 Voice and text feedback
📈 Accuracy scoring for yoga poses
👤 User authentication and profile management
📚 Multiple yoga pose support
📱 Responsive and user-friendly interface


🛠️ Tech Stack
Frontend
HTML5
CSS3
JavaScript
Backend
Python
Flask
AI/ML
TensorFlow
MoveNet Pose Estimation
OpenCV
Database
SQLite / MySQL
Tools
VS Code
Git & GitHub



🏗️ System Architecture
User
  │
  ▼
Web Interface
  │
  ▼
Flask Backend
  │
  ├── User Authentication
  ├── Progress Tracking
  └── Pose Evaluation
  │
  ▼
OpenCV + MoveNet
  │
  ▼
Pose Detection
  │
  ▼
Feedback & Accuracy Score
📂 Project Structure
VedicHuman/
│
├── static/
│   ├── css/
│   ├── js/
│   └── images/
│
├── templates/
│   ├── index.html
│   ├── login.html
│   ├── dashboard.html
│   └── yoga.html
│
├── models/
│   └── movenet_model/
│
├── database/
│   └── users.db
│
├── app.py
├── requirements.txt
├── README.md
└── .gitignore


⚙️ Installation
1. Clone Repository
git clone https://github.com/your-username/VedicHuman.git
cd VedicHuman
2. Create Virtual Environment
python -m venv venv
3. Activate Environment
Windows
venv\Scripts\activate
Linux/Mac
source venv/bin/activate
4. Install Dependencies
pip install -r requirements.txt
5. Run Application
python app.py

Open browser:
http://localhost:5000


📋 Requirements
Python 3.10+
Flask
OpenCV
TensorFlow
NumPy
SQLite/MySQL

Install manually:
pip install flask opencv-python tensorflow numpy


🎯 Future Enhancements
Personalized workout recommendations
AI-generated yoga plans
Mobile application
Multi-language support
Advanced posture correction
Wearable device integration
Community challenges and leaderboards


📊 Use Cases
Home yoga training
Fitness monitoring
Beginner yoga guidance
Rehabilitation exercises
Wellness and mindfulness programs
