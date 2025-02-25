# MS-app
Messaging and streaming app
# Streaming & Messaging App

## Overview
This project is a powerful Android application for streaming movies, music, and audiobooks while integrating secure messaging, cloud storage, and additional features like a notepad/diary. The app prioritizes user privacy and security with encrypted storage and decentralized cloud options.

## Features
### Streaming
- **Movies & TV Shows**: Supports multiple sources with subtitle integration, playback speed control, and Picture-in-Picture (PiP) mode.
- **Music**: Integrated with SoundCloud, YouTube, and Spotify (notifying users about YouTube's background restrictions). Includes search, playlists, and history.
- **Audiobooks & Books**: In-app audiobook player with speed control, sleep timer, bookmarks, and listen-later feature.
- **DLNA Casting**: Allows streaming content to a TV while keeping the phone free for other tasks.

### Download Management
- Multi-threaded downloads for faster speeds.
- Background downloads with pause/resume and failure retries.
- Wi-Fi-only download option.
- Cloud storage option (Storj) with synchronization and usage tracking.

### Messaging System (XMPP-based)
- One-to-one and group messaging with end-to-end encryption.
- File & image sharing (Storj integration).
- Read receipts & typing indicators.
- Message reactions & user reporting.
- Self-destructing messages in private chats.
- 666-Rule enforcement: Users who delete 666 messages are banned from a group.

### Notepad & Diary
- Secure, encrypted storage with cloud backup.
- Image support for diary entries.
- Dark mode enforced across the entire app.

### User Authentication
- **Seed Phrase Recovery**: Similar to Coinbase wallets, ensuring account recovery without password resets.
- **Anonymous & Secure Login**: Users receive a generated password via email (not stored by the system).

## Installation
### Backend Setup
1. **Set up XMPP Server (Prosody)**
   - Install Prosody and configure for secure messaging.
   - Enable message encryption, file sharing, and group chats.

2. **Set up Storj for Cloud Storage**
   - Create an account on Storj.
   - Generate API credentials and configure the app to sync data.

### Android App Setup
1. **Clone the Repository**
   ```sh
   git clone https://github.com/your-repo/streaming-messaging-app.git
   cd streaming-messaging-app
   ```

2. **Open in Android Studio**
   - Import the project into Android Studio.
   - Ensure Kotlin and necessary dependencies are installed.

3. **Configure API Keys**
   - Add Storj API keys.
   - Set up XMPP credentials.
   - Configure streaming source APIs.

4. **Build and Run**
   - Compile and install the app on an Android device.

## Usage
1. **Streaming Content**
   - Search and watch movies, TV shows, music, and audiobooks.
   - Download content for offline viewing.
   - Cast videos to a TV via DLNA.

2. **Messaging**
   - Securely chat with other users.
   - Share images and files through Storj cloud.
   - Enable disappearing messages in private chats.

3. **Notepad & Diary**
   - Create encrypted notes.
   - Attach images.
   - Sync with cloud storage for backup.

## Roadmap
- Implement AI-powered recommendations.
- Improve UI/UX for seamless navigation.
- Introduce more streaming sources.
- Enhance security features further.

## License
This project is licensed under [MIT License](LICENSE).

---
### Support & Contribution
Feel free to submit issues or contribute via pull requests on GitHub. Suggestions and improvements are always welcome!

