# 🦯 Blind Assistance App

Android application that assists visually impaired users by detecting real-world objects using TensorFlow Lite and providing voice feedback. The app also stores detection history in Firebase.

## 📸 Features

- 🧠 Detects 20+ common objects using on-device ML (TensorFlow Lite)
- 🔊 Real-time voice alerts for detected objects
- ☁️ Saves detection history in Firebase
- 📱 Clean UI with Kotlin and XML
- 🔐 Offline capable

## 🛠️ Tech Stack

- Android (Kotlin, Java)
- TensorFlow Lite (Object Detection)
- Firebase (Realtime Database)
- Text-to-Speech API

## 🚀 Getting Started

### Prerequisites

- Android Studio Hedgehog or later
- Gradle 8+
- Android SDK 33+

### Installation

```bash
git clone https://github.com/TennisPotter/BlindAssistance.git
cd BlindAssistance
```

- Open in Android Studio and run on emulator or physical device.

### Firebase Setup

1. Create Firebase project.
2. Enable Realtime Database.
3. Download `google-services.json` and add to `/app`.

## 📂 Project Structure

```
BlindAssistance/
├── app/
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/com/yourapp/
│   │   │   └── res/
│   │   └── AndroidManifest.xml
├── build.gradle.kts
├── settings.gradle.kts
└── README.md
```

## 🤝 Contributing

Pull requests welcome! For major changes, open an issue first to discuss.

🙋‍♂️ About the Developer
Developed by S. TENNIS MCA,
💻 Passionate about Software and Android development.
📫 Reach me at: tennisoffcial@gmail.com
🌐 GitHub | LinkedIn

## 📄 License

[MIT](LICENSE)
