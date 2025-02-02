# React Native ToDo List Application

A cross-platform ToDo list application developed using React Native and Expo, with Firebase Firestore as the backend. This app demonstrates CRUD (Create, Read, Update, Delete) operations in a mobile environment.

## Features

- **Add Tasks**: Create new tasks with ease.
- **View Tasks**: Display all tasks in an organized list.
- **Edit Tasks**: Modify existing tasks as needed.
- **Delete Tasks**: Remove tasks that are no longer necessary.
- **Persistent Storage**: Utilizes Firebase Firestore to store tasks securely.

## Technologies Used

- **React Native**: Framework for building native apps using React.
- **Expo**: A platform for making React Native development easier.
- **Firebase Firestore**: NoSQL database for storing tasks.

## Installation

To run this application locally:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/JeremiahDMoore/todo-list-react-native.git
   cd todo-list-react-native
   ```

2. **Install Dependencies**:
   Ensure you have [Node.js](https://nodejs.org/) and [Expo CLI](https://docs.expo.dev/get-started/installation/) installed. Then, run:
   ```bash
   npm install
   ```

3. **Configure Firebase**:
   - Create a Firebase project in the [Firebase Console](https://console.firebase.google.com/).
   - Add a web app to your Firebase project.
   - Copy the Firebase configuration and replace the existing configuration in `config.js`.

4. **Start the Application**:
   ```bash
   expo start
   ```
   Use the Expo Go app on your mobile device to scan the QR code and run the application.

## Usage

- **Add a Task**: Tap the "Add" button, enter the task details, and save.
- **Edit a Task**: Tap on a task to modify its details.
- **Delete a Task**: Swipe left on a task to reveal the delete option.

## Acknowledgments

This application was developed to demonstrate the integration of React Native, Expo, and Firebase Firestore for building mobile CRUD applications.
