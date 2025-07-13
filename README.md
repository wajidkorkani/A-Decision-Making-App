# Ask Me Anything (Magic 8 Ball)

A simple Flutter application that simulates a Magic 8 Ball. Tap the ball to get a new answer!

## ✨ Features

* **Interactive Ball:** Tap the ball to receive a new, randomly generated response.
* **Clean UI:** A straightforward and easy-to-use interface.
* **Material Design:** Built with Flutter's Material Design components for a modern look and feel.

## 🚀 Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

Before you begin, ensure you have the following installed:

* [Flutter SDK](https://flutter.dev/docs/get-started/install)
* [VS Code](https://code.visualstudio.com/) or [Android Studio](https://developer.android.com/studio) with the Flutter plugin installed.

### Installation

1.  **Clone the repository:**

    ```bash
    git clone https://github.com/wajidkorkani/A-Decision-Making-App.git
    cd A-Decision-Making-App/dma
    ```

2.  **Get dependencies:**

    ```bash
    flutter pub get
    ```

3.  **Add Images:**
    This project requires image assets. You need to create an `images` folder in the root of your project and place five image files named `ball1.png`, `ball2.png`, `ball3.png`, `ball4.png`, and `ball5.png` inside it.

    Your project structure should look something like this:

    ```
    your_project_name/
    ├── lib/
    │   └── main.dart
    ├── images/
    │   ├── ball1.png
    │   ├── ball2.png
    │   ├── ball3.png
    │   ├── ball4.png
    │   └── ball5.png
    ├── pubspec.yaml
    └── ... (other project files)
    ```

    Ensure your `pubspec.yaml` file includes the assets:

    ```yaml
    flutter:
      uses-material-design: true
      assets:
        - images/
    ```
    If you don't have these images, the app will crash due to missing assets. You can create simple placeholder images or find free stock images online.

### Running the App

To run the app on a connected device or emulator:

```bash
flutter run