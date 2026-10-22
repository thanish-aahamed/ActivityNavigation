# Activity Navigation App (Kotlin)

A simple Android application created to practice Activity navigation, button click handling, and explicit Intents in Kotlin.

## 📱 Features

- **Main Activity (`MainActivity.kt`)**: Displays a title and a button labeled **Second Activity**.
- **Second Activity (`SecondActivity.kt`)**: Displays a welcome screen navigating from `MainActivity`.
- **Button Click Handling**: Uses `setOnClickListener` to trigger navigation.
- **Explicit Intent**: Demonstrates how to navigate from `MainActivity` to `SecondActivity` using `Intent(this, SecondActivity::class.java)`.

## 📁 Key File Structure

```text
app/src/main/java/com/example/activitynavigation/
├── MainActivity.kt        # Handles button click and starts SecondActivity
└── SecondActivity.kt      # Displays Second Activity screen

app/src/main/res/layout/
├── activity_main.xml      # Layout containing the button
└── activity_second.xml    # Layout for second activity
```

## 🚀 How to Run

1. Open the project in **Android Studio**.
2. Sync Gradle files.
3. Select an **Android Emulator** or connected physical device.
4. Click **Run** (`Shift + F10`).
