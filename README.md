# TasksHub – Persistent Storage & Local Notifications

TasksHub is a mobile application developed using React Native and Expo as part of Mobile Application Development Practical Tutorial 07.

The application helps students manage their daily tasks, save personal profile details, and receive local notifications.

## Features

- **Task Management:** Add tasks with a task name and description.
- **Persistent Storage:** Store tasks and profile details using AsyncStorage.
- **Dashboard:** View saved tasks on the Home screen.
- **Local Notifications:** Receive notifications when a task is saved.
- **Student Profile:** Save student name and student ID.
- **Image Picker:** Select a profile picture from the device gallery.
- **Clear Data:** Clear all locally stored application data.

## Technologies Used

- React Native
- Expo
- TypeScript
- Expo Router
- AsyncStorage
- Expo Notifications
- Expo Image Picker

## Project Structure

```text
src/
└── app/
    ├── _layout.tsx
    ├── add-task.tsx
    └── (tabs)/
        ├── _layout.tsx
        ├── index.tsx
        └── profile.tsx

output_screens/
```

## Installation and Setup

1. Clone the repository:

```bash
git clone https://github.com/kaveesha64/TasksHub.git
```

2. Navigate to the project folder:

```bash
cd TasksHub
```

3. Install dependencies:

```bash
npm install
```

4. Start the Expo development server:

```bash
npx expo start
```

## Screenshots

Application screenshots and Image Picker proof are available in the `output_screens` folder.

## Author

Developed as part of the Mobile Application Development Practical Tutorial 07.

**Project Name:** TasksHub

**Repository:** https://github.com/kaveesha64/TasksHub