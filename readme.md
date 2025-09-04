# Sanvaad - A Multimodal Interaction System for Language Barriers

![Sanvaad Project Banner](https://img.shields.io/badge/Sanvaad-Breaking%20Barriers-blue?style=for-the-badge&logo=react)

A multimodal interaction system designed to bridge communication gaps for individuals with speech and hearing impairments by integrating real-time sign language recognition and voice translation.

![React Version](https://img.shields.io/badge/React-18.3.1-61DAFB?logo=react&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-5.0+-3178C6?logo=typescript&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green)

## 📖 About The Project

Communication is a fundamental human right, yet it remains a significant challenge for many with speech and hearing impairments. **Sanvaad** (Sanskrit for "dialogue") is a capstone project that addresses this issue by providing a unified, offline-first communication aid.

The application features two core AI-powered modules:

🤟 **Real-time Sign Language Recognition**: Computer vision system that recognizes Indian Sign Language (ISL) through a standard webcam using OpenCV and MediaPipe.

🗣️ **Voice Translation System**: Offline voice translator that provides keyword-based, two-way translation between English and Hindi/Marathi.

The project's main innovation is its **offline-first design**, ensuring user privacy and dependability without requiring an internet connection for core features.

## ✨ Key Features

### 🤟 Real-Time Sign Language Recognition
- Utilizes OpenCV and MediaPipe for ISL gesture interpretation
- Live video feed processing with real-time recognition
- Sentence expansion from recognized words
- Text-to-speech conversion for recognized signs

### 🗣️ Offline Voice Translation
- Multi-language support (English, Hindi, Marathi)
- Real-time speech-to-text conversion using Vosk
- Bidirectional translation capabilities
- Cultural context insights for better communication
- Natural-sounding text-to-speech output

### 🌐 AI Enhancements (Gemini API)
- **Sentence Expander**: Converts single words into complete, polite sentences
- **Cultural Context**: Provides cultural insights for appropriate communication
- **Enhanced Translation**: Nuanced translations with context awareness
- **Natural TTS**: AI-powered text-to-speech for smoother interactions

### 🎨 Modern User Interface
- Clean, intuitive design built with React and Tailwind CSS
- Responsive design for all device types
- Accessibility-focused with high contrast and clear typography
- Smooth animations and transitions
- Dark/light mode support

### 🔒 Privacy-Focused
- Core functionalities work completely offline
- No data transmission for basic features
- User privacy and security prioritized
- Local processing for sensitive communications

## 🛠️ Built With

### Frontend
- **React.js** - Modern JavaScript library for building user interfaces
- **TypeScript** - Type-safe JavaScript for better development
- **Tailwind CSS** - Utility-first CSS framework
- **Lucide React** - Beautiful icon library
- **React Router** - Client-side routing
- **Shadcn/ui** - High-quality accessible components

### Backend (Planned Integration)
- **Python** - Core backend language
- **Flask** - Lightweight web framework
- **OpenCV** - Computer vision library
- **MediaPipe** - ML framework for multimodal data
- **TensorFlow** - Machine learning framework
- **Vosk** - Offline speech recognition
- **pyttsx3** - Text-to-speech conversion

### AI & APIs
- **Google Gemini API** - Advanced AI capabilities
- **Custom ML Models** - Sign language recognition

## 🚀 Getting Started

### Prerequisites

- **Node.js** 18+ and npm
- **Python** 3.9+ and pip (for backend integration)
- **Webcam** and **microphone** for full functionality
- **Modern web browser** with WebRTC support

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/sanvaad.git
   cd sanvaad
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the development server**
   ```bash
   npm run dev
   ```

4. **Open your browser**
   ```
   Navigate to http://localhost:5173
   ```

### Backend Setup (Coming Soon)

```bash
# Navigate to backend directory
cd backend

# Create virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install Python dependencies
pip install -r requirements.txt

# Run the backend server
python app.py
```

## 💡 Usage

### 🏠 Home Interface
- Overview of all available features
- Quick access to sign language and voice translation modes
- Feature demonstrations and tutorials

### 🤟 Sign Language Interface
1. **Activate Webcam**: Grant camera permissions
2. **Perform Gestures**: Use ISL gestures in front of the camera
3. **View Recognition**: See recognized words in real-time
4. **Expand Sentences**: Convert single words to complete sentences
5. **Listen**: Use text-to-speech to hear the expanded sentences

### 🗣️ Voice Translator Interface
1. **Select Languages**: Choose source and target languages
2. **Start Recording**: Use microphone to capture speech
3. **View Translation**: See real-time translation results
4. **Cultural Context**: Get insights for appropriate communication
5. **Play Audio**: Listen to translated text in target language

## 🎯 Project Structure

```
sanvaad/
├── src/
│   ├── components/           # Reusable UI components
│   │   ├── ui/              # Shadcn/ui components
│   │   └── Header.tsx       # Navigation header
│   ├── pages/               # Main application pages
│   │   ├── Home.tsx         # Landing page
│   │   ├── SignLanguage.tsx # Sign language interface
│   │   └── VoiceTranslator.tsx # Voice translation interface
│   ├── assets/              # Images and static files
│   ├── hooks/               # Custom React hooks
│   ├── lib/                 # Utility functions
│   └── App.tsx             # Main application component
├── backend/                 # Python backend (planned)
├── public/                  # Public assets
└── README.md               # Project documentation
```

## 🌟 Features in Development

- [ ] **Backend Integration**: Connect with Python ML backend
- [ ] **Offline Mode**: Full offline functionality
- [ ] **Extended ISL Support**: Expanded sign language vocabulary
- [ ] **Voice Training**: Custom voice model training
- [ ] **Multi-user Sessions**: Collaborative communication sessions
- [ ] **Mobile App**: React Native mobile application
- [ ] **Analytics Dashboard**: Usage insights and improvements
- [ ] **Accessibility Enhancements**: Advanced screen reader support

## 🤝 Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### Development Guidelines

- Follow React and TypeScript best practices
- Use semantic commit messages
- Ensure accessibility compliance
- Test across different devices and browsers
- Update documentation for new features

## 📝 License

Distributed under the MIT License. See `LICENSE` for more information.

## 🙏 Acknowledgments

- [React Team](https://reactjs.org/) for the amazing framework
- [Tailwind CSS](https://tailwindcss.com/) for the utility-first CSS framework
- [OpenCV](https://opencv.org/) for computer vision capabilities
- [MediaPipe](https://mediapipe.dev/) for ML framework
- [Shadcn/ui](https://ui.shadcn.com/) for beautiful UI components
- [Lucide](https://lucide.dev/) for the icon library


<div align="center">
  <strong>Breaking Barriers Through Technology</strong>
  <br>
  Made with ❤️ for accessibility and inclusion
</div>
