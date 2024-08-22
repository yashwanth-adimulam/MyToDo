# MyToDo
## This is repo for a simple todo list using Kotlin in Android Studio

This project is build on Android Studio Koala version - 2024.1.1 Patch 2 and gradle version 8.7

## Workings of this project
### This is the load screen
![image](https://github.com/user-attachments/assets/26ff612b-5c02-4518-abfb-0539334f1939)

### To add a task simply just type and press on "Add Todo" button
![image](https://github.com/user-attachments/assets/95f691b4-4cfa-4642-90b8-907a55d29bdd)

### You can mark the completed tasks by ticking the checkbox beside every todo
![image](https://github.com/user-attachments/assets/6be8057f-1979-4381-afc2-560a7eb52111)

### You can delete the completed tasks by pressing on the "Delete Done" button
![image](https://github.com/user-attachments/assets/60c58ac6-b6bb-4af9-800a-35b99dce57aa)

## Build this repo in your local system
1. You can directly clone this repo using git clone command and if you have the same versions for Android Studio and Gradle this should work fine
2. Else you can also choose to build a new project in Android Studio (make sure that you choose "Empty Views Activity" not "Empty Activity" option while making a new project)
3. And there are just five flies that you need to modify inorder to build this project
4. Those five files are "MainActivity.kt", "ToDo.kt", "ToDoAdapter.kt" in the app/src/main/java/com/example/<name_of_your_project> folder
5. And "activity_main.xml", "item_todo.xml" in the app/src/main/res/layout folder

## Note:

Please note that this is not a complete todo. It in its current version doesn't have any database connected such that the tasks can be carried on between session.

Database connection for this app is currently in works and the repo will be updated in a short period of time with the feature.
