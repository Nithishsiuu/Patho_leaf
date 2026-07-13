# 🌿 Patho Leaf

Patho Leaf is an Android application developed using Kotlin that helps identify tomato leaf diseases using Artificial Intelligence. The application analyzes an uploaded or captured leaf image using a TensorFlow Lite model and provides disease predictions along with treatment recommendations and preventive measures.

## Features

- 📷 Capture or upload tomato leaf images
- 🤖 AI-powered disease detection using TensorFlow Lite
- 🌱 Provides treatment recommendations
- 🛡️ Suggests preventive measures
- 📱 User-friendly Android interface
- ⚡ Fast on-device inference without requiring internet connectivity

## Technologies Used

- Kotlin
- Android Studio
- Android SDK
- AndroidX
- Material Design
- ConstraintLayout
- View Binding
- LiveData
- ViewModel
- TensorFlow Lite
- TensorFlow Lite Support Library

## Machine Learning

The application uses a TensorFlow Lite model for classifying tomato leaf diseases directly on the device, enabling quick predictions while maintaining user privacy.

## Project Structure

```
PathoLeaf/
│
├── app/
│   ├── src/
│   ├── ml/
│   ├── java/
│   ├── res/
│   └── AndroidManifest.xml
│
├── gradle/
├── build.gradle.kts
└── settings.gradle.kts
```

## Installation

1. Clone the repository

```bash
git clone https://github.com/yourusername/PathoLeaf.git
```

2. Open the project in Android Studio.

3. Allow Gradle to sync.

4. Build and run the application on an Android device or emulator.

## Future Improvements

- Support multiple crop species
- Cloud-based disease database
- Real-time camera detection
- Disease history tracking
- Multi-language support
- Offline medicine recommendation database

## Authors

Nithish Kumar V

## License

This project is licensed under the MIT License.
