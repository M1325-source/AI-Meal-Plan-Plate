# AI-Meal-Plan-Plate
Plan & Plate 🍽️

AI-Powered Meal Planning & Grocery Management App

Plan & Plate is an AI-powered Android application designed to simplify meal planning and grocery management. The app uses Google Gemini AI, Firebase Authentication, and Firestore to generate weekly meal plans and grocery lists tailored to user preferences.

🚀 Features

AI Meal Planning
Generates personalized weekly meal plans and grocery lists using Google Gemini AI.

Chat Interface
Users interact with the AI meal planner through a clean, conversational interface.

Firebase Authentication
Secure login and signup using Google or Email/Password.

Firestore Cloud Storage
Stores user-specific meal plans and grocery lists.

Weekly Meal Overview
Displays breakfast, lunch, and dinner for 7 days in a clear layout.

Grocery List Management
Automatically generated grocery list based on the meal plan.

User Profile
Shows user information with logout functionality.

Modern UI/UX
Clean screens, intuitive navigation, bottom navigation bar, and consistent design.

🏗️ Tech Stack

Frontend: Kotlin, Android Studio
Backend: Firebase Authentication, Firestore
AI Integration: Google Gemini API
Architecture: Clean Layout + Fragment Navigation
Database: Firestore Cloud Document Storage

📂 Project Structure (Highlight)
/app
 ├── activities
 │   ├── SplashActivity.kt
 │   ├── WelcomeActivity.kt
 │   └── MainActivity.kt
 ├── fragments
 │   ├── HomeFragment.kt
 │   ├── MealFragment.kt
 │   ├── GroceryFragment.kt
 │   └── ProfileFragment.kt
 ├── layout
 │   ├── activity_main.xml
 │   ├── activity_splash.xml
 │   ├── activity_welcome.xml
 │   ├── fragment_grocery.xml
 │   └── ... (others)

 🧠 How It Works

User logs in using Google or Email/Password.

User asks the AI meal planner via chat for a weekly plan.

Gemini AI returns structured weekly meals + grocery list.

Data is saved in Firestore under the logged-in user's profile.

Users can later view:

Meal Plan

Grocery List

Profile Information
🔐 Firebase Setup

Enable Firebase Authentication

Add Google Sign-In

Add Firestore database

Place your google-services.json in app/

Add Web Client ID in strings.xml


📱 App Screenshots

<img width="392" height="308" alt="image" src="https://github.com/user-attachments/assets/23592d52-d933-4831-9080-c888274a99fd" />
<img width="259" height="304" alt="image" src="https://github.com/user-attachments/assets/9ad89a66-968f-430c-bcaa-c9e89e3d40ac" />
<img width="307" height="182" alt="image" src="https://github.com/user-attachments/assets/118d3df5-d239-4c43-8f13-4173f792d200" />
<img width="268" height="308" alt="image" src="https://github.com/user-attachments/assets/d30039ce-7fd7-44c9-8055-2464947197cf" />
<img width="246" height="302" alt="image" src="https://github.com/user-attachments/assets/6a864dbc-15f3-448d-9217-b47da0d3fba5" />
<img width="253" height="298" alt="image" src="https://github.com/user-attachments/assets/a08f58bd-2e2b-4204-bcb2-852c16bb65ff" />
<img width="260" height="302" alt="image" src="https://github.com/user-attachments/assets/138bdf8f-fd0e-43f1-9c35-17d3d2a20e71" />
<img width="250" height="301" alt="image" src="https://github.com/user-attachments/assets/8de02572-f719-4fe0-ba8d-99e301c0d620" />


▶️ Installation & Setup

Clone this repository:

git clone https://github.com/yourusername/plan-and-plate.git


Open in Android Studio.

Add your Firebase configuration.

Add Gemini AI API keys where required.

Run the app on an emulator or device.

📘 Project Report

For a complete explanation of the app’s working, features, and UI, refer to the provided project report 

Plan & Plate 2 (1)

.

🙋‍♀️ Author

Manisha Priya
School of Computer Science and Engineering

⭐ Contributions

Pull requests are welcome!
If you’d like to improve UI, optimize data handling, or enhance AI integration, feel free to contribute.
