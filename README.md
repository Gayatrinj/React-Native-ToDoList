# React-Native-ToDo

This is a [**React Native**](https://reactnative.dev) To-Do List app that allows users to manage their daily tasks. The app is built using React Native and includes features such as task management, persistent storage, animations, and more.

---

## Features

- **Add Tasks:** Users can add tasks to the list.
- **Delete Tasks:** Tasks can be removed from the list.
- **Edit Tasks:** Task descriptions can be modified.
- **Mark Tasks as Complete:** Users can toggle the completion status of tasks with visual feedback.
- **Persistent Storage:** Tasks are saved locally using AsyncStorage, so they remain even after the app is closed.
- **Smooth Animations:** Animated transitions for task actions, such as fade-out effects for deletions, enhance the user experience.

---

## Getting Started

> **Note:** Make sure you have completed the [React Native - Environment Setup](https://reactnative.dev/docs/environment-setup) instructions up to the "Creating a new application" step before proceeding.

### Prerequisites

1. Follow the [React Native Environment Setup Guide](https://reactnative.dev/docs/environment-setup).
2. Install Node.js and npm from [Node.js](https://nodejs.org/).
3. Install Android Studio or Xcode based on your development platform.

### Clone the Repository

```bash
git clone https://github.com/Gayatrinj/React-Native-ToDoList.git
cd React-Native-ToDoList
```

---

### Installation

1. **Install Dependencies:**

   ```bash
   npm install
   ```

2. **Start Metro Bundler:**

   ```bash
   npx react-native start
   ```

3. **Run the App:**
   - For Android:
     ```bash
     npx react-native run-android
     ```
   - For iOS:
     ```bash
     npx react-native run-ios
     ```

4. **Modify the App:**
   - Open `App.tsx` in your preferred editor to make changes.
   - Reload the app to see updates:
     - Android: Press `R` twice or use `Ctrl + M` (Windows/Linux) or `Cmd ⌘ + M` (macOS).
     - iOS: Press `Cmd ⌘ + R` in the iOS simulator.

---

## Troubleshooting

### Common Errors

1. **EADDRINUSE Error:**
   ```bash
   npx react-native start --port=8082
   ```
   > Metro Bundler is already running on port 8081. Use the above command to start on a different port.

2. **Gradle Build Error:**
   ```bash
   rm -rf ~/.gradle
   ```
   > Clear the Gradle cache to resolve build issues.

### General Tips

- Ensure your device/emulator is properly configured.
- Restart Metro Bundler and the emulator if needed.

---

## Resources

- [React Native Documentation](https://reactnative.dev/)
- [Metro Bundler Documentation](https://facebook.github.io/metro/)

---

## Contributing

Feel free to submit pull requests or suggest improvements. Fork the repository and contribute to making the app even better!

---

