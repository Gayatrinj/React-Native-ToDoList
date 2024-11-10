# React-Native-ToDo

This is a new [**React Native**](https://reactnative.dev) project, bootstrapped using [`@react-native-community/cli`](https://github.com/react-native-community/cli).

# Getting Started

> **Note**: Make sure you have completed the [React Native - Environment Setup](https://reactnative.dev/docs/environment-setup) instructions up to the "Creating a new application" step before proceeding.

## Step 1: Start the Metro Server

First, you will need to start **Metro**, the JavaScript _bundler_ that ships _with_ React Native.

To start Metro, run the following command from the _root_ of your React Native project:

```bash
npx react-native start
```
Step 2: Start your Application
Let Metro Bundler run in its own terminal. Open a new terminal from the root of your React Native project. Run the following command to start your Android or iOS app:


For Android
```bash

npx react-native run-android
```
For iOS

```bash

npx react-native run-ios
```
If everything is set up correctly, you should see your new app running in your Android Emulator or iOS Simulator shortly, provided you have set up your emulator/simulator correctly.

This is one way to run your app — you can also run it directly from within Android Studio and Xcode, respectively.

Step 3: Modifying your App
Now that you have successfully run the app, let's modify it.

Open App.tsx in your text editor of choice and edit some lines.

For Android: Press the <kbd>R</kbd> key twice or select "Reload" from the Developer Menu (<kbd>Ctrl</kbd> + <kbd>M</kbd> on Windows and Linux, or <kbd>Cmd ⌘</kbd> + <kbd>M</kbd> on macOS) to see your changes.

For iOS: Hit <kbd>Cmd ⌘</kbd> + <kbd>R</kbd> in your iOS Simulator to reload the app and see your changes.

## Congratulations! 🎉
You've successfully run and modified your React Native App. 🥳

Now what?
If you want to add this new React Native code to an existing application, check out the Integration guide.
If you're curious to learn more about React Native, check out the Introduction to React Native.
Troubleshooting
If you can't get this to work, see the Troubleshooting page.

### Learn More
To learn more about React Native, take a look at the following resources:

React Native Website - learn more about React Native.
Getting Started - an overview of React Native and how to set up your environment.
Learn the Basics - a guided tour of the React Native basics.
Blog - read the latest official React Native Blog posts.
@facebook/react-native - the Open Source GitHub repository for React Native.

### Explanation of Changes
- **Metro Server**: Updated to `npx react-native start` to ensure consistency with the CLI approach.
- **Android and iOS Commands**: Changed to `npx react-native run-android` and `npx react-native run-ios`, as recommended by the React Native CLI community.

### Steps to Update and Push to GitHub

1. Open your `README.md` file in a text editor.
2. Replace the content with the updated version above.
3. Save the file.
4. Open your terminal in the project directory and run the following commands:

   ```bash
   git add README.md
   git commit -m "Update README with React Native CLI commands"
   git push origin main
```