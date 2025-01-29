Fitt: A Real-Time Virtual Gym Trainer and Posture Corrector


Overview
Fitt is a full-stack virtual gym trainer that leverages real-time pose landmark detection to analyze and correct exercise posture. By utilizing computer vision and a pre-trained model, Fitt provides immediate feedback, helping users refine their workout techniques.

Features
✅ Real-Time Posture Correction – Uses a computer vision model to detect and analyze user posture during exercises.
✅ Instant Feedback – Provides live feedback on workout form, helping users correct their movements dynamically.
✅ Personalized Training – Analyzes sample exercise videos to generate adaptive rules for guiding new users.
✅ Progress Tracking – Tracks user performance over time, offering insights to improve workout efficiency.
✅ Seamless UI/UX – Built with React and Tailwind CSS, ensuring a responsive and visually appealing interface.

Tech Stack
Frontend: React, Tailwind CSS
Backend: Flask (Python)
Computer Vision: Mediapipe, OpenCV
Deployment: Vercel (Frontend), Flask Server
Installation & Setup
Prerequisites
Ensure you have the following installed:

Node.js (for frontend)
Python 3 (for backend)
Docker (Optional, for containerized setup)
Backend Setup (Flask Server)
sh
Copy
git clone https://github.com/sudhanvarajesh/fitt/tree/main
cd Fitt/backend
pip install -r requirements.txt
python app.py
The Flask server will start running on http://127.0.0.1:5000/.

Frontend Setup (React App)
sh
Copy
cd ../frontend
npm install
npm run dev
The frontend will start running on http://localhost:3000/.

Usage
Open the app in your browser.
Grant webcam access for real-time posture tracking.
Perform exercises while the model provides instant feedback.
Track improvements and refine workout form.


Contributing
Contributions are welcome! If you’d like to improve Fitt, feel free to:

Fork the repository
Create a new branch (feature/your-feature)
Commit your changes
Open a pull request

