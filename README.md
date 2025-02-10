# TheraSpeak

## PennApps XXIV: Best AI Hack | September 2023
### Tech Stack: Python, HTML5, CSS, JavaScript, React, Twilio API, OpenAI API
## Contributors
Rishabh (Rishi) Prabhu, Jesse Choe, Abhisheik Sharma, Siddhant Sood 

## Overview
TheraSpeak is an AI-powered web application designed to enhance mental health support by assisting both individuals in crisis and suicide hotline responders. Using reinforcement learning, the system provides real-time AI-driven suggestions for hotline workers while also offering automated counseling via SMS and voice calls. 

## Features
- **AI-Assisted Hotline Support:** Provides real-time AI-driven suggestions to hotline workers to improve their conversations with callers.
- **Live Transcription & AI Suggestions:** Uses OpenAI’s API to transcribe calls and generate response recommendations.
- **Automated SMS Counseling:** Offers fast, AI-based mental health support via SMS, ensuring immediate assistance when human responders are unavailable.
- **Anonymity & Privacy:** Maintains the anonymity of both the caller and the hotline worker, ensuring a secure communication environment.

## How It Works
TheraSpeak is divided into two core functionalities:

1. **For Individuals Seeking Support:**
   - Users can call or text a Twilio-hosted phone number.
   - AI-based counseling is available via SMS and call support, offering immediate assistance.
   - Calls are connected to human responders when available.

2. **For Hotline Workers:**
   - Provides real-time AI-generated response suggestions based on live transcription of calls.
   - Responders can choose AI suggestions and send messages directly while maintaining anonymity.
   - Reinforcement learning allows responders to provide feedback on AI suggestions to improve future recommendations.

## Development & Architecture
### **Frontend (TheraSpeak Website)**
- Developed a multi-page website including a home page, about page, and login system.
- Implemented a portal where hotline workers can access either the text-based chat system or the call transcription playground.
- Designed with Tailwind CSS for an intuitive and modern UI.
- Integrated with backend services using JavaScript fetch requests.

### **Backend (Text & Call Functionality)**
- **Text-Based Support:**
  - Twilio API facilitates SMS-based mental health assistance.
  - AI-generated responses from OpenAI API are prompt-engineered to provide empathetic and concise advice.
  - Integration with the TheraSpeak portal allows for human intervention when needed.
- **Call-Based Support:**
  - Calls are transcribed in real-time using AI.
  - AI-generated suggestions appear on the TheraSpeak web portal for hotline workers to incorporate into conversations.
  - Reinforcement learning improves AI recommendations over time based on responder feedback.

## Tech Stack
- **Backend:** Python, OpenAI API, Twilio API
- **Frontend:** JavaScript, React, HTML5, Tailwind CSS
- **Mobile App:** React Native

## Future Improvements
- Expanding reinforcement learning to refine AI suggestions further.
- Enhancing multi-language support for global accessibility.
- Improving AI-driven sentiment analysis for more accurate recommendations.



---
**TheraSpeak: Empowering hotline responders with AI-driven insights to improve mental health support.**
