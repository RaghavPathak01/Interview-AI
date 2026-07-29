# Interview Copilot 🚀

## 📌 Overview
Interview Copilot is a full-stack, AI-powered application designed to help job seekers prepare for technical and behavioral interviews. By analyzing a user's resume and a target job description, the application generates a highly personalized interview strategy, including potential questions, skill gap analysis, and a tailored preparation plan. 

## ✨ Features
- **AI-Powered Strategy:** Leverages Google's Gemini AI to generate highly targeted, role-specific interview preparation reports.
- **Resume Parsing:** Automatically extracts and analyzes content from uploaded PDF or DOCX resumes.
- **Custom Interview Plans:** Generates likely technical questions, behavioral scenarios, and actionable plans based on the specific job description.
- **PDF Export:** Allows users to download their customized interview strategy as a cleanly formatted PDF.
- **Secure Authentication:** Complete user authentication and session management using JWT (JSON Web Tokens) and bcrypt password hashing.

## 🛠️ Tech Stack
- **Frontend:** React.js, Vite, Axios, SCSS
- **Backend:** Node.js, Express.js
- **Database:** MongoDB Atlas, Mongoose
- **AI Integration:** Google Gemini API (`@google/genai`)
- **Utilities:** Puppeteer (for web scraping context), PDF-Parse (for resume parsing)

## 🚀 Getting Started

### Prerequisites
- Node.js (v18 or higher)
- MongoDB Atlas account (or local MongoDB installation)
- Google Gemini API Key (from Google AI Studio)

### Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/interview-copilot.git
   cd interview-copilot
   ```

2. **Backend Setup**
   ```bash
   cd Backend
   npm install
   ```
   Create a `.env` file in the `Backend` directory and add the following variables:
   ```env
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret_key
   GOOGLE_GENAI_API_KEY=your_google_gemini_api_key
   ```
   Start the backend server:
   ```bash
   npm run dev
   ```

3. **Frontend Setup**
   Open a new terminal and navigate to the Frontend directory:
   ```bash
   cd Frontend
   npm install
   npm run dev
   ```

4. **Access the Application**
   Open your browser and navigate to `http://localhost:5173`.

## 🌐 Deployment Architecture
- **Frontend Hosting:** Designed to be deployed on Vercel or Netlify.
- **Backend Hosting:** Designed to be deployed on Render, Railway, or Heroku.
- **Database:** Hosted on MongoDB Atlas.

## 🤝 Contributing
Contributions, issues, and feature requests are welcome! Feel free to check the issues page.

## 📝 License
This project is [MIT](LICENSE) licensed.
