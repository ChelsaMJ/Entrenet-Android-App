# Entrenet Android App

## Overview
Entrenet is an Android application designed to provide a platform for learning, networking, and engaging with entrepreneurs. It combines multiple features like reminders, skill-based entrepreneur discovery, AI-powered chat personalities, and personalized notifications - all in a clean, intuitive interface.

## Features

### Reminder
- Set alarms (requires exact alarm permission on Android 12+).
- Get reminders via notifications.
- Uses AlarmManager and NotificationChannel for scheduling and alerts.

### Find Entrepreneurs
- Browse a list of entrepreneurs with their skills and locations.
- Filter entrepreneurs by skill using a Spinner (dropdown).
- Select multiple entrepreneurs and view your selection in real-time.
- Data displayed via RecyclerView with an EntrepreneurAdapter.

### AI Chat (Gemini API)
- Chat with personalities like Elon Musk and Jeff Bezos.
- Messages are sent via Retrofit to the Gemini API.
- Includes typing indicators and error handling for failed requests.

### UI/UX
- Bottom Navigation for quick access to app sections.
- Navigation Drawer with shortcuts (Checklist, Announcements, Theme Picker, About Us).
- Floating Action Button (FAB) for instant chatbot access.
- Light/Dark/System Default Themes stored in SharedPreferences.
- Notifications and toasts for better interaction feedback.

## Tech Stack
- Language: Kotlin
- Framework: Android SDK
- Architecture: Fragment-based navigation
- API: Gemini API (via Retrofit)
- UI: RecyclerView, Spinner, DrawerLayout, Snackbar, Toast
- IDE: Android Studio

## Installation
1. Clone this repository:
   
   ```
   git clone https://github.com/ChelsaMJ/Entrenet-Android-App.git

   ```
3. Open the project in Android Studio.
4. Add your Gemini API key in the Retrofit service class.
5. Build and run the app on an emulator or physical device.

## Usage
- Navigate through the app using the bottom navigation bar.
- Use the navigation drawer for quick access to other features.
- Set reminders and receive notifications.
- Browse and filter entrepreneurs by skills.
- Chat with AI personalities using the chatbot.
