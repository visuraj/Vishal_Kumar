# Voice-Based Patient Call System  
An advanced healthcare communication solution employing voice technology, self-reliant AI agents, and real-time mobile platforms to optimize patient-nurse communication in medical environments.  

---

## Overview  
The **Voice-Based Patient Call System** aims to simplify interactions between patients and nurses. It leverages a voice-activated interface powered by **Azure OpenAI** to comprehend and handle patient needs, rank them using **Autonomous AI Agents**, and convey them to nurses through a real-time mobile application. This system greatly enhances response efficiency and improves patient care quality.  

---

## Key Outcomes  
- **Autonomous AI Agents**: Effortlessly manage and respond to patient needs.  
- **Speech Services Integration**: Facilitate communication with **Speech-to-Text** and **Text-to-Speech** capabilities.  
- **NLP-Powered Request Analysis**: Evaluate and rank patient requests using **Azure OpenAI** and **NLP techniques**.  
- **Voice-Driven Interface**: Intuitive, voice-first system for patient needs.  
- **Nurse Mobile Application**: Provides real-time notifications for nurses, including patient details and specific needs.  
- **Enhanced Patient Care**: Accelerates nurse response time and enriches patient experience.  

---

## Key Features  

### Multi-Role Authentication  
- **Patients**: Simple registration and user-friendly access to the system.  
- **Nurses**: Secure sign-up requiring admin validation for controlled access.  
- **Admins**: Holistic dashboard to oversee nurse operations, manage requests, and review analytics.  

### Voice and AI-Driven Functionality  
- **Natural Language Processing (NLP)** for evaluating patient demands.  
- **Speech Services** (**Speech-to-Text** and **Text-to-Speech**) for smooth voice-based engagement.  
- **Priority Assignment**: AI determines urgency for better request handling.  

### Real-Time Communication  
- Instant alerts and live progress tracking for nurses.  
- Consistent interaction using **Socket.IO**.  

### Comprehensive Dashboards  
- **Admin dashboard** displays approvals, nurse activities, and system performance.  
- **Nurse dashboard** facilitates monitoring and efficient handling of patient demands.  

---

## Technology Stack  

### Backend  
- **Node.js** with **Express.js**  
- **MongoDB** with **Mongoose**  
- **Socket.IO** for real-time functionalities  
- **JWT** for robust authentication  
- **TypeScript**  

### Frontend  
- **React Native** with **Expo**  
- **TypeScript**  
- **Socket.IO Client**  
- **React Navigation**  

### AI & NLP  
- **Azure OpenAI** for request evaluation via NLP.  
- **Microsoft Speech Services** for **Speech-to-Text** and **Text-to-Speech** processing.  

---

## Getting Started  

### Prerequisites  
- **Node.js** (version 14 or higher)  
- **MongoDB** (local instance or cloud setup)  
- **npm** or **yarn**  
- **Expo CLI**  
- **Android Studio** or **Xcode** for mobile simulation.


## Installation  

### 1. Clone the Repository  

cd Voice-Based-Patient-Call-System



### 2. Backend Setup

cd server  
npm install  




### Update the .env file with your configurations:

env
Copy code
MONGO_URI=your_mongodb_uri  
JWT_SECRET=your_jwt_secret  
PORT=5000

Start the backend server:


Copy code
npm start  

### 3. Frontend Setup
cd client  
npm install  

### Update the configuration: Edit src/config.ts with your backend URL.
Start the frontend application:

npm start

### Running the Application

Use the Expo Go app to scan the QR code from your terminal.
Alternatively, run the app on an emulator via Android Studio or Xcode.

### Default Admin Credentials

Email: admin
Password: admin



Contributing
Contributions are welcome! Follow these steps:

### Fork the repository:
Copy code
git fork https://github.com/visuraj/Vishal_Kumar.git

### Create a new branch:

Copy code
git checkout -b feature/AmazingFeature 

### Commit your changes:

Copy code
git commit -m 'Add some AmazingFeature'  

### Push to the branch:

Copy code
git push origin feature/AmazingFeature  
Open a pull request for review.


### License

This project is licensed under the MIT License. See the LICENSE file for details.

markdown
Copy code

### Instructions:
1. Copy the entire code above.
2. Paste it into your `README.md` file on GitHub.
3. Commit and push the changes to your repository.

This will create a properly structured and formatted `README.md` file with all the necessary

