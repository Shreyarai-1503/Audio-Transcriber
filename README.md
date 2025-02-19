# Audio Transcription App with Spring AI and React

## 📌 Overview

This project demonstrates how to build an **AI-powered audio transcription application** using **Spring Boot** for the backend and **React.js** for the frontend. The application utilizes OpenAI's audio model to convert audio files into text.

## 🚀 Features

- 🎧 **Transcribe Audio**: Upload and convert audio files into text.
- ⚙️ **Spring Boot Backend**: A robust backend setup with OpenAI integration.
- 📁 **File Upload Handling**: Seamlessly process and manage audio files.
- 🛠 **Postman API Testing**: Test and validate the API.
- 💻 **React UI**: A responsive and user-friendly interface.

## 🏗️ Tech Stack

### Backend (Spring Boot)

- **Spring Boot**
- **Spring AI** (for OpenAI integration)
- **Spring Web**
- **Maven**
- **Postman** (for API testing)

### Frontend (React)

- **React.js**
- **CSS (Styled UI)**
- **Axios (for API requests)**

## 🛠 Setup Instructions

### Backend (Spring Boot)

1. **Clone the repository:**
   ```sh
   git clone https://github.com/Shreyarai-1503/Audio-Transcriber.git
   cd audio-transcribe
   ```
2. **Configure OpenAI API Key:**
   - Add the following:
     ```properties
     spring.ai.openai.api-key=your_openai_api_key
     ```
3. **Run the Spring Boot application:**
   
4. **Test API using Postman:**
   - Use the `/api/transcribe` endpoint to test audio file uploads.

### Frontend (React.js)

1. **Navigate to the frontend directory:**
   ```sh
   cd ../audio-transcribe-frontend
   ```
2. **Install dependencies:**
   ```sh
   npm install
   ```
3. **Run the React application:**
   ```sh
   npm run dev
   ```

## 🔥 Usage Guide

1. **Upload an audio file** (e.g., `.wav`, `.mp3`).
2. **Click the transcribe button** to process the file.
3. **View the transcribed text** on the UI.

## 📚 Key Insights

- 🤖 **AI Integration:** AI-powered transcription enhances web applications, making them interactive.
- 🔧 **Backend Setup:** Proper API handling ensures a smooth user experience.
- 📊 **Testing:** API testing via Postman helps debug efficiently.
- 🎨 **UI/UX Design:** A well-designed UI improves user engagement.

Made with ❤️ by [Shreya Rai](https://github.com/Shreyarai-1503) 🚀

