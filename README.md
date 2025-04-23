 # TidalTasks AI

TidalTasks AI is an AI-powered scheduling and productivity app tailored for high-school and university students. It integrates advanced features like Google Calendar sync, AI-driven study session planning, and a chatbot assistant to optimize time management and reduce stress.

---

## Features

### Core Functionalities
- **Dashboard**: 
  - Displays tasks, events, deadlines, and study sessions in a prioritized and user-friendly layout.
  - Provides insights and actionable items at a glance.

- **Calendar**:
  - Full integration with Google Calendar for syncing tasks and events.
  - Visualize all scheduled activities in one place.

- **Study Sessions**:
  - AI-planned study sessions using techniques like the Pomodoro method.
  - Includes features like mini-quizzes and adaptive breaks.
  - A dedicated view for ongoing, completed, and upcoming sessions.

- **Analytics**:
  - Visualize productivity trends and time usage.
  - Track progress in completing tasks, events, and study sessions.

- **Chatbot**:
  - Quickly create tasks, events, and study sessions via a conversational interface.
  - Provides assistance during study sessions and resolves scheduling conflicts.

- **Settings**:
  - Configure syncing preferences, notification settings, and app themes.

---

## Installation

### Prerequisites
- **Node.js** (v16 or later)
- **React** (v18 or later)
- **Vite**
- **Next.js** (v13 or later)
- **Firebase Project** with the following services enabled:
  - Authentication
  - Firestore Database
  - Cloud Functions

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/DhairyaS450/track-ai-web.git
   cd track-ai-web
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Set up Firebase:
   - Create a Firebase project in the [Firebase Console](https://console.firebase.google.com/).
   - Enable required Firebase services.
   - Download the `firebase-service-account.json` file for server-side usage.
   - Add Firebase configuration to your environment variables.

4. Start the server:
   ```bash
   npm run start
   ```

---

## Usage

### Initial Setup
1. Connect your Google account to sync tasks and events.
2. Configure app settings, including notification preferences and study session parameters.

### Key Workflows
- **Create Tasks/Events**:
  - Use the chatbot or manual entry to add tasks/events.
  - Sync them with Google Calendar.

- **Plan Study Sessions**:
  - Define goals, duration, and techniques like Pomodoro.
  - Let AI suggest optimal study times.
