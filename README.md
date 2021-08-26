# Frame

Frame for Android - A minimalistic Tasks app available for [Web](https://todoist-todo.firebaseapp.com/) and [Android](https://github.com)

## Demo

Coming soon

## Stack
- Android SDK API 30
- Kotlin
- Clean MVVM Architecture
- Firebase (Auth and RTDB)
- Navigation Component & ktx

## Build

1. Clone the repo
```
git clone https://github.com/sanskar10100/Frame
```
2. Create a Firebase project and a rtdb with the following hierarchy:
```
users
|
<firebase uid>...
|
<auto-generated task id>...
|
item: String,
timestamp: Long (epoch)
status: String {pending, compeleted}
```
3. Add google-services.json to app directory and build.