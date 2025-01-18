# Expo Linking.getInitialURL() returns null inconsistently on Android

This repository demonstrates a bug in Expo's `Linking.getInitialURL()` API where it inconsistently returns `null` on Android devices, even when a valid deep link is used to launch the application. This issue is particularly noticeable when launching the app from specific notifications or on certain Android versions.

The `bug.js` file contains a reproduction of the problem, while `bugSolution.js` shows a potential workaround involving event listeners and handling multiple `getInitialURL` attempts.