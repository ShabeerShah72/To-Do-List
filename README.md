# ✅ Flutter To-Do List App

A **minimalist, efficient, and user-friendly** To-Do List app built using **Flutter**. Designed to help users manage and organize daily tasks with priority, notes, and reminders—all in a clean, elegant interface.

> Designed & developed by **Shabeer Shah**

---

## ✨ Features

- 📋 Add, view, edit, and delete tasks
- ✅ Mark tasks as completed with stylish **strikethrough + grey text**
- 📆 Select **due date & time** with an intuitive picker
- 🔺 Set **task priority** (Low / Medium / High)
- 🗒 Attach **optional notes** to each task
- 👆 Long-press a task to view **overlay with notes**
- 🎯 **Default onboarding tasks** (disappear after first real task is added)
- 🔘 **Custom round checkbox** UI
- 🔄 **In-memory storage** using a `Task` model class

---

## 🖼️ Screenshots

| 

---

## 🚀 Getting Started

### ✅ Prerequisites

- Flutter SDK (`>=3.0.0`)
- Dart SDK
- VS Code / Android Studio

  ###Project Structure
lib/
├── main.dart            # App entry point, navigation, Home screen
├── EditTaskPage.dart    # UI & logic for creating/editing tasks
├── task_model.dart      # Task class with properties (title, notes, date, etc.)
├── IntroPage.dart       # Optional onboarding/splash screen
└── assets/              # App icons, fonts, images, etc.


### Future Improvements
Persistent local storage (e.g. Hive, Shared Preferences, SQLite)

Light/Dark mode toggle

Notification/reminder alerts

Task categories and filters

Drag & drop task sorting

###👤 Author
Shabeer Shah
🔗 GitHub
📧 shabeershah.business@gmail.com
💼 LinkedIn Syed Shabeer Abbas Shah


### 📦 Installation

```bash
git clone https://github.com/shabeerShah72/flutter-todo-list-app.git
cd flutter-todo-list-app
flutter pub get
flutter run
---
