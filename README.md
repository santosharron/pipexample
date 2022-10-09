# Picture-in-picture (PiP) support
PiP is a special type of multi-window mode mostly used for video playback. It lets the user watch a video in a small window pinned to a corner of the screen while navigating between apps or browsing content on the main screen.

PiP leverages the multi-window APIs made available in Android 7.0 to provide the pinned video overlay window. To add PiP to your app, you need to register your activities that support PiP, switch your activity to PiP mode as needed, and make sure UI elements are hidden and video playback continues when the activity is in PiP mode.

The PiP window appears in the topmost layer of the screen, in a corner chosen by the system.

[![Preview](https://i.imgur.com/FIj2AWK.jpg)](https://youtu.be/JnvO-gRAm6E)

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.
