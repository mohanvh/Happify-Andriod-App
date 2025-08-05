# 🌟 Happy Places - Android App

[![Android](https://img.shields.io/badge/Android-21+-green.svg)](https://developer.android.com/)
[![Kotlin](https://img.shields.io/badge/Kotlin-1.3+-blue.svg)](https://kotlinlang.org/)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

A beautiful and intuitive Android application that helps users capture, store, and relive their happy moments and favorite places. Built with modern Android development practices using Kotlin and Material Design principles.

## 📱 About the App

Happy Places is a personal memory keeper that allows users to:
- **Capture Memories**: Add photos and details of your favorite places
- **Location Tracking**: Automatically capture and store location data
- **Personal Journal**: Add descriptions and dates to your memories
- **Interactive Maps**: View your happy places on Google Maps
- **User Authentication**: Secure login and registration system
- **Swipe Gestures**: Intuitive swipe-to-edit and swipe-to-delete functionality

## ✨ Key Features

### 🔐 User Authentication
- Secure login and registration system
- Session management with SharedPreferences
- Auto-redirect for logged-in users

### 📍 Location Services
- GPS location capture
- Google Places integration
- Interactive map viewing
- Address reverse geocoding

### 📸 Media Management
- Camera integration for photo capture
- Gallery image selection
- Image storage and retrieval
- Circular image display

### 🎨 Modern UI/UX
- Material Design components
- Smooth animations and transitions
- Swipe gestures for actions
- Responsive layout design

### 💾 Data Persistence
- SQLite database for local storage
- User-specific data isolation
- Efficient CRUD operations

## 🛠 Technology Stack

- **Language**: Kotlin
- **Minimum SDK**: Android 21 (Android 5.0)
- **Target SDK**: Android 29 (Android 10)
- **Architecture**: MVC Pattern
- **Database**: SQLite with DatabaseHandler
- **UI Components**: Material Design, RecyclerView, CardView
- **Location Services**: Google Play Services Location
- **Maps**: Google Maps API
- **Permissions**: Dexter Runtime Permissions
- **Image Handling**: CircleImageView, Volley

## 📋 Prerequisites

Before running this project, make sure you have:

- Android Studio 4.0 or higher
- Android SDK 21 or higher
- Google Maps API Key (for location features)
- Google Play Services (for location and maps)

## 🚀 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/mohanvh/Happify-Andriod-App.git
   cd Happify-Andriod-App
   ```

2. **Open in Android Studio**
   - Launch Android Studio
   - Select "Open an existing Android Studio project"
   - Navigate to the cloned directory and select it

3. **Configure Google Maps API Key**
   - Get your API key from [Google Cloud Console](https://console.cloud.google.com/)
   - Replace the placeholder in `app/src/main/res/values/strings.xml`:
   ```xml
   <string name="google_maps_api_key">YOUR_API_KEY_HERE</string>
   ```

4. **Build and Run**
   - Connect your Android device or start an emulator
   - Click "Run" in Android Studio
   - The app will install and launch on your device

## 📱 Screenshots

> **📸 Add your app screenshots here!**
> 
> Create a `screenshots/` folder in your repository root and add the following images:
> - `login_screen.png` - Login/Registration screen
> - `main_screen.png` - Main dashboard with happy places list
> - `add_place.png` - Add new happy place screen
> - `detail_view.png` - Happy place detail view
> - `map_view.png` - Map view of happy places
> - `swipe_actions.png` - Swipe gestures demonstration

### Screenshot Guidelines:
- **Size**: 1080x1920 pixels (9:16 ratio) or 1920x1080 (16:9 ratio)
- **Format**: PNG or JPG
- **Quality**: High resolution, clear and crisp
- **Content**: Show the most important features and UI elements

## 🏗 Project Structure

```
app/
├── src/main/
│   ├── java/com/happyplaces/
│   │   ├── activities/          # UI Activities
│   │   ├── adapters/           # RecyclerView Adapters
│   │   ├── database/           # Database operations
│   │   ├── models/             # Data models
│   │   └── utils/              # Utility classes
│   ├── res/
│   │   ├── layout/             # UI layouts
│   │   ├── drawable/           # Images and drawables
│   │   ├── values/             # Strings, colors, styles
│   │   └── menu/               # Menu resources
│   └── AndroidManifest.xml     # App configuration
└── build.gradle               # App-level dependencies
```

## 🔧 Configuration

### Required Permissions
The app requires the following permissions:
- `READ_EXTERNAL_STORAGE` - For accessing gallery images
- `WRITE_EXTERNAL_STORAGE` - For saving captured images
- `CAMERA` - For taking photos
- `ACCESS_FINE_LOCATION` - For precise location tracking
- `ACCESS_COARSE_LOCATION` - For approximate location

### Google Maps Setup
1. Enable Google Maps API in Google Cloud Console
2. Create credentials (API Key)
3. Add the API key to `strings.xml`
4. Enable billing (required for Google Maps API)

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Mohan VH**
- GitHub: [@mohanvh](https://github.com/mohanvh)
- Project Link: [https://github.com/mohanvh/Happify-Andriod-App](https://github.com/mohanvh/Happify-Andriod-App)

## 🙏 Acknowledgments

- [Material Design](https://material.io/) for UI components
- [Google Maps API](https://developers.google.com/maps) for location services
- [Dexter](https://github.com/Karumi/Dexter) for runtime permissions
- [CircleImageView](https://github.com/hdodenhof/CircleImageView) for circular images

---

⭐ **Star this repository if you found it helpful!** 