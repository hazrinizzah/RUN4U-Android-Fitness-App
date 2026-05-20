# 🏃‍♂️ RUN4U - All-in-One Fitness App

**RUN4U** is a comprehensive fitness application developed as a group project for **TTTK2323 Mobile Programming** at **The National University of Malaysia (UKM)**. It helps users stay active, track fitness metrics, plan meals, and stay motivated, all in one place.

---

## 📱 Description

RUN4U is designed for individuals of all fitness levels who want to track their daily steps, monitor calorie and BMI, follow workout videos, join team workouts, listen to personalized music playlists, and plan their diet, all within a single mobile app.

The app aims to solve common fitness challenges such as lack of motivation, difficulty tracking progress, and the need for personalized dietary guidance.

---

## ✨ Key Features

- 🔐 **Login & Register** (Firebase Authentication)
- 🏠 **Home Screen**
- 🦶 **Step Tracker** (using phone sensors)
- 🧮 **BMI Calculator** with category & save to local database
- 🔥 **Calorie Calculator** with daily food entries & pie chart visualization
- 🥗 **Diet Planner** with animated recipe cards
- 📹 **Workout Videos** categorized by muscle groups (Legs, Abs, Chest, Back)
- 🎵 **Personalized Music Playlist** (add, play, delete local audio files)
- 👥 **Team Workout** with ZEGOCLOUD video conferencing
- 💾 **Local data persistence** using Room Database

---

## 🛠️ Tech Stack & Android Components

| Technology | Purpose |
|------------|---------|
| Kotlin | Main programming language |
| Jetpack Compose | UI toolkit |
| Firebase Authentication | User login/signup |
| Room Database | Local data storage |
| ViewModel & StateFlow | UI state management |
| Kotlin Coroutines | Async operations |
| SensorEventListener | Step detection |
| ZEGOCLOUD API | Video conferencing |
| MediaPlayer API | Music playback |
| RecyclerView | Display playlists & lists |
| Material 3 | UI components & animations |

---

## 📱 App Screenshots

