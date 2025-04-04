Doc AI

Overview

Doc AI is a healthcare web application that helps users check for potential diseases based on symptoms and test reports. It also features a mental health chatbot that provides emotional support and guidance. The platform includes lab test recommendations, a map of nearby labs, and AI-based disease prediction for diabetes, heart disease, and Parkinson’s.

Features

1. Disease Prediction

Users can check for diabetes, heart disease, and Parkinson's by inputting test report data.

Provides lab test recommendations based on symptoms.

2. Symptom-Based Diagnosis

Users can enter symptoms to get possible disease predictions.

Helps in early detection and awareness.

3. Mental Health Chatbot

Allows users to share their feelings and get AI-generated supportive responses.

Recognizes keywords related to anxiety, depression, stress, sleep issues, and crisis situations.

Provides crisis hotline recommendations when necessary.

Interactive chatbot with a floating toggle button for easy access.

4. Find Docs/Labs

Choose your doctor from thousands of specialist,general and trusted hospitals.

It will show nearby Labs/Docs with their location.

Technologies Used

Frontend: HTML, CSS, JavaScript

AI for Disease Prediction: Machine Learning Model

Mental Health Chatbot: JavaScript-based AI response system

Maps Integration: Google Maps API

Backend for Chatbot: Streamlit (Python)

Installation & Usage

Clone the repository:

git clone https://github.com/Anjali0109/DOC-Ai.git

Open the project folder and run it on a local server or directly open index.html in a browser.

Start the mental health chatbot backend using Streamlit:

streamlit run health.py

Enter disease parameters or symptoms to check possible conditions.

Use the mental health chatbot by clicking the floating "Want to talk?" button.

Mental Health Chatbot Details

The chatbot uses predefined keyword-based responses to detect emotions and mental health concerns.

It responds with reassuring messages and provides support based on user inputs.

Crisis-related messages trigger an alert with emergency contact information.

Future Enhancements

Database Integration: Storing user queries and responses for better analytics.

Mobile App Version: Expanding the platform to mobile applications.

Disclaimer

This project is an AI-based support system and not a substitute for professional medical advice. For emergencies, always contact a qualified healthcare professional or a crisis hotline.

Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request.

License

This project is licensed under the MIT License.