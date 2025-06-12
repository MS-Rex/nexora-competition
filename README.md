# Nexora University Copilot

## Project Overview

Nexora is an AI-powered voice chat application ecosystem designed to revolutionize university communication and support. Our comprehensive solution combines real-time voice conversations, intelligent AI agents, and modern web interfaces to create an seamless educational technology platform. Built for the Nexora 1.0 Inter-University Datathon 2025, this project demonstrates advanced AI agent orchestration, real-time communication, and intelligent user interaction capabilities.

The Nexora ecosystem consists of three integrated components working together to provide a complete AI-powered university communication solution.

## System Architecture

Our project is organized into three main repositories, each handling a specific component of the Nexora ecosystem:

### 📱 [Mobile Application](https://github.com/MS-Rex/nexora-app.git)

**Flutter-based AI Voice Chat App**

- Real-time voice conversations with AI agents
- Beautiful animated UI with voice visualizations
- WebSocket communication for instant responses
- Speech recognition and audio processing
- Cross-platform mobile experience (iOS & Android)

### 🤖 [AI Agentic System](https://github.com/MS-Rex/nexora-ai.git)

**Backend AI Engine & Agent Orchestration**

- Intelligent conversation processing
- Voice-to-text and text-to-voice conversion
- AI agent management and coordination
- Machine learning pipeline integration
- [Placeholder: Additional backend features]

### 🌐 [Web Application & Landing Page](https://github.com/nilanviduranga/uni-chat-bot.git)

**Web Interface & Marketing Platform**

- University chatbot web interface
- Landing page and marketing materials
- Web-based chat functionality
- [Placeholder: Additional web features]

## Features

### Core Features

- **Real-time Voice Chat**: Instant AI-powered voice conversations
- **Cross-platform Mobile App**: Native experience on iOS and Android
- **Intelligent AI Agents**: Advanced conversation processing and responses
- **Web Chat Interface**: Browser-based chatbot for universities
- **WebSocket Communication**: Real-time bidirectional data exchange
- **Speech Recognition**: Advanced voice-to-text capabilities
- **Voice Synthesis**: Natural AI voice responses

### Additional Features

- **Beautiful Animations**: Dynamic voice wave patterns and breathing effects
- **Multi-platform Support**: Mobile, web, and backend integration
- **Secure Communication**: Encrypted real-time data transmission
- **User Authentication**: Secure user management system
- **Chat History**: Persistent conversation storage
- **Permission Management**: Granular device permission control

## Tech Stack

### Mobile Frontend (Flutter App)

- **Frontend**: Flutter 3.29.1, Dart, Material Design 3
- **State Management**: BLoC Pattern, Injectable DI
- **Navigation**: Auto Route
- **Audio**: Record Package, AudioPlayers
- **Communication**: WebSocket, JSON

### Backend (AI Agentic System)

- **Backend**: Laravel (PHP framework)
- **Real-time Communication**: Pusher (WebSocket service)
- **Authentication & Authorization**: Spatie Laravel Permission (Role management)
- **Database**: MySQL
- **AI/ML**: OpenAI Whisper (Small model - 244M parameters)
- **Voice Processing**: OpenAI Whisper for speech recognition and transcription
- **Communication**: WebSocket Gateway, REST APIs

### Web Application

- **Frontend**: Next.js (React-based framework)
- **Backend**: Laravel (PHP framework)
- **Database**: MySQL
- **Others**: [Placeholder: Additional libraries and APIs]

## Live Infrastructure

Our complete Nexora ecosystem is deployed and running live on AWS cloud infrastructure:

### AWS Architecture

- **🖥️ EC2 Instance 1**: Laravel backend server
- **🖥️ EC2 Instance 2**: FastAPI AI processing server
- **🗄️ Amazon RDS**: Managed relational database service
- **📊 Sentry**: Real-time error tracking and performance monitoring
- **🌐 Load Balancing**: Distributed across multiple availability zones

### Monitoring & Operations

- **Error Tracking**: Sentry integration for real-time error monitoring
- **Performance Monitoring**: Application performance insights and alerting
- **Database Management**: Amazon RDS for scalable and reliable data storage
- **Auto-scaling**: EC2 instances configured for dynamic scaling based on demand

