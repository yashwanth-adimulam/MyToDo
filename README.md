# MyToDo
Hey there! 👋 This is a simple todo list app I built using Kotlin in Android Studio. It's pretty basic, but it gets the job done!

## Tech Stuff
I made this using Android Studio Koala version 2024.1.1 Patch 2 and Gradle version 8.7. If you're using different versions, you might need to tweak some things.

## How It Works
### First Look
![image](https://github.com/user-attachments/assets/26ff612b-5c02-4518-abfb-0539334f1939)

This is what you'll see when you open the app.

### Adding Tasks
![image](https://github.com/user-attachments/assets/95f691b4-4cfa-4642-90b8-907a55d29bdd)

Just type your task and hit "Add Todo".

### Checking Off Tasks
![image](https://github.com/user-attachments/assets/6be8057f-1979-4381-afc2-560a7eb52111)

Finished a task? Just tick the box next to it.

### Cleaning Up
![image](https://github.com/user-attachments/assets/60c58ac6-b6bb-4af9-800a-35b99dce57aa)

Hit "Delete Done" to clear out all those completed tasks. Goodbye, clutter!

## Want to Try It Out?
1. If you're feeling brave, just clone this repo and run it. Should work if you've got the same Android Studio and Gradle versions.
2. Or, start a new project in Android Studio. Make sure you pick "Empty Views Activity" (not just "Empty Activity").
3. You'll only need to mess with five files to get this working:
   - In `app/src/main/java/com/example/<your_project_name>`:
     - `MainActivity.kt`
     - `ToDo.kt`
     - `ToDoAdapter.kt`
   - In `app/src/main/res/layout`:
     - `activity_main.xml`
     - `item_todo.xml`

## Heads Up!

This app isn't perfect yet. It doesn't save your tasks between sessions (no database connection). But don't worry, I'm working on that! I'll update this repo soon with that fancy feature.

Feel free to play around with the code. If you come up with any cool improvements, let me know!
