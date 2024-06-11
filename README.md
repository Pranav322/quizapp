# QuizApp

QuizApp is a Flutter-based mobile application that allows users to take quizzes on various topics. The app retrieves quiz data from Firebase Firestore and provides an interactive and user-friendly interface for quiz-taking.

## Features

- **User Authentication**: Secure user authentication with Firebase Auth.
- **Real-time Data**: Retrieve quiz data in real-time from Firebase Firestore.
- **Interactive UI**: A clean and responsive user interface using Flutter's modern design principles.
- **Progress Tracking**: Track the user's progress through quizzes with a progress bar.
- **User Reports**: Update and display user performance reports.

## Getting Started

### Prerequisites

Before you begin, ensure you have met the following requirements:

- You have installed [Flutter](https://flutter.dev/docs/get-started/install).
- You have a Google Firebase account and have set up a Firebase project.

### Installation

1. **Clone the repository**:

    ```bash
    git clone https://github.com/yourusername/quizapp.git
    cd quizapp
    ```

2. **Install dependencies**:

    ```bash
    flutter pub get
    ```

3. **Set up Firebase**:

    - Go to the Firebase console and create a new project.
    - Enable Firestore and Authentication.
    - Download the `google-services.json` file and place it in the `android/app` directory.
    - Follow the [Firebase setup instructions](https://firebase.google.com/docs/flutter/setup) for iOS and Android.

4. **Run the app**:

    ```bash
    flutter run
    ```


## Usage

- **Launching the app**: Upon launching, users will be prompted to sign in.
- **Selecting a quiz**: Users can browse and select a quiz from the list of available topics.
- **Taking a quiz**: Users answer questions one by one. Feedback is provided after each question.
- **Completing a quiz**: Users receive a funny gif as response if they win and their report is updated in Firestore.

OR

### Getting the App

To get started, download the latest version of the app from the [Releases](https://github.com/Pranav322/quizapp/releases/tag/v0.0.1) section.

### Launching the App

Upon launching, users will be prompted to sign in.

### Selecting a Quiz

Users can browse and select a quiz from the list of available topics.

### Taking a Quiz

Users answer questions one by one. Feedback is provided after each question.

### Completing a Quiz

Users receive a funny gif as a response if they win, and their report is updated in Firestore.



## Contributing

You can if you have no other work to do.




## Acknowledgments

- [Flutter](https://flutter.dev/)
- [Firebase](https://firebase.google.com/)
- [FireShip](https://fireship.io)