**🚀 Live Demo**: [https://nexora-chat.vercel.app/](https://nexora-chat.vercel.app/)

## Screenshots/Demo

### Mobile Application Demo

![Mobile App Demo](https://via.placeholder.com/800x400?text=Mobile+App+Screenshots)
_Screenshots and demo videos available in the [mobile app repository](https://github.com/MS-Rex/nexora-app.git)_

### Web Application Demo

![Web App Demo](https://via.placeholder.com/800x400?text=Web+App+Screenshots)
_Screenshots and demo videos available in the [web app repository](https://github.com/nilanviduranga/uni-chat-bot.git)_

### AI System Architecture

![AI Architecture](https://via.placeholder.com/800x400?text=AI+System+Architecture)
_Architecture diagrams and documentation available in the [AI system repository](https://github.com/MS-Rex/nexora-ai.git)_

## Setup Instructions

To run the complete Nexora ecosystem locally, follow the setup instructions for each component:

### 1. Mobile Application Setup

```bash
# Clone the mobile app repository
git clone https://github.com/MS-Rex/nexora-app.git
cd nexora-app

# Install Flutter dependencies
flutter pub get

# Generate required files
dart run build_runner build --delete-conflicting-outputs

# Run the mobile application
flutter run
```

### 2. AI Agentic System Setup

```bash
# Clone the AI system repository
git clone https://github.com/MS-Rex/nexora-ai.git
cd nexora-ai

# [Placeholder: Installation instructions]
# Follow setup instructions in the AI system repository
```

### 3. Web Application Setup

```bash
# Clone the web app repository
git clone https://github.com/nilanviduranga/uni-chat-bot.git
cd uni-chat-bot

# [Placeholder: Installation instructions]
# Follow setup instructions in the web application repository
```

### Environment Configuration

Create `.env` files in each repository with the required environment variables. Refer to the individual repository README files for specific configuration details.

## Repository Links

| Component     | Repository                                                         | Description                                    |
| ------------- | ------------------------------------------------------------------ | ---------------------------------------------- |
| 📱 Mobile App | [nexora-app](https://github.com/MS-Rex/nexora-app.git)             | Flutter-based AI voice chat mobile application |
| 🤖 AI System  | [nexora-ai](https://github.com/MS-Rex/nexora-ai.git)               | Backend AI engine and agent orchestration      |
| 🌐 Web App    | [uni-chat-bot](https://github.com/nilanviduranga/uni-chat-bot.git) | Web interface and landing page                 |

## Team

- **[Placeholder: Team Member 1]** – AI/ML & Mobile Developer & Project Lead
- **[Placeholder: Team Member 2]** – AI/ML Engineer & Backend Developer
- **[Placeholder: Team Member 3]** – Web Developer & Frontend Developer
- **[Placeholder: Team Member 4]** – UI/UX Designer & API Integration Specialist

_Team RexFlow - Where AI meets innovation and data fuels transformation!_

## Documentation

- **Mobile App Documentation**: Available in [nexora-app repository](https://github.com/MS-Rex/nexora-app.git)
- **AI System Documentation**: Available in [nexora-ai repository](https://github.com/MS-Rex/nexora-ai.git)
- **Web App Documentation**: Available in [uni-chat-bot repository](https://github.com/nilanviduranga/uni-chat-bot.git)
- **API Documentation**: [Placeholder: Link to API docs]
- **Architecture Diagrams**: [Placeholder: Link to system architecture]

## Competition Details

**🏆 Nexora 1.0 Inter-University Datathon 2025**

This project represents a complete AI-powered university communication ecosystem, showcasing:

- Advanced AI agent orchestration
- Real-time voice and text communication
- Cross-platform mobile and web applications
- Intelligent conversation processing
- Modern UI/UX design principles

**Prizes:** 🥇 LKR 50,000 | 🥈 LKR 30,000 | 🥉 LKR 20,000

## Submission

**Developed for Nexora 1.0 – Round 2**  
**Submission Date**: 12th June 2025

**Live Demo**: https://nexora-chat.vercel.app/
**Project Website**: [nexora.msanjana.com](https://nexora.msanjana.com/)

---

## Contact & Support

- 📧 **Email**: miyurusanjana@gmail.com
- 🌐 **Website**: https://nexora-chat.vercel.app/
- 💬 **Issues**: Use the individual repository issue trackers

---

**Made with ❤️ by Team RexFlow**  
_Transforming university communication through AI-powered innovation_
