# Voice Notes

It is an audio journalling app.

Voice Notes' is a user-friendly project using React for the frontend, Auth0 for authentication, Express for the backend, and MongoDB Atlas for cloud storage. 
It lets you easily record voice notes, and with OpenAI's Whisper model, converts them to text for convenient reading and editing later.

## Features

- **Voice Notes Recording:** Users can effortlessly capture their thoughts in real-time by recording voice notes throughout the day.
  
- **OpenAI Whisper Integration:** Leveraging OpenAI's Whisper model for speech-to-text transcription enhances the user experience. This feature allows users to convert voice notes into text effortlessly, facilitating easy review and analysis of daily entries.

## Tech Stack

- **Frontend:** Built using React, a powerful JavaScript library for creating dynamic and interactive user interfaces. The intuitive and responsive design ensures a seamless user experience.
  
- **Third-Party Authentication:** Employing Auth0 for robust and secure third-party authentication ensures the protection of user data and privacy. It delivers seamless sign-in experiences.
  
- **Backend:** Powered by Express, a flexible and minimalist Node.js web application framework, facilitating smooth data flow and efficient communication between the frontend and database.
  
- **Cloud Database:** MongoDB Atlas serves as the cloud database, offering scalability, performance, and reliable data storage for the 'Journaling App'.

## Environment Variables

- **OPEN_AI_KEY:** Use your OpenAI key to access the Whisper API for speech-to-text transcription.
- **DATABASE:** Connect to your own MongoDB Atlas cloud database. Follow the steps provided.
- **Auth0 Application:** Create an Auth0 application and follow the provided steps.
- **Auth0 API:** Create Auth0 API to protect your backend and replace variables as instructed.

## Local Installation Guide

### Prerequisites

- Node.js: Install node version (v18.16.0) on your local environment.
- Git: Download the latest version from their official website.

### Installation Steps

1. **Clone the repository:** Run `git clone https://github.com/Chakilam-Gayatri/VoiceNotes.git` in your terminal.
2. **Navigate to backend:** Go to the backend directory and install dependencies with `npm install`.
3. **Run backend:** Start the backend server with `nodemon server.js`.
4. **Navigate to frontend:** Move to the frontend directory and repeat step 2.
5. **Run frontend:** Start the frontend server with `npm run dev` and access the application on http://localhost:5173/.

## Future

Integrating ChatGPT to analyze journal entries and provide insights to manage triggers and monitor mood fluctuations would be an intriguing feature to explore.

---

Feel free to adjust the formatting or add any additional information specific to your project.
