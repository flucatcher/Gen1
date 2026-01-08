# 🧠 Gen 1 - AI Productivity Workspace

![Project Status](https://img.shields.io/badge/Status-Active-success)
![Tech Stack](https://img.shields.io/badge/Built_With-HTML_CSS_JS-blue)
![AI Power](https://img.shields.io/badge/AI-Google_Gemini-orange)

**Gen 1** is a local-first, aesthetic productivity dashboard designed to help students and professionals focus better. It combines Pomodoro timers, AI-powered scheduling, and ambient music into a fully customizable "Glassmorphism" interface.

> **Live Demo:** [Click here to view App](https://<YOUR-USERNAME>.github.io/<YOUR-REPO-NAME>/)
> *(Replace `<YOUR-USERNAME>` and `<YOUR-REPO-NAME>` with your actual link)*

---

## ✨ Key Features

### 🎯 Focus & Study Tools
* **Deep Focus Mode:** A distraction-free, fullscreen experience with a large timer and inspirational quotes.
* **Pomodoro Timer:** Built-in standard 25-minute timer to manage study sessions effectively.
* **Stats Tracking:** Visual charts tracking your total focus hours and daily consistency.

### 🤖 AI-Powered Scheduler (Gemini Integration)
* **Image-to-Schedule:** Upload a screenshot of your school/work timetable, and the AI (Gemini Flash) automatically extracts events and populates your calendar.
* **Smart Chat:** An embedded AI chatbot for quick questions, brainstorming, or study help without leaving the tab.

### 🎨 Customizable UI (Glassmorphism)
* **Draggable Widgets:** Chat, Music, Goals, and Stats widgets can be moved and resized anywhere on the screen.
* **Themes:** One-click switch between Light Mode and Dark Mode.
* **Dynamic Backgrounds:** Change wallpapers instantly via URL.

### 🎵 Ambient & Media
* **YouTube Music Player:** Integrated mini-player with playlist support (Custom Lofi/Study beats).
* **Ambient Sounds:** Built-in Rain, Fireplace, and Café noise generators for background focus.

---

## 🛠️ Tech Stack

* **Frontend:** HTML5, CSS3 (Advanced Animations & Glassmorphism), Vanilla JavaScript (ES6+).
* **AI Engine:** Google Gemini API (Model: `gemini-2.5-flash`).
* **Libraries:**
    * `Chart.js` (For statistics visualization).
    * `FontAwesome` (UI Icons).
    * `YouTube IFrame API` (Music player).
* **Storage:** `localStorage` (Browser-based data persistence for notes, settings, and schedules).

---

## 🚀 How to Use

### 1. Setup API Key (Crucial for AI Features)
Since this is a client-side application, you need your own Google Gemini API Key for the AI Chat and Schedule features to work.
1.  Get a free key at [Google AI Studio](https://aistudio.google.com/).
2.  Open **Gen 1**.
3.  Go to the **AI Schedule** tab (Wand icon).
4.  Enter your key in the "API Key" input and click **Save**.
    * *Note: Your key is saved locally in your browser and is never sent to any external server other than Google's API.*

### 2. Music Player
* The music player uses YouTube IDs. You can add any song by pasting a YouTube URL into the playlist panel.

### 3. Running Locally
Simply clone the repo and open `index.html`.
```bash
git clone [https://github.com/your-username/gen1-web.git](https://github.com/your-username/gen1-web.git)
cd gen1-web
# Open index.html in your browser
