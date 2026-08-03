# Language Support App

A professional Android application demonstrating dynamic localization and multi-language support. This project showcases how to implement runtime language switching and manage string resources across different locales.

## 🚀 Features

- **Dynamic Language Switching:** Change the application language at runtime without changing system settings.
- **Multi-language Support:** Pre-configured support for English, Español (Spanish), and Français (French).
- **Locale Detection:** Automatically detects and displays the current active locale.
- **Modern UI:** Built with Material Design components for a clean and intuitive user experience.
- **Resource Management:** Efficient use of Android's `values-{locale}` resource directory structure.

## 🛠 Technologies Used

- **Kotlin:** The primary programming language.
- **Android SDK:** Using modern APIs and components.
- **AppCompat & Material Design:** For backward compatibility and consistent styling.
- **Localization:** XML-based string resource management.

## 📱 Getting Started

### Prerequisites

- Android Studio Giraffe or newer.
- Android SDK 24 (Nougat) or higher.
- Gradle 8.0+

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/language-support-app.git
   ```
2. Open the project in **Android Studio**.
3. Let Gradle sync and download dependencies.
4. Run the app on an emulator or physical device.

## 📖 Usage

1. Launch the application.
2. The main screen displays the current language.
3. Tap the **"Change Language"** button.
4. Select your preferred language from the dialog (English, Español, or Français).
5. The application will automatically restart and apply the selected language.

## 📁 Project Structure

- `app/src/main/java`: Contains the Kotlin source code (e.g., `MainActivity.kt`).
- `app/src/main/res/values`: Default English string resources.
- `app/src/main/res/values-es`: Spanish string translations.
- `app/src/main/res/values-fr`: French string translations.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
*Developed with ❤️ by [Your Name]*