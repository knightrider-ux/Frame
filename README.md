# Frame

Frame - A minimalistic Tasks app available for [Web](https://todoist-todo.firebaseapp.com/) and [Android](https://github.com/sanskar10100/Frame/releases/download/v1.0/Frame.1.0.apk) featuring realtime sync.

## Demo

https://user-images.githubusercontent.com/22092047/131017643-657ad552-2e9c-4ebf-be83-675c319a7dd3.mp4

## Light Mode
![Frame Light](https://user-images.githubusercontent.com/22092047/131018323-13863c58-cb3b-4958-a0a9-a82d50d6cba7.png)

## Dark Mode
![Frame Dark](https://user-images.githubusercontent.com/22092047/131018606-2bffbe37-9e45-4d06-8ce6-4742370e78dc.png)



## Stack
- Android SDK API 30
- Kotlin
- Clean MVVM Architecture
- Firebase (Auth and RTDB)
- Navigation Component & ktx
- Coil Image Loading Library
- Lottie

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
