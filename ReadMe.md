# This page is Under construction 🚧

# Blokkah 🏢

<img src="Screenshots/logo.png" alt="Blokkah Logo" width="200" height="200"/>

A modern property marketplace mobile application built with Flutter, offering a seamless experience for property buyers, sellers, and agents. Features an AI-powered chatbot, real-time notifications, and multilingual support.

## ✨ Key Features

- 🏠 Property Listings with Advanced Filters
- 🏢 Agent Profiles
- 🔍 Search Functionality
- 🗂️ Saved Properties & Favorites
- 📊 User Profiles & Ratings
- 📈 Market Trends & Insights
- 🏦 Payment Integration (paymob)
- 🤖 AI-Powered Chatbot Assistant
- 🔐 Secure Authentication (Email, Google, Twitter)
- 🌙 Dynamic Theme (Light/Dark Mode)
- 🌐 Multilingual Support (English & Arabic)
- 📍 Interactive Maps & Location Services
- 🔔 Real-time Push Notifications
- 📱 Intuitive Onboarding Experience
- 💼 Property Management Dashboard
- 📊 Analytics & Performance Tracking

## 🎯 Technical Highlights

- **State Management**: Advanced BLoC pattern implementation with proper state handling
- **Custom Widgets**: Reusable widget library following Material Design 3 guidelines
- **API Integration**: RESTful API integration with error handling and retry mechanisms

## 🏗️ Architecture & Design Patterns

### BLoC-First Architecture
We chose a Feature-First architecture with BLoC pattern because:

#### 1. Project Structure
```
lib/
├── bloc_observer.dart      # Global BLoC state observer
├── firebase_options.dart   # Firebase configuration
├── main.dart              # Application entry point
├── generated/            # Generated localization files
├── l10n/                # Localization resources
├── layout/              # Core layout components
│   ├── app/            # Main app layout with bottom navigation
│   └── fab/            # Floating action button & dialogs
├── models/             # Data models and DTOs
├── modules/           # Feature modules
│   ├── authentication/  # Auth related features
│   ├── home/           # Home screen features
│   ├── property/       # Property listing features
│   ├── crm/           # CRM & Analytics features
│   └── more/          # Additional features
└── shared/           # Shared components
    ├── cubit/        # Global state management
    ├── router/       # Navigation & routing
    ├── theme/        # App theming & styling
    ├── utils/        # Common utilities
    └── widgets/      # Reusable widgets
```

#### 2. Architecture Benefits

- **Feature Separation**: Each feature (property, authentication, CRM) is self-contained
- **State Management**: BLoC pattern for predictable state handling
- **Modular Design**: Features can be developed and tested independently
- **Code Organization**: Clear separation between UI, business logic, and data
- **Scalability**: Easy to add new features without affecting existing ones

## 📱 Screenshots

| User Flow | Agent Flow |
|-----------|------------|
| ![](Screenshots/user_flow/Spalsh.pdf) | ![](Screenshots/agent_flow/Splash.png) |
| ![](Screenshots/user_flow/Onboarding%20-%20Select%20Language.jpg) | ![](Screenshots/agent_flow/On%20Boarding.png) |
| ![](Screenshots/user_flow/Onboarding.png) | ![](Screenshots/agent_flow/Create%20Account.png) |
| ![](Screenshots/user_flow/Create%20Account.jpg) | ![](Screenshots/agent_flow/Log%20In.png) |
| ![](Screenshots/user_flow/OTP%20verification.jpg) | ![](Screenshots/agent_flow/Dashboard.png) |
| ![](Screenshots/user_flow/Fill%20profile.jpg) | ![](Screenshots/agent_flow/Property%20Listings.png) |
| ![](Screenshots/user_flow/Home.png) | ![](Screenshots/agent_flow/Add%20Listings.png) |
| ![](Screenshots/user_flow/Explore.png) | ![](Screenshots/agent_flow/Stepper%20Flow.png) |
| ![](Screenshots/user_flow/Search.png) | ![](Screenshots/agent_flow/Profile.png) |
| ![](Screenshots/user_flow/Property.png) | ![](Screenshots/agent_flow/More.png) |
| ![](Screenshots/user_flow/Chat%20Bot.png) | ![](Screenshots/agent_flow/Annual.jpg) |
| ![](Screenshots/user_flow/More.png) | ![](Screenshots/agent_flow/Semi-Annual.jpg) |
| ![](Screenshots/user_flow/App%20Information.png) | ![](Screenshots/agent_flow/Quarterly.jpg) |

## 🛠️ Technologies Used

- **Framework**: Flutter 3.x
- **State Management**: Flutter Bloc
- **Backend Services**: Firebase (Auth, Analytics, Messaging)
- **Maps**: Google Maps Flutter
- **Networking**: Dio
- **Local Storage**: SharedPreferences
- **Localization**: Flutter Intl
- **Authentication**: Firebase Auth, Google Sign-In, Twitter Login
- **Notifications**: Firebase Cloud Messaging, Flutter Local Notifications
- **Analytics**: Firebase Analytics
- **Branch.io**: Deep Linking
- **Payment Integration**: Paymob




## 📥 Download
> **Note**: App download links may not be available as the clint didn't deploy check back later.

[![Get it on App Store](https://img.shields.io/badge/Download_on-the_App_Store-black.svg?style=for-the-badge&logo=apple&logoColor=white)](https://apps.apple.com/app/blokkah)
[![Get it on Google Play](https://img.shields.io/badge/Get_it_on-Google_Play-green.svg?style=for-the-badge&logo=google-play&logoColor=white)](https://play.google.com/store/apps/details?id=com.blokkahco.blokkah)


