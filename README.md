# 🤖 Orbi 2 - AI Conversation Partner

An intelligent, modern chat application powered by Google's Gemini AI, featuring a sleek dark mode interface and seamless Google OAuth integration.

![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)
![Google AI](https://img.shields.io/badge/Google_AI-4285F4?style=for-the-badge&logo=google&logoColor=white)

## ✨ Features

- 🎨 **Modern Dark Mode UI** - Beautiful, responsive interface with smooth animations
- 🤖 **Gemini AI Integration** - Powered by Google's advanced Gemini AI model
- 🔐 **Google OAuth Login** - Secure authentication with Google Sign-In
- 💬 **Real-time Chat** - Instant AI responses with typing indicators
- 📱 **Fully Responsive** - Works seamlessly on desktop, tablet, and mobile
- 🎯 **Quick Actions** - Pre-built prompts for common tasks
- 📝 **Character Counter** - 4000 character limit with live counter
- 🌐 **Firebase Hosting** - Fast, secure deployment on Firebase

## 🚀 Live Demo

[View Live Demo](https://orbi-2.web.app) _(Coming Soon)_

## 📸 Screenshots

_Screenshots coming soon_

## 🛠️ Technologies Used

- **Frontend**: HTML5, CSS3, Vanilla JavaScript
- **AI Engine**: Google Gemini AI API
- **Authentication**: Google OAuth 2.0
- **Hosting**: Firebase Hosting
- **Design**: Custom CSS with modern design tokens

## 📦 Installation

### Prerequisites

- Node.js (v14 or higher)
- Firebase CLI
- Google AI API Key
- Google OAuth Client ID

### Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/Maruthi-2025/orbi-AI.git
   cd orbi-AI
   ```

2. **Create environment configuration**
   ```bash
   # Create .env file (never commit this!)
   touch .env
   ```

3. **Add your credentials to .env**
   ```env
   GEMINI_API_KEY=your_gemini_api_key_here
   GOOGLE_CLIENT_ID=your_google_client_id_here
   ```

4. **Install Firebase CLI** (if not already installed)
   ```bash
   npm install -g firebase-tools
   ```

5. **Login to Firebase**
   ```bash
   firebase login
   ```

6. **Initialize Firebase** (already configured)
   ```bash
   firebase init
   ```

7. **Serve locally**
   ```bash
   firebase serve
   ```

8. **Deploy to Firebase**
   ```bash
   firebase deploy
   ```

## 🔐 Security

⚠️ **Important**: Never commit API keys or sensitive credentials to Git!

- Use environment variables for all sensitive data
- The `.env` file is already in `.gitignore`
- Consider using Firebase Functions for server-side API calls
- Implement API key restrictions in Google Cloud Console

## 📁 Project Structure

```
orbi-AI/
├── public/
│   └── index.html          # Main application file
├── .firebaserc             # Firebase project configuration
├── firebase.json           # Firebase hosting configuration
├── .gitignore              # Git ignore rules
└── README.md               # Project documentation
```

## 🎯 Usage

1. **Sign in with Google** - Click the Google Sign-In button
2. **Start chatting** - Type your message in the input field
3. **Use quick actions** - Click pre-built prompts for common tasks
4. **View conversations** - Access your chat history in the sidebar

## 🤝 Contributing

Contributions are welcome! Feel free to:

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 👨‍💻 Author

**Maruthi**
- GitHub: [@Maruthi-2025](https://github.com/Maruthi-2025)
- Email: mudhirajmaruthi4@gmail.com

## 🙏 Acknowledgments

- Google Gemini AI for the powerful language model
- Firebase for hosting and infrastructure
- Google OAuth for secure authentication

## 📊 Project Status

🚧 **Active Development** - This project is actively being developed and improved.

---

⭐ Star this repository if you find it helpful!
