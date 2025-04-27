MindWell
MindWell is a mental wellness web application that helps users improve their mental health through meditation, mindfulness exercises, emotional support, and self-assessment tools. The platform provides personalized features for users to track and manage their mental health journey.

Features
Meditation: Access guided meditation sessions to improve mental clarity and focus.

Mental Health Assessment: Complete self-assessments like PHQ-9 to evaluate depression severity.

Mindfulness: Learn mindfulness techniques for stress relief and emotional balance.

User Authentication: Secure login and registration system with options to log out.

Tech Stack
Frontend:

React.js
Tailwind CSS
Framer Motion (for animations)
Redux (for state management)
React Router (for routing)
React Icons (for icons)
Backend:

Node.js
Express
MongoDB (for storing user data and assessments
Third-Party Libraries:

React Wrap Balancer (for text balancing)
React Toastify (for toast notifications)
Axios (for API requests)
Installation
Prerequisites

Make sure you have the following installed:

Node.js (version 14 or above)
MongoDB or a MongoDB cluster URI
Postman (or any API testing tool)
Steps

Clone the repository:

git clone https://github.com/Mulanisafa/mental-wellness-app.git
Backend Setup (Node.js/Express):

Navigate to the backend folder:
cd server
Install the dependencies:
npm Install
Create a .env file in the root of the project and add the following variables:
PORT=3000
MONGO_URI=your_mongo_connection_uri
JWT_SECRET

Start the server:

npm run server

Frontend Setup (React.js):

Navigate to the frontend folder:
cd client
Install the dependencies:
npm Install
Start the React Dev server:

npm run dev

Usage
User Authentication: Sign up or log in to track your mental wellness.

Mood Tracking: Log your mood on a scale, track trends, and see visualizations.

PHQ-9 Assessment: Take the PHQ-9 test to evaluate your depression severity.

Meditation: Explore guided meditations for stress relief and mindfulness.

Exercies: Explore the exercises for stress relief

Journal: Write your personal journal about how you feeling today

-Calm Audio: Listen some calm & stress relief audios/ songs

License
This project is licensed under the MIT License - see the MIT file for details.

# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

Future Updates
Real-time Emotional Support Chatbot: Integrate a mental health AI chatbot that would provide real-time conversations and emotional support to users based on their input.

Emotion Recognition from Video or Audio: Use emotion recognition AI models to analyze users’ facial expressions or voice tone during video/audio assessments to determine emotional states.

Demo
https://mental-wellness-one.vercel.app/
