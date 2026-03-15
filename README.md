# 🧠 Kawach AI-Powered Mental Wellness Platform

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![React](https://img.shields.io/badge/React-19.0.0-blue.svg)](https://reactjs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.7.2-blue.svg)](https://www.typescriptlang.org/)
[![Express.js](https://img.shields.io/badge/Express.js-4.21.2-green.svg)](https://expressjs.com/)
[![Vite](https://img.shields.io/badge/Vite-6.2.0-purple.svg)](https://vitejs.dev/)

> **Transform your mental wellness journey with AI-driven insights, personalized therapy plans, and interactive experiences designed to help you overcome depression, stress, anxiety, and restlessness.**

## 🌟 Overview

MindSync is a comprehensive mental wellness platform that combines cutting-edge AI technology with evidence-based therapeutic approaches. Our platform provides personalized mental health support through mood tracking, guided meditation, therapeutic games, and AI-powered chatbot assistance.

### 🎯 Key Features

- **🤖 AI-Powered Mood Analysis** - Real-time emotion detection using Google Gemini 2.0 Flash
- **📊 Personalized Therapy Plans** - Custom mental health plans tailored to your needs
- **🧘 Guided Meditation** - Interactive meditation sessions with progress tracking
- **🎮 Therapeutic Games** - Engaging games designed for mental wellness
- **💬 24/7 AI Chatbot Support** - Round-the-clock mental health assistance
- **👥 Therapist Marketplace** - Connect with licensed mental health professionals
- **📈 Progress Analytics** - Track your mental health journey with detailed insights

## 🚀 Live Demo

- **Frontend**: [http://localhost:5173](http://localhost:5173)
- **Backend API**: [http://localhost:5000](http://localhost:5000)
- **GitHub Repository**: [https://github.com/Sidhant-Mishra/MindSync](https://github.com/Sidhant-Mishra/MindSync)

## 🛠️ Technology Stack

### Frontend
- **React 19** with TypeScript
- **Vite** for fast development and building
- **Tailwind CSS** for styling
- **Framer Motion** for animations
- **Radix UI** for accessible components
- **React Router** for navigation

### Backend
- **Express.js** with ES modules
- **Google Gemini AI** for emotion detection
- **CORS** enabled for cross-origin requests
- **RESTful API** architecture

### Machine Learning
- **EEG Data Analysis** with custom ML models
- **Emotion Classification** algorithms
- **Python-based** data processing and visualization

## 📦 Installation & Setup

### Prerequisites
- Node.js (v18 or higher)
- npm or yarn
- Git

### 1. Clone the Repository
```bash
git clone https://github.com/Sidhant-Mishra/MindSync.git
cd Mind_Sync
```

### 2. Install Dependencies

#### Frontend Setup
```bash
cd client
npm install
```

#### Backend Setup
```bash
cd server
npm install
```

### 3. Environment Configuration

Create a `.env` file in the server directory:
```env
GOOGLE_AI_API_KEY=your_google_ai_api_key_here
PORT=5000
```

### 4. Run the Application

#### Start the Backend Server
```bash
cd server
npm start
# or for development
node app.js
```

#### Start the Frontend Development Server
```bash
cd client
npm run dev
```

### 5. Access the Application
- **Frontend**: Open [http://localhost:5173](http://localhost:5173) in your browser
- **Backend API**: Available at [http://localhost:5000](http://localhost:5000)

## 📁 Project Structure

```
Mind_Sync/
├── client/                 # React frontend application
│   ├── src/
│   │   ├── components/     # Reusable UI components
│   │   ├── pages/         # Page components
│   │   ├── assets/        # Static assets
│   │   └── lib/          # Utility functions
│   ├── public/            # Public assets
│   └── package.json
├── server/                # Express.js backend
│   ├── controllers/       # Route controllers
│   ├── models/           # Data models
│   ├── routes/           # API routes
│   ├── utils/            # Utility functions
│   └── app.js            # Main server file
├── EEG ML Model/         # Machine learning models
│   ├── eeg_classifier    # Trained model
│   ├── results.csv       # Model results
│   └── *.png            # Visualization files
└── README.md
```

## 🔧 API Endpoints

### Mood Detection
```http
POST /detect-mood
Content-Type: application/json

{
  "text": "I'm feeling really stressed today"
}
```

**Response:**
```json
{
  "emotion": "Stressful"
}
```

### Health Check
```http
GET /
```

**Response:**
```
Server runs well.
```

## 🎨 Features in Detail

### 🏠 Landing Page
- Hero section with animated text
- Feature showcase with 3D cards
- Call-to-action buttons
- Responsive design

### 📖 About Page
- Project mission and vision
- Technology stack overview
- Team information
- Contact details

### 📞 Contact Page
- Contact form with validation
- Pricing plans (Basic, Premium, Enterprise)
- Demo payment processing
- Support resources and FAQ

### 🎮 Dashboard
- Mood tracking interface
- Progress visualization
- Quick access to features
- AI-powered insights

### 🧘 Meditation Room
- Guided meditation sessions
- Progress tracking
- Audio controls
- Timer functionality

### 🎯 Games & Challenges
- Therapeutic games
- Mental wellness challenges
- Progress tracking
- Achievement system

## 🤖 AI Integration

### Emotion Detection
Our platform uses Google Gemini 2.0 Flash to analyze user input and detect emotions from a predefined set:
- Stressful, Frustrated, Sad, Angry, Anxious
- Confident, Excited, Happy, Hopeful
- Depressed, Overwhelmed, Calm, Annoyed, Tense

### EEG Data Analysis
The project includes machine learning models for EEG data analysis:
- Emotion classification from brain signals
- Training and validation plots
- ROC curves for model evaluation
- Confusion matrix analysis

## 🚀 Deployment

### Frontend Deployment (Vercel/Netlify)
```bash
cd client
npm run build
# Deploy the dist/ folder
```

### Backend Deployment (Railway/Heroku)
```bash
cd server
# Configure environment variables
# Deploy with your preferred platform
```

## 🤝 Contributing

We welcome contributions! Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Sidhant Mishra**
- GitHub: [@Sidhant-Mishra](https://github.com/Sidhant-Mishra)
- LinkedIn: [sidhantmishra](https://linkedin.com/in/sidhantmishra)
- Email: sidhantmishra2003@gmail.com

## 🙏 Acknowledgments

- Google Gemini AI for emotion detection capabilities
- React and Vite communities for excellent tooling
- Tailwind CSS for beautiful styling
- All contributors and users who provide feedback

## 📊 Project Statistics

- **Languages**: TypeScript (90.7%), JavaScript (5.6%), CSS (3.4%), HTML (0.3%)
- **Total Commits**: Multiple feature additions and improvements
- **Last Updated**: January 2025
- **Active Development**: Yes

## 🔮 Future Roadmap

- [ ] Mobile app development (React Native)
- [ ] Advanced AI therapy recommendations
- [ ] Group therapy sessions
- [ ] Integration with wearable devices
- [ ] Multi-language support
- [ ] Advanced analytics dashboard

## 📞 Support

If you have any questions or need help:

- **Email**: sidhantmishra2003@gmail.com
- **Phone**: +91 9810290156
- **Address**: Delhi, India 110043
- **Business Hours**: Mon-Fri: 9AM-6PM IST, Sat: 10AM-4PM IST

---

<div align="center">

**Made with ❤️ for better mental health**

[⭐ Star this repo](https://github.com/Sidhant-Mishra/MindSync) | [🐛 Report Bug](https://github.com/Sidhant-Mishra/MindSync/issues) | [💡 Request Feature](https://github.com/Sidhant-Mishra/MindSync/issues)

</div>
