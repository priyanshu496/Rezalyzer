# Rezalyzer - AI-Powered Resume Analyzer


> **Smart feedback for your dream job** - An intelligent resume analysis platform that provides ATS scores and improvement recommendations.

## 🚀 Features

- **ATS Score Analysis** - Get comprehensive scoring based on Applicant Tracking System compatibility
- **AI-Powered Feedback** - Receive detailed insights on tone, content, structure, and skills
- **Job-Specific Analysis** - Tailored recommendations based on company and job description
- **Interactive Visualizations** - Score gauges, progress circles, and detailed breakdown charts
- **PDF Processing** - Automatic conversion and preview of uploaded resumes
- **Secure Cloud Storage** - File management and user data persistence via Puter.js platform

## 🛠️ Tech Stack

### Frontend
- **React 19** - Modern React with latest features
- **TypeScript** - Type-safe development
- **React Router v7** - File-based routing and navigation
- **Tailwind CSS** - Utility-first styling framework
- **Vite** - Fast build tool and development server

### State Management & Utilities
- **Zustand** - Lightweight state management
- **React Dropzone** - Drag-and-drop file uploads
- **PDF.js** - PDF processing and image conversion
- **clsx & tailwind-merge** - Conditional styling utilities

### Backend & Services
- **Puter.js** - Cloud platform for file storage, AI services, and authentication
- **Node.js** - Server-side runtime

## 🚀 Getting Started

### Prerequisites
- Node.js 22+ 
- npm or yarn package manager
- Puter.js account for backend services

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/rezalyzer.git
   cd rezalyzer
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start development server**
   ```bash
   npm run dev
   ```

4. **Build for production**
   ```bash
   npm run build
   npm start
   ```

## 💡 How It Works

1. **Upload Resume** - Users upload PDF resumes with job details (company, role, description)
2. **AI Analysis** - The system processes the resume using AI to analyze multiple factors:
   - **Tone & Style** - Professional language and formatting
   - **Content Quality** - Relevance and completeness of information
   - **Structure** - Organization and readability
   - **Skills Alignment** - Match with job requirements
3. **ATS Scoring** - Generate compatibility score for Applicant Tracking Systems
4. **Detailed Feedback** - Provide actionable recommendations for improvement
5. **Progress Tracking** - Save and review multiple resume submissions

## 🎯 Key Features Breakdown

### Smart File Processing
- Drag-and-drop PDF upload with 20MB limit
- Automatic PDF-to-image conversion for preview
- Secure cloud storage via Puter.js platform

### AI-Powered Analysis
- Context-aware feedback based on job descriptions
- Multi-category scoring system (0-100 scale)
- Personalized improvement suggestions

### Interactive UI
- Responsive design with mobile support
- Animated score visualizations
- Collapsible feedback sections


### Data Persistence
- User authentication and session management
- Resume history and progress tracking
- Secure file storage and retrieval

## 🔒 Security & Privacy

- Secure authentication via Puter.js platform
- Encrypted file storage and transmission
- No permanent storage of sensitive resume data
- GDPR-compliant data handling practices

## 🙏 Acknowledgments

- [Puter.js](https://puter.com) - Cloud platform and AI services
- [React Router](https://reactrouter.com) - Application routing
- [Tailwind CSS](https://tailwindcss.com) - Styling framework
- [PDF.js](https://mozilla.github.io/pdf.js/) - PDF processing library

---
