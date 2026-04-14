# Android Music Player Application

## 🚀 Author
Bojan Brankovic 

## Project Overview
This project is an Android Music Player Application designed to demonstrate core audio playback functionality, media handling, and user interaction within a mobile environment.

The application simulates a typical offline music player, allowing users to browse, manage, and play audio files stored on their device.

Modern Android music players commonly support multiple audio formats, playlist management, and playback controls such as shuffle, repeat, and equalizer settings. :contentReference[oaicite:0]{index=0}

## Features
- Play, pause, next, previous controls  
- Audio file playback (MP3, WAV, etc.)  
- Playlist creation and management  
- Music library browsing (songs, albums, artists)  
- Shuffle and repeat functionality  
- Background playback  
- Notification controls (if implemented)  

## Tech Stack
- Java / Kotlin (Android)
- Android SDK
- MediaPlayer API
- Android Studio

## Application Flow
1. User opens the app  
2. Music library is loaded from device storage  
3. User selects a song  
4. Playback starts  
5. User controls playback (pause, skip, shuffle, etc.)  

## Scope of Testing
- Audio playback functionality  
- File loading and media scanning  
- Playback controls (play/pause/next/previous)  
- Playlist behavior  
- Background playback and app lifecycle  
- UI responsiveness  

## Tools Used
- Manual Testing  
- Android Emulator / Real Device  
- Logcat (debugging)  

## Testing Types
- Functional Testing  
- UI/UX Testing  
- Exploratory Testing  
- Regression Testing  
- Performance Testing (basic)  

## Deliverables
- Test Cases  
- Bug Reports  
- Test Execution Report  

## Key Issues Identified
- Music playback stops when app goes to background  
- Some audio formats not supported  
- Playlist does not save after app restart  
- Delay when switching between songs  
- Notification controls not updating correctly  

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/devbojan/android-music-player-app.git
