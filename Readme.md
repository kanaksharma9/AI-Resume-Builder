Markdown
# AI-Powered Resume Builder 

A full-stack web application designed to help users dynamically generate professional, ATS-friendly resumes. Built with the MERN stack and powered by the Google Gemini API, this application takes standard user input and intelligently summarizes, enhances, and formats job experiences using advanced Natural Language Processing (NLP).

## ✨ Features

* **AI Content Generation:** Leverages the Google Gemini API to automatically generate impactful, professional summaries for job experiences.
* **Dynamic PDF Export:** Seamlessly compiles user data and AI-generated content into a beautifully formatted, downloadable PDF resume.
* **Fully Containerized:** Architected with Docker and Docker Compose for instant local development and scalable production deployment.
* **Responsive UI:** Built with React and Vite for a lightning-fast, mobile-friendly user experience.

## 🛠️ Tech Stack

* **Frontend:** React, Vite, React Router
* **Backend:** Node.js, Express.js
* **Database:** MongoDB
* **AI Integration:** Google Gemini 1.5 API
* **DevOps/Deployment:** Docker, Docker Compose, Render

## 🚀 Getting Started

### Prerequisites

To run this project locally, you will need:
* [Docker Desktop](https://www.docker.com/products/docker-desktop/) installed and running.
* A [Google Gemini API Key](https://aistudio.google.com/app/apikey).
* A MongoDB connection string (local or MongoDB Atlas).

### 1. Clone the Repository
```bash
git clone [https://github.com/kanaksharma9/AI-Resume-Builder.git](https://github.com/kanaksharma9/AI-Resume-Builder.git)
cd AI-Resume-Builder
2. Environment Variables
Create a .env file in the root directory and add the following keys:
  MONGO_URI=your_mongodb_connection_string
  GEMINI_API_KEY=your_google_gemini_api_key
3. Run with Docker (Recommended)
You can spin up the entire application (Frontend, Backend, and Database) using a single command:

Bash
docker-compose up --build
The Frontend will be available at http://localhost:3000

The Backend API will be running on http://localhost:5000

4. Run Manually (Without Docker)
If you prefer to run the services separately:

Backend:
cd backend
npm install
npm start

Frontend:
cd frontend
npm install
npm run dev


🌐 Live Deployment
Backend API: Deployed via Docker containers on Render.

Frontend: https://ai-resume-builder-rcjf.onrender.com
