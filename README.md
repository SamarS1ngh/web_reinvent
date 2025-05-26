# Flutter Todo List App

A clean and modern todo list application built with Flutter. This app demonstrates basic Flutter UI components, state management, and user interactions in a simple yet elegant todo list interface.

## Features

- Clean and modern Material Design 3 UI
- Add new tasks with a title
- Mark tasks as complete/incomplete
- Delete tasks (swipe or button)
- Beautiful animations and transitions
- Responsive design
- Custom theme with gradient background

## Screenshots
![b4986e9d-47ad-4d7b-83ae-c00321cbf44c](https://github.com/user-attachments/assets/7683424f-5e05-4cf1-811b-5817218d0572)

![47ce8750-c33d-4f75-8a1e-1b50e5fe388d](https://github.com/user-attachments/assets/6c3db8b6-33b3-4843-8c14-d6890c065677)

![0465ed05-c470-4882-965d-ebd666a47fa7](https://github.com/user-attachments/assets/8bdc0c85-0c04-414a-a7a6-e61a7a2f1d03)

![1172430d-07e5-404f-be2a-6f2b7bbf7a44](https://github.com/user-attachments/assets/8dc3bedb-d8c4-44bd-a2c2-3abd8794cfdc)

## Getting Started

### Prerequisites

- Flutter SDK (latest version)
- Dart SDK (latest version)
- Android Studio / VS Code with Flutter extensions
- Git

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/todo_app.git
   ```

2. Navigate to the project directory:
   ```bash
   cd todo_app
   ```

3. Install dependencies:
   ```bash
   flutter pub get
   ```

4. Run the app:
   ```bash
   flutter run
   ```

## Project Structure

```
lib/
├── main.dart                 # App entry point and theme configuration
├── models/
│   └── task.dart            # Task model class
├── screens/
│   └── home_screen.dart     # Main screen widget
└── widgets/
    ├── empty_tasks.dart     # Empty state widget
    ├── task_input.dart      # Task input field widget
    └── task_list.dart       # Task list widget
```

## Usage

### Adding a Task
1. Type your task in the input field at the top
2. Press Enter or tap the "Add" button

### Managing Tasks
- **Complete a task**: Tap the checkbox on the left of the task
- **Delete a task**: 
  - Swipe the task from right to left
  - OR tap the delete icon on the right of the task

## Features in Detail

### Task Management
- Add new tasks with a simple input field
- Mark tasks as complete/incomplete with a checkbox
- Delete tasks with a swipe gesture or delete button
- Visual feedback for completed tasks (strikethrough text)

### User Interface
- Material Design 3 components
- Custom color scheme
- Gradient background
- Card-based task items
- Responsive layout
- Empty state with helpful message

### Animations and Interactions
- Smooth swipe-to-delete animation
- Task completion animation
- Snackbar notifications
- Interactive feedback on user actions

## Dependencies

The project uses the following main dependencies:
- Flutter SDK
- Material Design 3
