# Dice Roller

A single-screen app with a **Roll** button that shows a random dice face from 1 to 6.

Built while following Google's [Android Basics with Compose](https://developer.android.com/courses/android-basics-compose/course) course (the "Dice Roller" codelab).

## Features

- Tap **Roll** to get a random number between 1 and 6
- Shows the matching dice image

## Built with

- Kotlin, Jetpack Compose, Material 3
- Compose state with `remember { mutableStateOf(...) }` driving recomposition
- Min SDK 24, target/compile SDK 35

## Run it

1. Open the project folder in Android Studio and let Gradle sync.
2. Run the `app` configuration on an emulator or device (Android 7.0 / API 24 or newer).

Or, with a device or emulator connected:

```sh
./gradlew installDebug
```
