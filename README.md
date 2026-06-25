# 🎵 Survana - Android Music Player

Survana is a lightweight Android Music Player application developed using Java and Android Studio. The app automatically scans the device storage for MP3 audio files and provides a simple and user-friendly interface for music playback.

## 📱 Features

* Scan device storage for MP3 files
* Display all available songs in a ListView
* Play selected songs instantly
* Pause and resume playback
* Navigate between previous and next tracks
* Interactive seek bar for song progress control
* Dynamic runtime permission handling
* Smooth and responsive user interface

## 🛠️ Tech Stack

* Java
* Android Studio
* Android SDK
* MediaPlayer API
* Dexter Permission Library
* XML Layouts

## 📂 Project Structure

```
Survana/
│
├── app/
│   ├── src/main/java/com/example/survana/
│   │   ├── MainActivity.java
│   │   └── PlaySong.java
│   │
│   ├── res/layout/
│   │   ├── activity_main.xml
│   │   └── activity_play_song.xml
│   │
│   ├── res/drawable/
│   └── AndroidManifest.xml
│
└── README.md
```

## 🚀 How It Works

1. The application requests storage access permission.
2. It scans the device storage recursively for MP3 files.
3. All discovered songs are displayed in a list.
4. Users can select any song to start playback.
5. Playback controls allow:

   * Play/Pause
   * Next Song
   * Previous Song
   * Seek Through Audio

## ⚙️ Installation

### Clone the Repository

```bash
git clone https://github.com/mokshakamra/Survana.git
```

### Open in Android Studio

1. Launch Android Studio.
2. Select **Open Existing Project**.
3. Navigate to the cloned repository.
4. Sync Gradle files.

### Run the Application

1. Connect an Android device or start an emulator.
2. Build and run the project.
3. Grant storage permissions when prompted.
4. Enjoy your music.

## 📸 Screenshots

Add screenshots of:

* Song List Screen
* Music Playback Screen
* Seek Bar & Controls

## 🔮 Future Enhancements

* Playlist creation and management
* Shuffle and repeat modes
* Favorite songs section
* Background playback service
* Notification controls
* Album artwork support
* Dark mode UI
* Search functionality

## 🎯 Learning Outcomes

This project demonstrates:

* Android Activity Lifecycle
* Runtime Permission Handling
* File Management in Android
* MediaPlayer Integration
* Intent-based Navigation
* UI Development using XML
* Java Object-Oriented Programming

## 👨‍💻 Author

**Moksha Kamra**

B.Tech Undergraduate | Android Developer | Java Developer | AI/ML Enthusiast

## 📄 License

This project is open-source and available under the MIT License.
