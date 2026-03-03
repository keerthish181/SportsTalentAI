# SportsTalentAI

SportsTalentAI is an AI-powered Android application that analyzes athletic performance using real-time video recording and pose-based evaluation.

The app records athlete movements using CameraX, calculates performance metrics, generates grades, and evaluates college eligibility. It demonstrates clean Android architecture with modern UI design.

------------------------------------------------------------

PROJECT OVERVIEW

SportsTalentAI was developed to explore real-time sports performance tracking on Android devices. The application integrates video capture, movement analysis, structured data storage, and performance evaluation within a clean MVVM architecture.

------------------------------------------------------------

CORE FEATURES

- Real-time video recording using CameraX
- Pose-based performance analysis
- Automated performance score calculation
- Grade generation (A / B / C)
- College eligibility evaluation engine
- Local storage using Room Database
- Dashboard displaying performance summary
- Professional Material3-based UI design

------------------------------------------------------------

APPLICATION FLOW

1. Splash Screen
2. Athlete Name Entry
3. Sport Selection
4. Video Recording
5. Performance Analysis
6. Dashboard Summary

------------------------------------------------------------

TECHNOLOGIES USED

- Kotlin
- Android SDK
- CameraX (Video + Image Analysis)
- Material 3 UI Components
- MVVM Architecture
- Room Database
- ViewModel and LiveData
- On-device evaluation logic

------------------------------------------------------------

ARCHITECTURE

The app follows the MVVM (Model-View-ViewModel) pattern:

UI Layer:
Activities and Layouts handling user interaction.

ViewModel Layer:
Manages business logic and UI state.

Repository Layer:
Handles data operations.

Database Layer:
Room database for storing performance records.

AI Module:
Pose analysis and performance scoring logic.

------------------------------------------------------------

VIDEO STORAGE

Recorded videos are stored locally in:

Android/data/com.example.sportstalentai/files/Movies/SportsTalentAI

Each recording is saved using sport type and timestamp.

------------------------------------------------------------

DESIGN APPROACH

The UI uses:

- Deep navy sports theme
- Orange accent highlights
- Rounded Material buttons
- Elevated card layouts
- Clean, minimal typography

The goal was to create a professional, startup-level sports analytics interface.

------------------------------------------------------------

FUTURE IMPROVEMENTS

- Cloud storage integration
- Performance history tracking
- Multi-sport expansion
- Advanced AI scoring model
- Exportable performance reports

------------------------------------------------------------

AUTHOR

Developed as an Android AI-based sports performance tracking project.

------------------------------------------------------------

LICENSE

This project is created for educational and demonstration purposes.
