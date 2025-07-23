# -ThalCare-AI

Overview

ThalCare AI is an AI-powered blood donation and care network designed to support Thalassemia patients. It uses a Predictive Donor Availability Score (PDAS) to match patients with the most likely available donors in real-time while providing telemedicine support, donor gamification, and genetic counseling.

Key Features

✅ Real-Time Donor-Patient Matching (via e-RaktKosh & Blood Bridge APIs)

✅ AI-Powered Donor Prediction using TensorFlow & PyTorch

✅ Gamified Donor Engagement (leaderboards, impact dashboard)

✅ Telemedicine & AI Chatbots for patient education

✅ Secure & Compliant (AES-256 encryption, OAuth2.0, JWT, DPDPA 2023)

Technology Stack

Languages & Frameworks

Python, JavaScript, Dart (Flutter)

TensorFlow, PyTorch, scikit-learn (AI/ML)

Flask (Python), Express.js (Node.js) (Backend)

Flutter (Cross-platform mobile app)

Cloud & Databases

AWS, NIC Cloud

PostgreSQL, MongoDB

APIs & Services

e-RaktKosh & Blood Warriors’ Blood Bridge

Google Maps API (location-based donor matching)

Twilio / WhatsApp Business API (donor notifications)

WebRTC (telemedicine)

Project Structure

ThalCare-AI/
│
├── ai-model/               # PDAS model (TensorFlow / PyTorch)
│   ├── data/               # Training data or synthetic data
│   ├── pdas_model.py       # Core predictive model
│   └── model_notebook.ipynb # Google Colab-ready notebook
│
├── backend/
│   ├── app.py              # Flask API for AI model
│   ├── routes/             # Express.js routes
│   └── requirements.txt    # Dependencies
│
├── frontend/
│   ├── lib/                # Flutter app source code
│   ├── assets/             # Images, icons, etc.
│   └── pubspec.yaml        # Flutter dependencies
│
├── docs/
│   └── pitch-deck.pdf      # Project pitch deck & documentation
│
└── README.md               # This file

Installation & Usage

1. Clone the Repository

git clone https://github.com/AdityaKude/ThalCare-AI.git
cd ThalCare-AI

2. Backend Setup

cd backend
pip install -r requirements.txt
python app.py

3. Frontend Setup

cd frontend
flutter pub get
flutter run

4. AI Model (Optional)
Open ai-model/model_notebook.ipynb in Google Colab to retrain the PDAS model.

Try It Out

🔗 Live App (Prototype): Coming Soon
🔗 AI Model Notebook: Google Colab
🔗 Pitch Deck: Download here

Contributing:
 We welcome contributions! Feel free to submit PRs for:
  Improving PDAS model accuracy
  Enhancing Flutter UI/UX
  Adding new donor engagement features

License
 MIT License – Open for non-commercial use to help Thalassemia patients.

Contact
  Team Blood Warriors
  📧 Email: contact@thalcareai.org
  🌐 Website: Coming Soon
