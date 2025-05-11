# 📝 To-Do List App – Flutter

A clean, minimal, and efficient To-Do List app built using **Flutter**. It allows users to create, manage, and track their daily tasks with ease.

Designed and developed by **Shabeer Shah**.

---

## ✨ Features

- 📋 Add, view, and manage your tasks.
- ✅ Mark tasks as completed (with strikethrough and grey text).
- 🕓 Due date selection using a **date & time picker**.
- 🔺 Set task priority (Low / Medium / High).
- 🗒 Add optional **notes** to each task.
- 📤 Long-press on any task to reveal an overlay displaying its notes.
- 🆓 Comes with **default onboarding tasks** that automatically disappear after adding your first custom task.
- ☑️ Custom-styled round checkbox for cleaner UI.
- 🔄 Data saved in-memory using model integration (`Task` class).

---

## 🖼️ Screenshots

| Main Screen              | Add/Edit Task Screen        |
|--------------------------|-----------------------------|
| ![Main Screen](screenshots/main_screen.png) | ![Edit Screen](screenshots/edit_screen.png) |

---

## 🚀 Getting Started

### Prerequisites

- Flutter SDK (>=3.0)
- Dart
- VSCode

### Installation

```bash
git clone https://github.com/shabeerShah72/flutter-todo-list-app.git
cd flutter-todo-list-app
flutter pub get
flutter run

Project_Structure
/lib
│
├── main.dart              # Entry point, Home & Navigation logic
├── EditTaskPage.dart      # Page for creating or editing tasks
├── task_model.dart        # Task data model
├── IntroPage.dart         # Optional splash or intro page (if added)
└── assets/                # App icons, images, etc.

👤 Author
Shabeer Shah

If you like this project, feel free to ⭐ the repo or connect on LinkedIn!
