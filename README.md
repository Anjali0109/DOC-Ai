Doc AI
Overview
Doc AI is a healthcare web application that helps users check for potential diseases based on symptoms and test reports. It also features a mental health chatbot that provides emotional support and guidance. The platform includes lab test recommendations, a map of nearby labs, and AI-based disease prediction for diabetes, heart disease, and Parkinson’s.

Features
🏥 1. Disease Prediction
Users can check for diabetes, heart disease, and Parkinson's by inputting test report data.

Provides lab test recommendations based on symptoms.

🔍 2. Symptom-Based Diagnosis
Users can enter symptoms to get possible disease predictions.

Helps in early detection and awareness.

💬 3. Mental Health Chatbot
Allows users to share their feelings and get AI-generated supportive responses.

Recognizes keywords related to anxiety, depression, stress, sleep issues, and crisis situations.

Provides crisis hotline recommendations when necessary.

Interactive chatbot with a floating toggle button for easy access.

🏥 4. Find Doctors/Labs
Choose your doctor from thousands of specialists, general practitioners, and trusted hospitals.

Shows nearby Labs/Doctors with their location.

Technologies Used
Frontend: HTML, CSS, JavaScript

AI for Disease Prediction: Machine Learning Model

Mental Health Chatbot: JavaScript-based AI response system

Maps Integration: Google Maps API

Backend for Chatbot: Streamlit (Python)

Installation & Usage
📥 Clone the repository:
bash
Copy
Edit
git clone https://github.com/Anjali0109/DOC-Ai.git
cd DOC-Ai
🌐 Open the project:
Open index.html in a browser or run it on a local server.

🏃‍♂️ Start the chatbot backend using Streamlit:
bash
Copy
Edit
streamlit run health.py
💡 How to Use:
Enter disease parameters or symptoms to check possible conditions.

Use the mental health chatbot by clicking the floating "Want to talk?" button.

Mental Health Chatbot Details
Uses keyword-based AI responses to detect emotions and mental health concerns.

Provides reassuring messages based on user input.

Crisis-related messages trigger an alert with emergency contact information.

Future Enhancements
✅ Database Integration: Store user queries and responses for better analytics.
✅ Mobile App Version: Expand the platform to mobile applications.

Disclaimer
This project is an AI-based support system and not a substitute for professional medical advice. For emergencies, always contact a qualified healthcare professional or a crisis hotline.

Contributing
Contributions are welcome! Feel free to open an issue or submit a pull request.

License
This project is licensed under the MIT License.
