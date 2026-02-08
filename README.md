# Aplayer 🎬

A modern, lightweight, and sleek video player for Android built with **Jetpack Compose** and *
*Media3 (ExoPlayer)**.

## ✨ Features

- 🎥 **Video Picker:** Easily select videos from your device using the modern Photo Picker.
- 🚀 **Powered by Media3:** High-performance playback using Google's latest Media3 ExoPlayer.
- 🎨 **Custom Compose UI:** A beautiful, responsive player interface built entirely with Jetpack
  Compose.
- ⏯️ **Seamless Controls:** Play/Pause, seeking, and real-time progress tracking.
- ⏳ **Smart Buffering:** Visual feedback during video loading and buffering.
- 🌓 **Edge-to-Edge:** Modern UI design that respects system bars and provides an immersive
  experience.

## 🛠 Tech Stack

- **Language:** [Kotlin](https://kotlinlang.org/)
- **UI Framework:** [Jetpack Compose](https://developer.android.com/jetpack/compose)
- **Media Engine:
  ** [AndroidX Media3 (ExoPlayer)](https://developer.android.com/guide/topics/media/media3)
- **Design:** Material 3
- **Build System:** Gradle (Kotlin DSL)

## 📸 Screenshots

|                         Media Picker                          |                                    Video Player                                    |
|:-------------------------------------------------------------:|:----------------------------------------------------------------------------------:|
| ![Picker Placeholder](app/src/main/ic_launcher-playstore.png) | ![Player Placeholder](app/src/main/res/mipmap-xxxhdpi/ic_launcher_foreground.webp) |

*(Note: Replace these with actual screenshots of the app in action!)*

## 🚀 Getting Started

### Prerequisites

- Android Studio Ladybug or newer.
- Android SDK level 24 (Android 7.0) or higher.

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/Aplayer.git
   ```
2. **Open in Android Studio:**
    - Go to `File > Open` and select the `Aplayer` folder.
3. **Build and Run:**
    - Connect your Android device or start an emulator.
    - Click the **Run** button in Android Studio.

## 📁 Project Structure

```text
app/src/main/java/com/actaks/aplayer/
├── MainActivity.kt        # Entry point, sets up the theme and screen
├── MediaPickerScreen.kt   # Logic for picking videos and hosting the player
├── PlayerUi.kt            # Custom Compose-based player controls
└── ui/theme/             # Theme, Color, and Type definitions
```

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Made with ❤️ by Act-Aks