### 🔐 Authentication
![Login Screen](https://github.com/hazrinizzah/RUN4U-Android-Fitness-App/blob/6957c28582d3e177cb6fdc3126533efe8016ec49/screenshots/login.jpg?raw=true)

### 🏠 Main Menu
![Main Menu](https://github.com/hazrinizzah/RUN4U-Android-Fitness-App/blob/6957c28582d3e177cb6fdc3126533efe8016ec49/screenshots/mainmenu.jpg?raw=true)

### 📊 BMI & Calorie Tracking
![BMI Calculator](https://github.com/hazrinizzah/RUN4U-Android-Fitness-App/blob/6957c28582d3e177cb6fdc3126533efe8016ec49/screenshots/bmicalculator.jpg?raw=true)
![BMI History](https://github.com/hazrinizzah/RUN4U-Android-Fitness-App/blob/6957c28582d3e177cb6fdc3126533efe8016ec49/screenshots/bmihistory.jpg?raw=true)
![Calories Calculator](https://github.com/hazrinizzah/RUN4U-Android-Fitness-App/blob/6957c28582d3e177cb6fdc3126533efe8016ec49/screenshots/caloriescalculator.jpg?raw=true)
![Food Category Calorie Calculator](https://github.com/hazrinizzah/RUN4U-Android-Fitness-App/blob/6957c28582d3e177cb6fdc3126533efe8016ec49/screenshots/foodcategorycaloriecalculator.jpg?raw=true)

### 🥗 Diet Planner
![Diet Planner](https://github.com/hazrinizzah/RUN4U-Android-Fitness-App/blob/6957c28582d3e177cb6fdc3126533efe8016ec49/screenshots/dietplanner.jpg?raw=true)

### 👟 Step Tracker
![Step Tracker](https://github.com/hazrinizzah/RUN4U-Android-Fitness-App/blob/6957c28582d3e177cb6fdc3126533efe8016ec49/screenshots/steptracker.jpg?raw=true)

### 💪 Workout Videos
![Workout Video](https://github.com/hazrinizzah/RUN4U-Android-Fitness-App/blob/6957c28582d3e177cb6fdc3126533efe8016ec49/screenshots/workoutvideojpg.jpg?raw=true)
![Workout Video 2](https://github.com/hazrinizzah/RUN4U-Android-Fitness-App/blob/6957c28582d3e177cb6fdc3126533efe8016ec49/screenshots/workoutvideo2.jpg?raw=true)

### 🎵 Music Playlist
![Music Playlist](https://github.com/hazrinizzah/RUN4U-Android-Fitness-App/blob/6957c28582d3e177cb6fdc3126533efe8016ec49/screenshots/musicplaylist.jpg?raw=true)

### 👥 Team Workout
![Team Workout](https://github.com/hazrinizzah/RUN4U-Android-Fitness-App/blob/6957c28582d3e177cb6fdc3126533efe8016ec49/screenshots/teamworkout.jpg?raw=true)

---

## 📸 Screenshot Gallery

<div align="center">
  <h3>Authentication & Main Menu</h3>
  <img src="https://github.com/hazrinizzah/RUN4U-Android-Fitness-App/blob/6957c28582d3e177cb6fdc3126533efe8016ec49/screenshots/login.jpg?raw=true" width="200" alt="Login"/>
  <img src="https://github.com/hazrinizzah/RUN4U-Android-Fitness-App/blob/6957c28582d3e177cb6fdc3126533efe8016ec49/screenshots/mainmenu.jpg?raw=true" width="200" alt="Main Menu"/>
  
  <h3>BMI & Calorie Tracking</h3>
  <img src="https://github.com/hazrinizzah/RUN4U-Android-Fitness-App/blob/6957c28582d3e177cb6fdc3126533efe8016ec49/screenshots/bmicalculator.jpg?raw=true" width="200" alt="BMI Calculator"/>
  <img src="https://github.com/hazrinizzah/RUN4U-Android-Fitness-App/blob/6957c28582d3e177cb6fdc3126533efe8016ec49/screenshots/bmihistory.jpg?raw=true" width="200" alt="BMI History"/>
  <img src="https://github.com/hazrinizzah/RUN4U-Android-Fitness-App/blob/6957c28582d3e177cb6fdc3126533efe8016ec49/screenshots/caloriescalculator.jpg?raw=true" width="200" alt="Calories Calculator"/>
  <img src="https://github.com/hazrinizzah/RUN4U-Android-Fitness-App/blob/6957c28582d3e177cb6fdc3126533efe8016ec49/screenshots/foodcategorycaloriecalculator.jpg?raw=true" width="200" alt="Food Category Calorie"/>
  
  <h3>Diet & Step Tracking</h3>
  <img src="https://github.com/hazrinizzah/RUN4U-Android-Fitness-App/blob/6957c28582d3e177cb6fdc3126533efe8016ec49/screenshots/dietplanner.jpg?raw=true" width="200" alt="Diet Planner"/>
  <img src="https://github.com/hazrinizzah/RUN4U-Android-Fitness-App/blob/6957c28582d3e177cb6fdc3126533efe8016ec49/screenshots/steptracker.jpg?raw=true" width="200" alt="Step Tracker"/>
  
  <h3>Workout Videos</h3>
  <img src="https://github.com/hazrinizzah/RUN4U-Android-Fitness-App/blob/6957c28582d3e177cb6fdc3126533efe8016ec49/screenshots/workoutvideojpg.jpg?raw=true" width="200" alt="Workout Video"/>
  <img src="https://github.com/hazrinizzah/RUN4U-Android-Fitness-App/blob/6957c28582d3e177cb6fdc3126533efe8016ec49/screenshots/workoutvideo2.jpg?raw=true" width="200" alt="Workout Video 2"/>
  
  <h3>Music & Team Workout</h3>
  <img src="https://github.com/hazrinizzah/RUN4U-Android-Fitness-App/blob/6957c28582d3e177cb6fdc3126533efe8016ec49/screenshots/musicplaylist.jpg?raw=true" width="200" alt="Music Playlist"/>
  <img src="https://github.com/hazrinizzah/RUN4U-Android-Fitness-App/blob/6957c28582d3e177cb6fdc3126533efe8016ec49/screenshots/teamworkout.jpg?raw=true" width="200" alt="Team Workout"/>
</div>

---

## 🚀 How to Run the Project

### Prerequisites
- Android Studio (Arctic Fox or newer)
- Android device or emulator (API 24+)
- Internet connection for first-time setup

### Step 1: Clone the repository
```bash
git clone https://github.com/hazrinizzah/RUN4U-Android-Fitness-App.git
