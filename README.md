# Flutter Todo App

A simple Flutter-based Todo application that includes a splash screen, a validated login screen, and a task management system with local data storage.

# Features
🔹 Splash Screen
Displays app title "Todo App"
Automatically navigates to the login screen after a delay
# Login Screen
Form-based login UI
Email and password input fields
Input validation:
Email must be in valid format
Password must be at least 6 characters
Show/Hide password functionality
Navigation to home screen after successful validation
"Forgot Password" and "Sign Up" options (UI only)
# Todo Screen (Home)
Add new tasks
Update existing tasks
Delete tasks using swipe gesture
Tasks are stored locally using SharedPreferences
# App Flow
Splash Screen
Login Screen (with validation)
Todo Screen (task management)
# Technologies Used
Flutter
Dart
SharedPreferences (for local task storage)
# Project Structure
lib/
├── screens/
│   ├── splash_screen.dart
│   ├── login_screen.dart
│   └── home.dart
├── main.dart
# Getting Started
1. Clone the Repository
git clone https://github.com/your-username/flutter-todo-app.git
2. Navigate to Project Folder
cd flutter-todo-app
3. Install Dependencies
flutter pub get
4. Run the App
flutter run
# Login Screen Details
Uses Form with GlobalKey<FormState>
Email validation using regex pattern
Password validation:
Cannot be empty
Minimum 6 characters required
Password visibility toggle using setState
On successful validation:
Navigates to HomePage using Navigator.push
# Task Management
Tasks are stored locally using SharedPreferences
User can:
Add task
Edit task
Delete task (swipe gesture)
Data persists after app restart
# Future Improvements
Implement real authentication (Firebase/Auth API)
Connect login with backend
Improve UI/UX design
Add task categories or priorities
# Author
Muhammad Younas