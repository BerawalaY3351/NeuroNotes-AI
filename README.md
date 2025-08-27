# NeuroNotes-AI
NeuroNotes AI is a cross platform mobile app built with Expo and React Native. The app is an AI powered trancription and summarization to help students, professionals, and researchers capture, orgranise, and retrive lecture or meeting notes efficiently.

## 🚀 Features
- 🎙 **Audio Recording** — record lectures, meetings, or study sessions directly in the app.  
- 🤖 **AI Transcription** — convert speech to text using advanced speech-to-text models.  
- 📝 **Smart Summaries** — automatically generate concise summaries of long recordings.  
- 🔍 **Search & Organise** — tag, categorise, and quickly find notes by keyword.  
- 📱 **Cross-Platform** — runs on iOS and Android via Expo.  

---

## 🛠 Tech Stack
- **Framework:** [Expo](https://expo.dev/) + React Native  
- **Language:** JavaScript / TypeScript  
- **AI Integration:** OpenAI / Whisper API (planned)  
- **State Management:** React Hooks, Context API  
- **Storage:** AsyncStorage (local) with roadmap to cloud sync (Firebase / Supabase)  

---

## 📂 Project Structure
```plaintext
NeuroNotesAI/
├── assets/             # Images, icons, fonts
├── components/         # Reusable UI components
├── screens/            # App screens (Home, Record, Notes, Settings, etc.)
├── App.js              # Main entry point
├── app.json            # Expo configuration
├── package.json        # Dependencies and scripts
└── README.md           # Project documentation
`````
---

## 🧪 Development Roadmap
NeuroNotes AI is under active development. Below is the planned roadmap outlining completed work and upcoming features:

### ✅ Completed
- Basic app UI with navigation between core screens  
- Local audio recording functionality using `expo-av`  
- Storage of recorded files in local device memory  
- Initial project setup with Expo and React Native  

### 🚧 In Progress
- Integration of **AI transcription** (Whisper API / Speech-to-Text model)  
- Clean, formatted text output after transcription  
- Improved UI/UX for recording and viewing notes  

### 🔜 Planned
- **AI-powered Summaries**: Generate concise summaries from long transcripts  
- **Cloud Sync & User Accounts**: Enable login, sync notes across devices (Firebase / Supabase)  
- **Advanced Search & Tagging**: Filter notes by keywords, subjects, or tags  
- **Export Options**: Save notes as PDF, Markdown, or shareable links  
- **Offline Support**: Access previously saved notes without internet connection  

### 🌟 Future Enhancements
- **Multilingual Support**: Transcription in multiple languages  
- **Smart Reminders**: Get reminders to review key notes  
- **Collaboration Mode**: Share and co-edit notes with teammates or classmates  
- **Voice Command Navigation**: Control the app hands-free using voice  
