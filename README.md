# MyToDo

Hello and welcome! 👋 You've just stumbled upon **MyToDo**, a straightforward to-do list application developed using Kotlin in Android Studio. It’s designed to be simple yet functional, helping you keep track of your tasks efficiently.

## Technology Stack

This application was built using:
- **Android Studio Koala** version 2024.1.1 Patch 2
- **Gradle** version 8.7

If you're using different versions of these tools, you might need to make some adjustments to get everything working smoothly.

## Features

### Initial View
When you first open the app, you’ll be greeted with a clean and user-friendly interface:

![Initial View](https://github.com/user-attachments/assets/26ff612b-5c02-4518-abfb-0539334f1939)

### Adding Tasks
Adding new tasks is a breeze. Simply type your task into the input field and press "Add Todo" to include it in your list:

![Adding Tasks](https://github.com/user-attachments/assets/95f691b4-4cfa-4642-90b8-907a55d29bdd)

### Checking Off Tasks
Once you’ve completed a task, just check the box next to it to mark it as done:

![Checking Off Tasks](https://github.com/user-attachments/assets/6be8057f-1979-4381-afc2-560a7eb52111)

### Cleaning Up Completed Tasks
To keep your to-do list neat and tidy, use the "Delete Done" button to remove all completed tasks at once:

![Cleaning Up](https://github.com/user-attachments/assets/60c58ac6-b6bb-4af9-800a-35b99dce57aa)

## How to Get Started

Ready to give it a try? Here’s how you can set it up:

1. **Clone the Repository**:
   Clone this repo to your local machine. It should work seamlessly if you’re using the same versions of Android Studio and Gradle mentioned above.

2. **Create a New Project**:
   Alternatively, you can create a new project in Android Studio. Make sure to choose "Empty Views Activity" (not just "Empty Activity").

3. **Add the Files**:
   You’ll need to work with the following files to get everything running:
   - In `app/src/main/java/com/example/<your_project_name>`:
     - `MainActivity.kt`
     - `ToDo.kt`
     - `ToDoAdapter.kt`
   - In `app/src/main/res/layout`:
     - `activity_main.xml`
     - `item_todo.xml`

## Important Notes

This app is still a work in progress. Currently, it doesn’t save your tasks between sessions since it lacks a database connection. But don’t worry, I’m actively working on adding this feature and will update the repository soon.

Feel free to explore the code and make improvements. If you come up with any enhancements or have suggestions, I’d love to hear from you!

Enjoy using MyToDo, and happy task managing! 😊

