> **A YouTube-Inspired, Browser-Based Local Video Player.**

Tired of the cluttered and dated interfaces of traditional media players like VLC or PotPlayer? **LuminaStream** is a lightweight, privacy-focused web application designed to bring the seamless "web-native" experience of YouTube to your local offline media files.

---

Most desktop video players feel like software from a decade ago. As a developer and student, I am most comfortable with the navigation, shortcuts, and fluid UI of modern web platforms. I built LuminaStream to bridge the gap between **local storage performance** and **modern web UX**.

---

## ✨ Key Features
### 🎮 YouTube-Style Navigation
Full implementation of standard web-player hotkeys for an intuitive experience:
* **Space**: Play/Pause
* **J / L**: Seek 10s Backward/Forward
* **F**: Toggle Fullscreen
* **M**: Mute/Unmute
* **Top Slider**: dynamic volume boosting.

### 📂 Smart Folder Explorer
No more opening files one by one. LuminaStream uses the **WebkitDirectory API** to scan entire SSD directories:
* **Recursive Scanning**: Maps all sub-folders and video files into a clean tree structure.
* **Title Wrapping**: Long movie titles are fully readable—no more truncated text.
* **Visited Tracking**: Folders you have explored are automatically highlighted in **Yellow** to help you track your progress.

### 🔊 500% Audio Boost
Built with the **Web Audio API**, the integrated GainNode allows you to boost audio levels up to **5x (500%)**. Perfect for low-gain audio tracks or quiet laptop speakers.

### 🧠 Intelligent Memory (Resume Playback)
Never lose your spot again. The player uses **LocalStorage** to remember the exact timestamp of every video. When you return to a video, it resumes precisely where you left off.

### 🎨 Fluent Glassmorphism UI
A sleek, dark-themed interface featuring:
* **Dynamic Sidebar**: A hover-sensitive sidebar that maximizes your viewing area.
* **Integrated Dashboard**: A "Home" view showing your recently watched sessions.
* **Responsive Design**: The player dynamically resizes to ensure controls are always reachable.

---

## 🛠️ Tech Stack

* **Frontend**: HTML5, Tailwind CSS 
* **Logic**: Vanilla JavaScript 
* **Audio Engine**: Web Audio API 
* **Storage**: Browser LocalStorage API 
* **Icons**: FontAwesome 6

---

## 🚀 How to Use

1. Download the `index.html` file.
2. Open it in any modern browser (Chrome, Edge, Brave).
3. Click **"add Folder"** and select your media directory.
4. Bookmark the page for instant access to your local library!

---

## 🔒 Privacy First
this is entirely **client-side**. No data is ever uploaded to a server. Your file paths, history, and video content stay strictly on your local machine.
